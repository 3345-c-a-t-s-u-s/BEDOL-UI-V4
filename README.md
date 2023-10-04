# BEDOL-UI-V4
```lua
local ui = require(script.ModuleScript)

local window = ui:AddWindow()

local tab1 = window:AddTab("ads")
local tab2 = window:AddTab("earth")

local sec = tab1:AddSection("Section Kub")

sec:AddButton('Buttons',function()
	print('button')
end)

sec:AddLabel("aLabel")

sec:AddToggle("Toggle",false,function(a)
	print('toggle',a)
end)

sec:AddSlider('Slider',5,100,55,"%",function(a)
	print('slider',a)
end)

sec:AddDropdown('Dropdown',{1,2,3},1,function(a) 
	print('dropdown',a)
end)

```
