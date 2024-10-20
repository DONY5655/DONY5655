--dony created new script
--for noobs

local DtoorsPanel3 = Instance.new("ScreenGui")
local ScrollingFrame = Instance.new("ScrollingFrame")
local UICorner = Instance.new("UICorner")
local UIGradient = Instance.new("UIGradient")
local BOTTLE = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local BOTTLE_2 = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local BOTTLE_3 = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local Frame = Instance.new("Frame")
local FOV = Instance.new("TextBox")
local UICorner_5 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local UICorner_6 = Instance.new("UICorner")
local UICorner_7 = Instance.new("UICorner")
local GiveItem = Instance.new("Frame")
local STAR = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local UICorner_9 = Instance.new("UICorner")
local SPIRAL = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local MOON = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local CRUCIFIX = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local CRUCIFIX2 = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local CRUCIFIX3 = Instance.new("TextButton")
local UICorner_14 = Instance.new("UICorner")
local VITAMINS = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local LOCKPICK = Instance.new("TextButton")
local UICorner_16 = Instance.new("UICorner")
local BOTTLE_4 = Instance.new("TextButton")
local UICorner_17 = Instance.new("UICorner")
local STARVIAL = Instance.new("TextButton")
local UICorner_18 = Instance.new("UICorner")
local SKELETONKEY = Instance.new("TextButton")
local UICorner_19 = Instance.new("UICorner")
local BOTTLE_5 = Instance.new("TextButton")
local UICorner_20 = Instance.new("UICorner")
local Frame_2 = Instance.new("Frame")
local TextLabel_2 = Instance.new("TextLabel")
local TextBox = Instance.new("TextBox")
local UICorner_21 = Instance.new("UICorner")
local OK = Instance.new("TextButton")
local UICorner_22 = Instance.new("UICorner")
local UICorner_23 = Instance.new("UICorner")
local BOTTLE_6 = Instance.new("TextButton")
local UICorner_24 = Instance.new("UICorner")
local BOTTLE_7 = Instance.new("TextButton")
local UICorner_25 = Instance.new("UICorner")
local Frame_3 = Instance.new("Frame")
local up = Instance.new("TextButton")
local down = Instance.new("TextButton")
local onof = Instance.new("TextButton")
local TextLabel_3 = Instance.new("TextLabel")
local plus = Instance.new("TextButton")
local speed = Instance.new("TextLabel")
local mine = Instance.new("TextButton")
local Close = Instance.new("TextButton")
local minimize = Instance.new("TextButton")
local minimize2 = Instance.new("TextButton")
local Close_2 = Instance.new("TextButton")
local BOTTLE_8 = Instance.new("TextButton")
local UICorner_26 = Instance.new("UICorner")
local Achiviement = Instance.new("TextButton")
local UICorner_27 = Instance.new("UICorner")
local EVENT2 = Instance.new("TextButton")
local UICorner_28 = Instance.new("UICorner")
local Achiviement2 = Instance.new("TextButton")
local UICorner_29 = Instance.new("UICorner")
local EVENT2_2 = Instance.new("TextButton")
local UICorner_30 = Instance.new("UICorner")
local Achiviement3 = Instance.new("TextButton")
local UICorner_31 = Instance.new("UICorner")
local EVENT2_3 = Instance.new("TextButton")
local UICorner_32 = Instance.new("UICorner")
local Close_3 = Instance.new("ImageButton")
local UICorner_33 = Instance.new("UICorner")
local Open = Instance.new("ImageButton")
local UICorner_34 = Instance.new("UICorner")

--Properties:

DtoorsPanel3.Name = "DtoorsPanel3"
DtoorsPanel3.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
DtoorsPanel3.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

