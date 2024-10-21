-- Gui to DonyDoors
-- Version: 0.1.2.5

-- Scripts:

local DonyDoors = Instance.new("ScreenGui")
local FrameSome = Instance.new("ScrollingFrame")
local Cheats = Instance.new("ImageLabel")
local NAME = Instance.new("TextLabel")
local DONYDOORS = Instance.new("TextLabel")
local ExpertInfo = Instance.new("TextLabel")
local ExpertInfo_2 = Instance.new("TextLabel")
local ExpertInfo_3 = Instance.new("TextLabel")
local Cheats2 = Instance.new("ImageLabel")
local ExpertInfo_4 = Instance.new("TextLabel")
local ExpertInfo_5 = Instance.new("TextLabel")
local ExpertInfo_6 = Instance.new("TextLabel")
local Cheats2_2 = Instance.new("ImageLabel")
local TextButton = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local TextButton_2 = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local UICorner_3 = Instance.new("UICorner")
local Close = Instance.new("ImageButton")
local UICorner_4 = Instance.new("UICorner")
local Close_2 = Instance.new("TextLabel")
local Open = Instance.new("ImageButton")
local UICorner_5 = Instance.new("UICorner")
local Close_3 = Instance.new("TextLabel")

--Properties:

DonyDoors.Name = "DonyDoors"
DonyDoors.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
DonyDoors.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

FrameSome.Name = "FrameSome"
FrameSome.Parent = DonyDoors
FrameSome.Active = true
FrameSome.BackgroundColor3 = Color3.fromRGB(121, 99, 87)
FrameSome.BorderColor3 = Color3.fromRGB(0, 0, 0)
FrameSome.BorderSizePixel = 0
FrameSome.Position = UDim2.new(0.182130262, 0, 0.185156882, 0)
FrameSome.Size = UDim2.new(0, 853, 0, 492)
FrameSome.ScrollBarThickness = 4

Cheats.Name = "Cheats"
Cheats.Parent = FrameSome
Cheats.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Cheats.BorderColor3 = Color3.fromRGB(0, 0, 0)
Cheats.BorderSizePixel = 0
Cheats.Position = UDim2.new(0, 0, 0.0529182851, 0)
Cheats.Size = UDim2.new(0, 853, 0, 465)
Cheats.Image = "http://www.roblox.com/asset/?id=107715730080724"

NAME.Name = "NAME"
NAME.Parent = Cheats
NAME.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
NAME.BackgroundTransparency = 1.000
NAME.BorderColor3 = Color3.fromRGB(0, 0, 0)
NAME.BorderSizePixel = 0
NAME.Position = UDim2.new(0.0246189926, 0, -0.156989247, 0)
NAME.Size = UDim2.new(0, 217, 0, 47)
NAME.Font = Enum.Font.Oswald
NAME.Text = "Dony X BlackKing + Mspaint"
NAME.TextColor3 = Color3.fromRGB(255, 225, 184)
NAME.TextScaled = true
NAME.TextSize = 14.000
NAME.TextWrapped = true

DONYDOORS.Name = "DONYDOORS"
DONYDOORS.Parent = Cheats
DONYDOORS.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
DONYDOORS.BackgroundTransparency = 1.000
DONYDOORS.BorderColor3 = Color3.fromRGB(0, 0, 0)
DONYDOORS.BorderSizePixel = 0
DONYDOORS.Position = UDim2.new(0.382180542, 0, -0.156989247, 0)
DONYDOORS.Size = UDim2.new(0, 217, 0, 47)
DONYDOORS.Font = Enum.Font.Oswald
DONYDOORS.Text = "DonyDoors 1.0.2.5"
DONYDOORS.TextColor3 = Color3.fromRGB(255, 225, 184)
DONYDOORS.TextScaled = true
DONYDOORS.TextSize = 14.000
DONYDOORS.TextWrapped = true

ExpertInfo.Name = "ExpertInfo"
ExpertInfo.Parent = Cheats
ExpertInfo.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ExpertInfo.BackgroundTransparency = 1.000
ExpertInfo.BorderColor3 = Color3.fromRGB(0, 0, 0)
ExpertInfo.BorderSizePixel = 0
ExpertInfo.Position = UDim2.new(0.0656506419, 0, 0.195698932, 0)
ExpertInfo.Size = UDim2.new(0, 200, 0, 50)
ExpertInfo.Font = Enum.Font.Oswald
ExpertInfo.Text = "Player"
ExpertInfo.TextColor3 = Color3.fromRGB(255, 223, 179)
ExpertInfo.TextScaled = true
ExpertInfo.TextSize = 14.000
ExpertInfo.TextWrapped = true

