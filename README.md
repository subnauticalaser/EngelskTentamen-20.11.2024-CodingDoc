# ReadMe System - Roblox Lua


## Text


### addText

Adds Text too your ReadMe File with the following arguments.


`Text`: Required - The Text that is displayed. \
`Color`: Optional - If you want to use Color in the Text. Define it with Color3 like `Color3.fromRGB(red, green, blue)`, use [`ColorSlider`](https://www.google.com/search?q=color+slider&sca_esv=6436e396b7e6bdff&rlz=1C1GCEU_enNO1101NO1101&sxsrf=ADLYWIJOrEPtlZffwENon4R9RUfH6u19aQ%3A1732091252233&ei=dJ09Z_XzDbiQ1fIPh_208QQ&ved=0ahUKEwj1_brevuqJAxU4SFUIHYc-LU4Q4dUDCA8&uact=5&oq=color+slider&gs_lp=Egxnd3Mtd2l6LXNlcnAiDGNvbG9yIHNsaWRlcjILEAAYgAQYkQIYigUyBRAAGIAEMgoQABiABBhDGIoFMgsQABiABBiRAhiKBTIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABEj8MVDyH1ioMXAGeAGQAQCYAYkBoAHaCKoBBDEwLjK4AQPIAQD4AQGYAhKgAqUKwgIKEAAYsAMY1gQYR8ICDRAAGIAEGLADGEMYigXCAgsQLhiABBjRAxjHAcICBRAuGIAEwgINEAAYgAQYQxjJAxiKBcICCxAAGIAEGJIDGIoFwgILEC4YgAQYxwEYrwGYAwCIBgGQBgqSBwQxMy41oAelTQ&sclient=gws-wiz-serp). [It is not Required] `Default Color: Color3.new(1, 0, 0)`.


```lua
ReadmeModule.addText({
    Text = 'Exsample Text', -- Text
    Color = Color3.new(1, 0, 0) -- Red
})
```
