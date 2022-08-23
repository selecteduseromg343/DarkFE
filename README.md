local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local main_2 = Instance.new("ScrollingFrame")
local UICorner_3 = Instance.new("UICorner")
local infyield = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local slap = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local jet = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local doge = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local UICorner_8 = Instance.new("UICorner")

ScreenGui.Parent = game.CoreGui

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
main.Position = UDim2.new(0.205596089, 0, 0.226984113, 0)
main.Size = UDim2.new(0, 483, 0, 344)
main.Active = true
main.Draggable = true

UICorner.Parent = main

TextLabel.Parent = main
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 85, 0)
TextLabel.Position = UDim2.new(-5.96046448e-08, 0, 0, 0)
TextLabel.Size = UDim2.new(0, 53, 0, 23)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Dark FE "
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 14.000

UICorner_2.Parent = TextLabel

main_2.Name = "main"
main_2.Parent = main
main_2.Active = true
main_2.BackgroundColor3 = Color3.fromRGB(85, 255, 255)
main_2.Position = UDim2.new(0, 0, 0.140039936, 0)
main_2.Size = UDim2.new(0, 483, 0, 295)

UICorner_3.Parent = main_2

infyield.Name = "infyield"
infyield.Parent = main_2
infyield.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
infyield.Position = UDim2.new(0.0165631473, 0, 0.030259423, 0)
infyield.Size = UDim2.new(0, 144, 0, 32)
infyield.Font = Enum.Font.SourceSans
infyield.Text = "InfYield"
infyield.TextColor3 = Color3.fromRGB(0, 0, 0)
infyield.TextSize = 14.000
infyield.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
end)

UICorner_4.Parent = infyield

slap.Name = "slap"
slap.Parent = main_2
slap.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
slap.Position = UDim2.new(0.349896461, 0, 0.029080607, 0)
slap.Size = UDim2.new(0, 130, 0, 33)
slap.Font = Enum.Font.SourceSans
slap.Text = "Slap Battle Gui"
slap.TextColor3 = Color3.fromRGB(0, 0, 0)
slap.TextSize = 14.000
slap.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/dizyhvh/slap_battles_gui/main/0.lua"))()
end)

UICorner_5.Parent = slap

jet.Name = "jet"
jet.Parent = main_2
jet.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
jet.Position = UDim2.new(0.648033142, 0, 0.0288969092, 0)
jet.Size = UDim2.new(0, 131, 0, 33)
jet.Font = Enum.Font.SourceSans
jet.Text = "FE-Baseball"
jet.TextColor3 = Color3.fromRGB(0, 0, 0)
jet.TextSize = 14.000
jet.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://github.com/selecteduseromg343/AAAAAAAAAAAAAAAAAAA/blob/main/README.md"))()	
end)

UICorner_6.Parent = jet

doge.Name = "doge"
doge.Parent = main_2
doge.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
doge.Position = UDim2.new(0.0165631473, 0, 0.101285234, 0)
doge.Size = UDim2.new(0, 144, 0, 37)
doge.Font = Enum.Font.SourceSans
doge.Text = "FE Dog"
doge.TextColor3 = Color3.fromRGB(0, 0, 0)
doge.TextSize = 14.000
doge.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/selecteduseromg343/ddddddddddddddd/main/README.md"))()
end)

UICorner_7.Parent = doge

TextLabel_2.Parent = main
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 85, 0)
TextLabel_2.Position = UDim2.new(0.890269101, 0, 0, 0)
TextLabel_2.Size = UDim2.new(0, 53, 0, 23)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Dark FE "
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 14.000

UICorner_8.Parent = TextLabel_2