ScrollingFrame.Parent = DtoorsPanel3
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(86, 76, 61)
ScrollingFrame.BackgroundTransparency = 0.300
ScrollingFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScrollingFrame.BorderSizePixel = 0
ScrollingFrame.Position = UDim2.new(0.248611107, 0, 0.0277136266, 0)
ScrollingFrame.Size = UDim2.new(0, 757, 0, 818)
ScrollingFrame.CanvasPosition = Vector2.new(0, 914)
ScrollingFrame.ScrollBarThickness = 3
ScrollingFrame.VerticalScrollBarInset = Enum.ScrollBarInset.Always
ScrollingFrame.VerticalScrollBarPosition =
Enum.VerticalScrollBarPosition.Left

UICorner.CornerRadius = UDim.new(0, 17)
UICorner.Parent = ScrollingFrame

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00,
Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(0.22,
Color3.fromRGB(255, 84, 84)), ColorSequenceKeypoint.new(0.33,
Color3.fromRGB(255, 0, 0)), ColorSequenceKeypoint.new(0.53,
Color3.fromRGB(255, 65, 65)), ColorSequenceKeypoint.new(0.66,
Color3.fromRGB(255, 105, 105)), ColorSequenceKeypoint.new(0.70,
Color3.fromRGB(255, 120, 120)), ColorSequenceKeypoint.new(1.00,
Color3.fromRGB(255, 255, 255))}
UIGradient.Offset = Vector2.new(11, 11)
UIGradient.Rotation = 2
UIGradient.Parent = ScrollingFrame

BOTTLE.Name = "BOTTLE"
BOTTLE.Parent = ScrollingFrame
BOTTLE.BackgroundColor3 = Color3.fromRGB(157, 135, 91)
BOTTLE.BorderColor3 = Color3.fromRGB(0, 0, 0)
BOTTLE.BorderSizePixel = 0
BOTTLE.Position = UDim2.new(0.0928228647, 0, 0.100011624, 0)
BOTTLE.Size = UDim2.new(0, 600, 0, 56)
BOTTLE.Font = Enum.Font.Oswald
BOTTLE.Text = "AutoLoot"
BOTTLE.TextColor3 = Color3.fromRGB(255, 234, 171)
BOTTLE.TextScaled = true
BOTTLE.TextSize = 14.000
BOTTLE.TextWrapped = true

UICorner_2.Parent = BOTTLE

BOTTLE_2.Name = "BOTTLE"
BOTTLE_2.Parent = ScrollingFrame
BOTTLE_2.BackgroundColor3 = Color3.fromRGB(157, 135, 91)
BOTTLE_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
BOTTLE_2.BorderSizePixel = 0
BOTTLE_2.Position = UDim2.new(0.0928228647, 0, 0.141203746, 0)
BOTTLE_2.Size = UDim2.new(0, 600, 0, 56)
BOTTLE_2.Font = Enum.Font.Oswald
BOTTLE_2.Text = "FullBright"
BOTTLE_2.TextColor3 = Color3.fromRGB(255, 234, 171)
BOTTLE_2.TextScaled = true
BOTTLE_2.TextSize = 14.000
BOTTLE_2.TextWrapped = true

UICorner_3.Parent = BOTTLE_2

BOTTLE_3.Name = "BOTTLE"
BOTTLE_3.Parent = ScrollingFrame
BOTTLE_3.BackgroundColor3 = Color3.fromRGB(157, 135, 91)
BOTTLE_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
BOTTLE_3.BorderSizePixel = 0
BOTTLE_3.Position = UDim2.new(0.0928228647, 0, 0.187371656, 0)
BOTTLE_3.Size = UDim2.new(0, 600, 0, 56)
BOTTLE_3.Font = Enum.Font.Oswald
BOTTLE_3.Text = "dont flick lights"
BOTTLE_3.TextColor3 = Color3.fromRGB(255, 234, 171)
BOTTLE_3.TextScaled = true
BOTTLE_3.TextSize = 14.000
BOTTLE_3.TextWrapped = true

UICorner_4.Parent = BOTTLE_3