ExpertInfo_2.Name = "ExpertInfo"
ExpertInfo_2.Parent = Cheats
ExpertInfo_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ExpertInfo_2.BackgroundTransparency = 1.000
ExpertInfo_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
ExpertInfo_2.BorderSizePixel = 0
ExpertInfo_2.Position = UDim2.new(0.382180542, 0, -0.0559139773, 0)
ExpertInfo_2.Size = UDim2.new(0, 200, 0, 50)
ExpertInfo_2.Font = Enum.Font.Oswald
ExpertInfo_2.Text = "Visual"
ExpertInfo_2.TextColor3 = Color3.fromRGB(255, 223, 179)
ExpertInfo_2.TextScaled = true
ExpertInfo_2.TextSize = 14.000
ExpertInfo_2.TextWrapped = true

ExpertInfo_3.Name = "ExpertInfo"
ExpertInfo_3.Parent = Cheats
ExpertInfo_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ExpertInfo_3.BackgroundTransparency = 1.000
ExpertInfo_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
ExpertInfo_3.BorderSizePixel = 0
ExpertInfo_3.Position = UDim2.new(0.679953098, 0, -0.107526883, 0)
ExpertInfo_3.Size = UDim2.new(0, 200, 0, 50)
ExpertInfo_3.Font = Enum.Font.Oswald
ExpertInfo_3.Text = "Anti or Auto"
ExpertInfo_3.TextColor3 = Color3.fromRGB(255, 223, 179)
ExpertInfo_3.TextScaled = true
ExpertInfo_3.TextSize = 14.000
ExpertInfo_3.TextWrapped = true

Cheats2.Name = "Cheats2"
Cheats2.Parent = FrameSome
Cheats2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Cheats2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Cheats2.BorderSizePixel = 0
Cheats2.Position = UDim2.new(-0.00117233291, 0, 0.381744832, 0)
Cheats2.Size = UDim2.new(0, 853, 0, 248)
Cheats2.Image = "http://www.roblox.com/asset/?id=111255955278935"

ExpertInfo_4.Name = "ExpertInfo"
ExpertInfo_4.Parent = Cheats2
ExpertInfo_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ExpertInfo_4.BackgroundTransparency = 1.000
ExpertInfo_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
ExpertInfo_4.BorderSizePixel = 0
ExpertInfo_4.Position = UDim2.new(0.0668229759, 0, -0.207526907, 0)
ExpertInfo_4.Size = UDim2.new(0, 200, 0, 50)
ExpertInfo_4.Font = Enum.Font.Oswald
ExpertInfo_4.Text = "Player2"
ExpertInfo_4.TextColor3 = Color3.fromRGB(255, 223, 179)
ExpertInfo_4.TextScaled = true
ExpertInfo_4.TextSize = 14.000
ExpertInfo_4.TextWrapped = true

ExpertInfo_5.Name = "ExpertInfo"
ExpertInfo_5.Parent = Cheats2
ExpertInfo_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ExpertInfo_5.BackgroundTransparency = 1.000
ExpertInfo_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
ExpertInfo_5.BorderSizePixel = 0
ExpertInfo_5.Position = UDim2.new(0.348182887, 0, -0.20510754, 0)
ExpertInfo_5.Size = UDim2.new(0, 200, 0, 50)
ExpertInfo_5.Font = Enum.Font.Oswald
ExpertInfo_5.Text = "Visual2"
ExpertInfo_5.TextColor3 = Color3.fromRGB(255, 223, 179)
ExpertInfo_5.TextScaled = true
ExpertInfo_5.TextSize = 14.000
ExpertInfo_5.TextWrapped = true

ExpertInfo_6.Name = "ExpertInfo"
ExpertInfo_6.Parent = Cheats2
ExpertInfo_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ExpertInfo_6.BackgroundTransparency = 1.000
ExpertInfo_6.BorderColor3 = Color3.fromRGB(0, 0, 0)
ExpertInfo_6.BorderSizePixel = 0
ExpertInfo_6.Position = UDim2.new(0.679953098, 0, -0.107526883, 0)
ExpertInfo_6.Size = UDim2.new(0, 200, 0, 50)
ExpertInfo_6.Font = Enum.Font.Oswald
ExpertInfo_6.Text = "Extra (Extreme)"
ExpertInfo_6.TextColor3 = Color3.fromRGB(255, 223, 179)
ExpertInfo_6.TextScaled = true
ExpertInfo_6.TextSize = 14.000
ExpertInfo_6.TextWrapped = true

