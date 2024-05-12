# Ocerium UI
Credit To The Owner

# Creating A Library
```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/slf0Dev/Ocerium_Project/main/Library.lua"))()
```


# Creating a window
```lua
Window = Library.Main("Your Text","LeftAlt") -- change "LeftAlt" to key that you want will hide gui
```

# Adding tabs and sections
```lua
local Tab = Window.NewTab("Your Tab Text")
```

# Adding Section
```lua
local Section = Tab.NewSection("Section Text")
```

# Creating A Toggle
```lua
local EnabledToggle = Section.NewToggle("Enabled Toggle",function(bool)
-- code here
end,true) -- "true" is the default value of toggle
```

# Creating A Disabled Toggle
```lua
local DisabledToggle = Section.NewToggle("Disabled Toggle",function(bool)
-- code here
end,false) -- "false" is the default value of toggle
```

# Adding Sliders
```lua
local SliderPrecise = section.NewSlider("Slider precise",0,100,true,function(value)

end,25)
local SliderNotPrecise = section.NewSlider("Slider not precise",0,100,false,function(value)

end,75)
```