Frame.Parent = ScrollingFrame
Frame.BackgroundColor3 = Color3.fromRGB(108, 91, 70)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.134699747, 0, 0.222059622, 0)
Frame.Size = UDim2.new(0.730600476, 0, 0.0243295617, 0)

FOV.Name = "FOV"
FOV.Parent = Frame
FOV.BackgroundColor3 = Color3.fromRGB(131, 119, 78)
FOV.BorderColor3 = Color3.fromRGB(0, 0, 0)
FOV.BorderSizePixel = 0
FOV.Position = UDim2.new(0.398587286, 0, 0.0769230798, 0)
FOV.Size = UDim2.new(0.576368868, 0, 0.806451619, 0)
FOV.Font = Enum.Font.Oswald
FOV.PlaceholderColor3 = Color3.fromRGB(212, 212, 212)
FOV.PlaceholderText = "70"
FOV.Text = ""
FOV.TextColor3 = Color3.fromRGB(255, 207, 167)
FOV.TextScaled = true
FOV.TextSize = 14.000
FOV.TextWrapped = true

UICorner_5.Parent = FOV

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(145, 141, 93)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.125059277, 0, 0.0769229978, 0)
TextLabel.Size = UDim2.new(0.270893365, 0, 0.806451619, 0)
TextLabel.Font = Enum.Font.Oswald
TextLabel.Text = "FOV:"
TextLabel.TextColor3 = Color3.fromRGB(255, 223, 184)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

UICorner_6.Parent = TextLabel

UICorner_7.Parent = Frame

GiveItem.Name = "GiveItem"
GiveItem.Parent = ScrollingFrame
GiveItem.BackgroundColor3 = Color3.fromRGB(104, 90, 73)
GiveItem.BorderColor3 = Color3.fromRGB(0, 0, 0)
GiveItem.BorderSizePixel = 0
GiveItem.Position = UDim2.new(0.134535104, 0, 0.269487143, 0)
GiveItem.Size = UDim2.new(0, 592, 0, 827)

STAR.Name = "STAR"
STAR.Parent = GiveItem
STAR.BackgroundColor3 = Color3.fromRGB(202, 174, 117)
STAR.BorderColor3 = Color3.fromRGB(0, 0, 0)
STAR.BorderSizePixel = 0
STAR.Position = UDim2.new(0.0439189188, 0, 0.0314389355, 0)
STAR.Size = UDim2.new(0, 527, 0, 38)
STAR.Font = Enum.Font.Oswald
STAR.Text = "Give StarJug"
STAR.TextColor3 = Color3.fromRGB(255, 234, 171)
STAR.TextScaled = true
STAR.TextSize = 14.000
STAR.TextWrapped = true

UICorner_8.Parent = STAR

UICorner_9.CornerRadius = UDim.new(0, 17)
UICorner_9.Parent = GiveItem

SPIRAL.Name = "SPIRAL"
SPIRAL.Parent = GiveItem
SPIRAL.BackgroundColor3 = Color3.fromRGB(202, 174, 117)
SPIRAL.BorderColor3 = Color3.fromRGB(0, 0, 0)
SPIRAL.BorderSizePixel = 0
SPIRAL.Position = UDim2.new(0.0439189188, 0, 0.0991535708, 0)
SPIRAL.Size = UDim2.new(0, 527, 0, 38)
SPIRAL.Font = Enum.Font.Oswald
SPIRAL.Text = "Give SpiralJug"
SPIRAL.TextColor3 = Color3.fromRGB(255, 234, 171)
SPIRAL.TextScaled = true
SPIRAL.TextSize = 14.000
SPIRAL.TextWrapped = true

UICorner_10.Parent = SPIRAL

MOON.Name = "MOON"
MOON.Parent = GiveItem
MOON.BackgroundColor3 = Color3.fromRGB(202, 174, 117)
MOON.BorderColor3 = Color3.fromRGB(0, 0, 0)
MOON.BorderSizePixel = 0
MOON.Position = UDim2.new(0.0337837823, 0, 0.172914147, 0)
MOON.Size = UDim2.new(0, 527, 0, 38)
MOON.Font = Enum.Font.Oswald
MOON.Text = "Give MoonJug"
MOON.TextColor3 = Color3.fromRGB(255, 234, 171)
MOON.TextScaled = true
MOON.TextSize = 14.000
MOON.TextWrapped = true