Cheats2_2.Name = "Cheats2"
Cheats2_2.Parent = Cheats2
Cheats2_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Cheats2_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Cheats2_2.BorderSizePixel = 0
Cheats2_2.Position = UDim2.new(0, 0, 0.999835372, 0)
Cheats2_2.Size = UDim2.new(0, 853, 0, 453)
Cheats2_2.Image = "http://www.roblox.com/asset/?id=96520178495163"

TextButton.Parent = FrameSome
TextButton.BackgroundColor3 = Color3.fromRGB(217, 198, 155)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.636576772, 0, 0.789098442, 0)
TextButton.Size = UDim2.new(0, 209, 0, 47)
TextButton.Font = Enum.Font.Oswald
TextButton.Text = "GodMode"
TextButton.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

UICorner.CornerRadius = UDim.new(0, 17)
UICorner.Parent = TextButton

TextButton_2.Parent = FrameSome
TextButton_2.BackgroundColor3 = Color3.fromRGB(217, 198, 155)
TextButton_2.BackgroundTransparency = 1.000
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0.0914419666, 0, 0.851654708, 0)
TextButton_2.Size = UDim2.new(0, 411, 0, 85)
TextButton_2.Font = Enum.Font.Oswald
TextButton_2.Text = "Credits: To dony, + BlackkingCheat, +  Mspaint = DonyDoors"
TextButton_2.TextColor3 = Color3.fromRGB(255, 220, 181)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 14.000
TextButton_2.TextWrapped = true

UICorner_2.CornerRadius = UDim.new(0, 17)
UICorner_2.Parent = TextButton_2

UICorner_3.CornerRadius = UDim.new(0, 17)
UICorner_3.Parent = FrameSome

Close.Name = "Close"
Close.Parent = DonyDoors
Close.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Close.BackgroundTransparency = 0.500
Close.BorderColor3 = Color3.fromRGB(0, 0, 0)
Close.BorderSizePixel = 0
Close.Position = UDim2.new(0.0847222209, 0, 0.145496532, 0)
Close.Size = UDim2.new(0, 100, 0, 100)
Close.Image = "rbxassetid://13001544489"

UICorner_4.Parent = Close

Close_2.Name = "Close"
Close_2.Parent = Close
Close_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Close_2.BackgroundTransparency = 1.000
Close_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Close_2.BorderSizePixel = 0
Close_2.Position = UDim2.new(0, 0, 0.589999974, 0)
Close_2.Size = UDim2.new(0, 100, 0, 34)
Close_2.Font = Enum.Font.Oswald
Close_2.Text = "Close"
Close_2.TextColor3 = Color3.fromRGB(255, 237, 193)
Close_2.TextScaled = true
Close_2.TextSize = 14.000
Close_2.TextWrapped = true

Open.Name = "Open"
Open.Parent = DonyDoors
Open.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Open.BackgroundTransparency = 0.500
Open.BorderColor3 = Color3.fromRGB(0, 0, 0)
Open.BorderSizePixel = 0
Open.Position = UDim2.new(0.0847222209, 0, 0.290993065, 0)
Open.Size = UDim2.new(0, 100, 0, 100)
Open.Image = "rbxassetid://86753363652238"

UICorner_5.Parent = Open

Close_3.Name = "Close"
Close_3.Parent = Open
Close_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Close_3.BackgroundTransparency = 1.000
Close_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
Close_3.BorderSizePixel = 0
Close_3.Position = UDim2.new(0, 0, 0.589999974, 0)
Close_3.Size = UDim2.new(0, 100, 0, 34)
Close_3.Font = Enum.Font.Oswald
Close_3.Text = "Open"
Close_3.TextColor3 = Color3.fromRGB(255, 237, 193)
Close_3.TextScaled = true
Close_3.TextSize = 14.000
Close_3.TextWrapped = true

-- Scripts:

local function KICUEVO_fake_script() -- Close.Script 
	local script = Instance.new('Script', Close)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.FrameSome.Visible = false
	end)
end
coroutine.wrap(KICUEVO_fake_script)()
local function SQFEGF_fake_script() -- Open.Script 
	local script = Instance.new('Script', Open)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.FrameSome.Visible = true
	end)
end
coroutine.wrap(SQFEGF_fake_script)()
