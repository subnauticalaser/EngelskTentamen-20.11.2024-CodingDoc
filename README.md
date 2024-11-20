# ReadMe System - Roblox Lua


## Text


### addText

Adds Text too your ReadMe File with the following arguments.

`Arguments`

`Text`: Required - The Text that is displayed. \
`Color`: Optional - If you want to use Color in the Text. Define it with Color3 like `Color3.fromRGB(red, green, blue)`, use [`ColorSlider`](https://www.google.com/search?q=color+slider&sca_esv=6436e396b7e6bdff&rlz=1C1GCEU_enNO1101NO1101&sxsrf=ADLYWIJOrEPtlZffwENon4R9RUfH6u19aQ%3A1732091252233&ei=dJ09Z_XzDbiQ1fIPh_208QQ&ved=0ahUKEwj1_brevuqJAxU4SFUIHYc-LU4Q4dUDCA8&uact=5&oq=color+slider&gs_lp=Egxnd3Mtd2l6LXNlcnAiDGNvbG9yIHNsaWRlcjILEAAYgAQYkQIYigUyBRAAGIAEMgoQABiABBhDGIoFMgsQABiABBiRAhiKBTIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABEj8MVDyH1ioMXAGeAGQAQCYAYkBoAHaCKoBBDEwLjK4AQPIAQD4AQGYAhKgAqUKwgIKEAAYsAMY1gQYR8ICDRAAGIAEGLADGEMYigXCAgsQLhiABBjRAxjHAcICBRAuGIAEwgINEAAYgAQYQxjJAxiKBcICCxAAGIAEGJIDGIoFwgILEC4YgAQYxwEYrwGYAwCIBgGQBgqSBwQxMy41oAelTQ&sclient=gws-wiz-serp) to make your color, and copy the `RGB Section`. [It is not Required] `Default Color: Color3.fromRGB(255, 255, 255)`.



`returns`

`string` - The Content that if placed in a '.md' file, will show up with the text, and the Color [if Provided].


`Exsample Code`

```lua
ReadmeModule.addText({
    Text = 'Exsample Text', -- Text
    Color = Color3.new(1, 0, 0) -- Red
})
```

`Exsample Return`

What the Function should return, if successfull.

```txt
<span style="color: rgb(255, 255, 0);">GG</span>
```

`Exsample View`

What the Content should look like.



<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 55 20" fill="none">
    <text x="0" y="15" fill="#4285f4">G</text>
    <text x="12" y="15" fill="#ea4335">o</text>
    <text x="21" y="15" fill="#fbbc05">o</text>
    <text x="30" y="15" fill="#4285f4">g</text>
    <text x="40" y="15" fill="#389738">l</text>
    <text x="45" y="15" fill="#ea4335">e</text>
</svg>