UICorner_11.Parent = MOON

CRUCIFIX.Name = "CRUCIFIX"
CRUCIFIX.Parent = GiveItem
CRUCIFIX.BackgroundColor3 = Color3.fromRGB(202, 174, 117)
CRUCIFIX.BorderColor3 = Color3.fromRGB(0, 0, 0)
CRUCIFIX.BorderSizePixel = 0
CRUCIFIX.Position = UDim2.new(0.0337837823, 0, 0.2490931, 0)
CRUCIFIX.Size = UDim2.new(0, 527, 0, 38)
CRUCIFIX.Font = Enum.Font.Oswald
CRUCIFIX.Text = "Give Crucifix"
CRUCIFIX.TextColor3 = Color3.fromRGB(255, 234, 171)
CRUCIFIX.TextScaled = true
CRUCIFIX.TextSize = 14.000
CRUCIFIX.TextWrapped = true

UICorner_12.Parent = CRUCIFIX

CRUCIFIX2.Name = "CRUCIFIX2"
CRUCIFIX2.Parent = GiveItem
CRUCIFIX2.BackgroundColor3 = Color3.fromRGB(202, 174, 117)
CRUCIFIX2.BorderColor3 = Color3.fromRGB(0, 0, 0)
CRUCIFIX2.BorderSizePixel = 0
CRUCIFIX2.Position = UDim2.new(0.0337837823, 0, 0.327690452, 0)
CRUCIFIX2.Size = UDim2.new(0, 527, 0, 38)
CRUCIFIX2.Font = Enum.Font.Oswald
CRUCIFIX2.Text = "Give CuriousCrucifix"
CRUCIFIX2.TextColor3 = Color3.fromRGB(255, 234, 171)
CRUCIFIX2.TextScaled = true
CRUCIFIX2.TextSize = 14.000
CRUCIFIX2.TextWrapped = true

UICorner_13.Parent = CRUCIFIX2

CRUCIFIX3.Name = "CRUCIFIX3"
CRUCIFIX3.Parent = GiveItem
CRUCIFIX3.BackgroundColor3 = Color3.fromRGB(202, 174, 117)
CRUCIFIX3.BorderColor3 = Color3.fromRGB(0, 0, 0)
CRUCIFIX3.BorderSizePixel = 0
CRUCIFIX3.Position = UDim2.new(0.0337837823, 0, 0.40507859, 0)
CRUCIFIX3.Size = UDim2.new(0, 527, 0, 38)
CRUCIFIX3.Font = Enum.Font.Oswald
CRUCIFIX3.Text = "Give SpiralCrucifix"
CRUCIFIX3.TextColor3 = Color3.fromRGB(255, 234, 171)
CRUCIFIX3.TextScaled = true
CRUCIFIX3.TextSize = 14.000
CRUCIFIX3.TextWrapped = true

UICorner_14.Parent = CRUCIFIX3

VITAMINS.Name = "VITAMINS"
VITAMINS.Parent = GiveItem
VITAMINS.BackgroundColor3 = Color3.fromRGB(202, 174, 117)
VITAMINS.BorderColor3 = Color3.fromRGB(0, 0, 0)
VITAMINS.BorderSizePixel = 0
VITAMINS.Position = UDim2.new(0.0337837823, 0, 0.481257558, 0)
VITAMINS.Size = UDim2.new(0, 527, 0, 38)
VITAMINS.Font = Enum.Font.Oswald
VITAMINS.Text = "Vitamins"
VITAMINS.TextColor3 = Color3.fromRGB(255, 234, 171)
VITAMINS.TextScaled = true
VITAMINS.TextSize = 14.000
VITAMINS.TextWrapped = true

