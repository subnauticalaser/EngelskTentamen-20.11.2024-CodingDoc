# ReadMe System - Roblox Lua


## Text


### addText

Adds Text too your ReadMe File with the following arguments.

`Arguments`

`Text`: Required - The Text that is displayed. \
`Color`: Optional - If you want to use Color in the Text. Define it with Color3 like `Color3.fromRGB(red, green, blue)`, use [`ColorSlider`](https://www.google.com/search?q=color+slider&sca_esv=6436e396b7e6bdff&rlz=1C1GCEU_enNO1101NO1101&sxsrf=ADLYWIJOrEPtlZffwENon4R9RUfH6u19aQ%3A1732091252233&ei=dJ09Z_XzDbiQ1fIPh_208QQ&ved=0ahUKEwj1_brevuqJAxU4SFUIHYc-LU4Q4dUDCA8&uact=5&oq=color+slider&gs_lp=Egxnd3Mtd2l6LXNlcnAiDGNvbG9yIHNsaWRlcjILEAAYgAQYkQIYigUyBRAAGIAEMgoQABiABBhDGIoFMgsQABiABBiRAhiKBTIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABEj8MVDyH1ioMXAGeAGQAQCYAYkBoAHaCKoBBDEwLjK4AQPIAQD4AQGYAhKgAqUKwgIKEAAYsAMY1gQYR8ICDRAAGIAEGLADGEMYigXCAgsQLhiABBjRAxjHAcICBRAuGIAEwgINEAAYgAQYQxjJAxiKBcICCxAAGIAEGJIDGIoFwgILEC4YgAQYxwEYrwGYAwCIBgGQBgqSBwQxMy41oAelTQ&sclient=gws-wiz-serp) to make your color, and copy the `RGB Section`. [It is not Required] `Default Color: Color3.fromRGB(255, 255, 255)`.



`Exsample Code`

```lua
ReadmeModule.addText({
    Text = 'Exsample Text', -- Text
    Color = Color3.new(1, 0, 0) -- Red
})
```

`Exsample Return`

What the Function should return, if successfull.

```md
$\textsf{\color{#ffff00}{GG}}$
```

`Exsample View`

What the Content should look like.




$\textsf{\color{#ffff00}{GG}}$



### addHeaderText

Adds a Header Text too your ReadMe File with the following arguments.

`Arguments`

`Text`: Required - The Header Text that is displayed. \
`Size`: Optional - Set the Size of the Header, in the range of: 1 to 4. [Default: 1]


`Exsample Code`

```lua
local Text = Readme.Readme.addHeaderText({
	Text = 'GG',
	Size = 4
})
```


`Exsample Return`

What the Function should return, if successfull.

```md
#### GG
```


`Exsample View`

What the Content should look like.


#### GG
