## Create Window
```
local lib = loadstring(game:HttpGet("https://raw.githubusercontent.com/rainhitgrassed/Slixx-ui-library/refs/heads/main/source"))();
lib = Library:NewWindow("Yon", "Search")
```
## Create Tab
```lua
local t1 = lib:NewTab("Catching")
```
## Create Toggle
```lua
t1:NewToggle("Magnets", false, function(v)
	Configurations.Enabled = v
end)
```
## Create Slider
```lua
t1:NewSlider("X Size", 0, 25, 5, function(v)
	Configurations.Sizes.XSize = v
end)
```