UICorner_15.Parent = VITAMINS

LOCKPICK.Name = "LOCKPICK"
LOCKPICK.Parent = GiveItem
LOCKPICK.BackgroundColor3 = Color3.fromRGB(202, 174, 117)
LOCKPICK.BorderColor3 = Color3.fromRGB(0, 0, 0)
LOCKPICK.BorderSizePixel = 0
LOCKPICK.Position = UDim2.new(0.0337837823, 0, 0.558645725, 0)
LOCKPICK.Size = UDim2.new(0, 527, 0, 38)
LOCKPICK.Font = Enum.Font.Oswald
LOCKPICK.Text = "Lockpick"
LOCKPICK.TextColor3 = Color3.fromRGB(255, 234, 171)
LOCKPICK.TextScaled = true
LOCKPICK.TextSize = 14.000
LOCKPICK.TextWrapped = true

UICorner_16.Parent = LOCKPICK

BOTTLE_4.Name = "BOTTLE"
BOTTLE_4.Parent = GiveItem
BOTTLE_4.BackgroundColor3 = Color3.fromRGB(202, 174, 117)
BOTTLE_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
BOTTLE_4.BorderSizePixel = 0
BOTTLE_4.Position = UDim2.new(0.0337837823, 0, 0.638452232, 0)
BOTTLE_4.Size = UDim2.new(0, 527, 0, 38)
BOTTLE_4.Font = Enum.Font.Oswald
BOTTLE_4.Text = "Bottle"
BOTTLE_4.TextColor3 = Color3.fromRGB(255, 234, 171)
BOTTLE_4.TextScaled = true
BOTTLE_4.TextSize = 14.000
BOTTLE_4.TextWrapped = true

UICorner_17.Parent = BOTTLE_4

STARVIAL.Name = "STARVIAL"
STARVIAL.Parent = GiveItem
STARVIAL.BackgroundColor3 = Color3.fromRGB(202, 174, 117)
STARVIAL.BorderColor3 = Color3.fromRGB(0, 0, 0)
STARVIAL.BorderSizePixel = 0
STARVIAL.Position = UDim2.new(0.0337837823, 0, 0.718258739, 0)
STARVIAL.Size = UDim2.new(0, 527, 0, 38)
STARVIAL.Font = Enum.Font.Oswald
STARVIAL.Text = "StarVial"
STARVIAL.TextColor3 = Color3.fromRGB(255, 234, 171)
STARVIAL.TextScaled = true
STARVIAL.TextSize = 14.000
STARVIAL.TextWrapped = true

UICorner_18.Parent = STARVIAL

SKELETONKEY.Name = "SKELETONKEY"
SKELETONKEY.Parent = GiveItem
SKELETONKEY.BackgroundColor3 = Color3.fromRGB(202, 174, 117)
SKELETONKEY.BorderColor3 = Color3.fromRGB(0, 0, 0)
SKELETONKEY.BorderSizePixel = 0
SKELETONKEY.Position = UDim2.new(0.0337837823, 0, 0.801692843, 0)
SKELETONKEY.Size = UDim2.new(0, 527, 0, 38)
SKELETONKEY.Font = Enum.Font.Oswald
SKELETONKEY.Text = "SkeletonKey"
SKELETONKEY.TextColor3 = Color3.fromRGB(255, 234, 171)
SKELETONKEY.TextScaled = true
SKELETONKEY.TextSize = 14.000
SKELETONKEY.TextWrapped = true

UICorner_19.Parent = SKELETONKEY

