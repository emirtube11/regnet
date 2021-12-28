-- You Are Trying To Steal Huh? why?
-- You cant





































--stop












































--cant

























































--STOP






































































--Oke ican wait you












































































--Stop Okay?



local key = Instance.new("ScreenGui")
local keysystem = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local key_2 = Instance.new("TextBox")
local UICorner_2 = Instance.new("UICorner")
local check = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local Main = Instance.new("Frame")

--Properties:

key.Name = "key"
key.Parent = game.CoreGui
key.ZIndexBehavior = Enum.ZIndexBehavior.Sibling


keysystem.Name = "keysystem"
keysystem.Parent = key
keysystem.BackgroundColor3 = Color3.fromRGB(124, 124, 124)
keysystem.Position = UDim2.new(0.311386526, 0, 0.264150918, 0)
keysystem.Size = UDim2.new(0, 487, 0, 299)
keysystem.Active = true
keysystem.Draggable = true

UICorner.Parent = keysystem

TextLabel.Parent = keysystem
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Size = UDim2.new(0, 487, 0, 90)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Key System"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

key_2.Name = "key"
key_2.Parent = keysystem
key_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
key_2.Position = UDim2.new(0.199178651, 0, 0.389334798, 0)
key_2.Size = UDim2.new(0, 292, 0, 86)
key_2.Font = Enum.Font.SourceSans
key_2.Text = "Key Here"
key_2.TextColor3 = Color3.fromRGB(0, 0, 0)
key_2.TextScaled = true
key_2.TextSize = 14.000
key_2.TextTransparency = 0.500
key_2.TextWrapped = true

UICorner_2.Parent = key_2

check.Name = "check"
check.Parent = keysystem
check.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
check.Position = UDim2.new(0.209445596, 0, 0.762541831, 0)
check.Size = UDim2.new(0, 282, 0, 50)
check.Font = Enum.Font.SourceSans
check.Text = "Check"
check.TextColor3 = Color3.fromRGB(255, 255, 255)
check.TextScaled = true
check.TextSize = 14.000
check.MouseButton1Down:connect(function()
	local key = key_2
	if key.Text == "EmirHubV3" then -- Make the "Key" whatever you wish.
		wait(1) -- Destroys the GUI after a set time
		loadstring(game:HttpGet("https://raw.githubusercontent.com/emirtube11/crack1/main/README.md",true))()
    key.Text = "Welcome To Emir HUB V3!"
		 wait(1)
    key.Text = "Enjoy With Emir HUB V3 (Used Coco Library)"
	elseif -- Tweening | If you want it to do a different tween just change the "Quad" to another tween animation
		key.Text == "" then
		key.Text = "" else
		key.Text = "Incorrect, try again."
		wait(1)
		key.Text = "Key Here"
	end
	UICorner_3.Parent = check

end)