BOTTLE_5.Name = "BOTTLE"
BOTTLE_5.Parent = ScrollingFrame
BOTTLE_5.BackgroundColor3 = Color3.fromRGB(157, 135, 91)
BOTTLE_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
BOTTLE_5.BorderSizePixel = 0
BOTTLE_5.Position = UDim2.new(0.102476008, 0, 0.765110314, 0)
BOTTLE_5.Size = UDim2.new(0, 600, 0, 56)
BOTTLE_5.Font = Enum.Font.Oswald
BOTTLE_5.Text = "AntiCheat"
BOTTLE_5.TextColor3 = Color3.fromRGB(255, 234, 171)
BOTTLE_5.TextScaled = true
BOTTLE_5.TextSize = 14.000
BOTTLE_5.TextWrapped = true

UICorner_20.Parent = BOTTLE_5

Frame_2.Parent = ScrollingFrame
Frame_2.BackgroundColor3 = Color3.fromRGB(67, 64, 51)
Frame_2.BackgroundTransparency = 0.200
Frame_2.Position = UDim2.new(0.168433815, 0, 0.815644801, 0)
Frame_2.Size = UDim2.new(0, 490, 0, 127)

TextLabel_2.Parent = Frame_2
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 2.000
TextLabel_2.Position = UDim2.new(-0.065781571, 0, 0.0164525788, 0)
TextLabel_2.Size = UDim2.new(0, 508, 0, 54)
TextLabel_2.Font = Enum.Font.Oswald
TextLabel_2.Text = "WalkSpeed"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 216, 172)
TextLabel_2.TextSize = 28.000

TextBox.Parent = Frame_2
TextBox.BackgroundColor3 = Color3.fromRGB(121, 112, 93)
TextBox.Position = UDim2.new(0.0908834636, 0, 0.537407815, 0)
TextBox.Size = UDim2.new(0, 414, 0, 37)
TextBox.Font = Enum.Font.Cartoon
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox.TextSize = 30.000

UICorner_21.Parent = TextBox

OK.Name = "OK"
OK.Parent = Frame_2
OK.BackgroundColor3 = Color3.fromRGB(62, 56, 47)
OK.Position = UDim2.new(0.0315954089, 0, 1.11513972, 0)
OK.Size = UDim2.new(0, 468, 0, 41)
OK.Font = Enum.Font.Oswald
OK.Text = "Set SpeedBoost"
OK.TextColor3 = Color3.fromRGB(126, 111, 92)
OK.TextSize = 42.000

UICorner_22.Parent = OK

UICorner_23.Parent = Frame_2

BOTTLE_6.Name = "BOTTLE"
BOTTLE_6.Parent = ScrollingFrame
BOTTLE_6.BackgroundColor3 = Color3.fromRGB(157, 135, 91)
BOTTLE_6.BorderColor3 = Color3.fromRGB(0, 0, 0)
BOTTLE_6.BorderSizePixel = 0
BOTTLE_6.Position = UDim2.new(0.0901808515, 0, 0.940306842, 0)
BOTTLE_6.Size = UDim2.new(0, 600, 0, 56)
BOTTLE_6.Font = Enum.Font.Oswald
BOTTLE_6.Text = "Event"
BOTTLE_6.TextColor3 = Color3.fromRGB(255, 234, 171)
BOTTLE_6.TextScaled = true
BOTTLE_6.TextSize = 14.000
BOTTLE_6.TextWrapped = true

UICorner_24.Parent = BOTTLE_6

BOTTLE_7.Name = "BOTTLE"
BOTTLE_7.Parent = ScrollingFrame
BOTTLE_7.BackgroundColor3 = Color3.fromRGB(157, 135, 91)
BOTTLE_7.BorderColor3 = Color3.fromRGB(0, 0, 0)
BOTTLE_7.BorderSizePixel = 0
BOTTLE_7.Position = UDim2.new(0.0818660408, 0, 0.059690088, 0)
BOTTLE_7.Size = UDim2.new(0, 600, 0, 56)
BOTTLE_7.Font = Enum.Font.Oswald
BOTTLE_7.Text = "Notify Next Door"
BOTTLE_7.TextColor3 = Color3.fromRGB(255, 234, 171)
BOTTLE_7.TextScaled = true
BOTTLE_7.TextSize = 14.000
BOTTLE_7.TextWrapped = true

UICorner_25.Parent = BOTTLE_7

Frame_3.Parent = ScrollingFrame
Frame_3.Active = true
Frame_3.BackgroundColor3 = Color3.fromRGB(163, 255, 137)
Frame_3.BackgroundTransparency = 1.000
Frame_3.BorderColor3 = Color3.fromRGB(103, 221, 213)
Frame_3.Draggable = true
Frame_3.Position = UDim2.new(0.118006676, 123, 0.0887525156, -117)
Frame_3.Size = UDim2.new(0, 280, 0, 55)

up.Name = "up"
up.Parent = Frame_3
up.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
up.Size = UDim2.new(0, 44, 0, 28)
up.Font = Enum.Font.Oswald
up.Text = "UP"
up.TextColor3 = Color3.fromRGB(255, 218, 176)
up.TextScaled = true
up.TextSize = 14.000
up.TextWrapped = true

down.Name = "down"
down.Parent = Frame_3
down.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
down.Position = UDim2.new(0, 0, 0.491228074, 0)
down.Size = UDim2.new(0, 44, 0, 28)
down.Font = Enum.Font.Oswald
down.Text = "DOWN"
down.TextColor3 = Color3.fromRGB(255, 218, 176)
down.TextScaled = true
down.TextSize = 14.000
down.TextWrapped = true

onof.Name = "onof"
onof.Parent = Frame_3
onof.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
onof.Position = UDim2.new(0.702823341, 0, 0.491228133, 0)
onof.Size = UDim2.new(0, 56, 0, 28)
onof.Font = Enum.Font.Oswald
onof.Text = "fly"
onof.TextColor3 = Color3.fromRGB(255, 218, 176)
onof.TextScaled = true
onof.TextSize = 14.000
onof.TextWrapped = true

TextLabel_3.Parent = Frame_3
TextLabel_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.Position = UDim2.new(0.483612925, 0, 0.0181818176, 0)
TextLabel_3.Size = UDim2.new(0, 100, 0, 28)
TextLabel_3.Font = Enum.Font.Oswald
TextLabel_3.Text = "Fly Gui"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 218, 176)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

plus.Name = "plus"
plus.Parent = Frame_3
plus.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
plus.Position = UDim2.new(0.231578946, 0, 0, 0)
plus.Size = UDim2.new(0, 45, 0, 28)
plus.Font = Enum.Font.Oswald
plus.Text = "+"
plus.TextColor3 = Color3.fromRGB(255, 218, 176)
plus.TextScaled = true
plus.TextSize = 14.000
plus.TextWrapped = true

speed.Name = "speed"
speed.Parent = Frame_3
speed.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
speed.Position = UDim2.new(0.468421042, 0, 0.491228074, 0)
speed.Size = UDim2.new(0, 44, 0, 28)
speed.Font = Enum.Font.Oswald
speed.Text = "1"
speed.TextColor3 = Color3.fromRGB(255, 218, 176)
speed.TextScaled = true
speed.TextSize = 14.000
speed.TextWrapped = true

mine.Name = "mine"
mine.Parent = Frame_3
mine.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
mine.Position = UDim2.new(0.231578946, 0, 0.491228074, 0)
mine.Size = UDim2.new(0, 45, 0, 29)
mine.Font = Enum.Font.Oswald
mine.Text = "-"
mine.TextColor3 = Color3.fromRGB(255, 218, 176)
mine.TextScaled = true
mine.TextSize = 14.000
mine.TextWrapped = true

Close.Name = "Close"
Close.Parent = Frame_3
Close.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Close.Position = UDim2.new(0, 0, -1, 27)
Close.Size = UDim2.new(0, 45, 0, 28)
Close.Font = Enum.Font.Oswald
Close.Text = "X"
Close.TextColor3 = Color3.fromRGB(255, 218, 176)
Close.TextScaled = true
Close.TextSize = 30.000
Close.TextWrapped = tr
