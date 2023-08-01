-- Gui to Lua
-- Version: 3.2

-- Instances:

local UNUPDATR = Instance.new("ScreenGui")
local NOTICE = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Close = Instance.new("ImageButton")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local UIListLayout = Instance.new("UIListLayout")

--Properties:

UNUPDATR.Name = "UNUPDATR"
UNUPDATR.Parent = game.CoreGui
UNUPDATR.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

NOTICE.Name = "NOTICE"
NOTICE.Parent = UNUPDATR
NOTICE.BackgroundColor3 = Color3.fromRGB(48, 73, 111)
NOTICE.BorderColor3 = Color3.fromRGB(0, 0, 0)
NOTICE.BorderSizePixel = 0
NOTICE.Position = UDim2.new(0.381014317, 0, 0.358024687, 0)
NOTICE.Size = UDim2.new(0, 403, 0, 245)

UICorner.CornerRadius = UDim.new(0, 4)
UICorner.Parent = NOTICE

Close.Name = "Close"
Close.Parent = NOTICE
Close.Active = false
Close.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Close.BackgroundTransparency = 1.000
Close.Position = UDim2.new(0.936760604, 0, 0, 0)
Close.Selectable = false
Close.Size = UDim2.new(0, 25, 0, 25)
Close.Image = "http://www.roblox.com/asset/?id=12707060750"

TextLabel.Parent = NOTICE
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Size = UDim2.new(0, 403, 0, 50)
TextLabel.Font = Enum.Font.SourceSansSemibold
TextLabel.Text = "SCRIPT NOTICE READ:"
TextLabel.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel.TextSize = 40.000

TextLabel_2.Parent = NOTICE
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.0595533513, 0, 0.318367332, 0)
TextLabel_2.Size = UDim2.new(0, 354, 0, 88)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "The Shipt Event on driving empire has ended so there is no use for this script since its a autofarm for the event. But do not worry we will release more scripts for this game when a new event is out please join the discord if youd like to get notified of them"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 17.000
TextLabel_2.TextWrapped = true
TextLabel_2.TextYAlignment = Enum.TextYAlignment.Top

TextLabel_3.Parent = NOTICE
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0, 0, 0.771428585, 0)
TextLabel_3.Size = UDim2.new(0, 403, 0, 50)
TextLabel_3.Font = Enum.Font.SourceSansSemibold
TextLabel_3.Text = "discord.gg/scripts"
TextLabel_3.TextColor3 = Color3.fromRGB(85, 170, 255)
TextLabel_3.TextSize = 35.000

UIListLayout.Parent = UNUPDATR
UIListLayout.HorizontalAlignment = Enum.HorizontalAlignment.Center
UIListLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIListLayout.VerticalAlignment = Enum.VerticalAlignment.Center

-- Scripts:

local function CKXJEGR_fake_script() -- Close.LocalScript 
	local script = Instance.new('LocalScript', Close)

	script.Parent.MouseButton1Down:connect(function()
	
		UNUPDATR:Destroy()
	
		UNUPDATR:deleteTimeout(2)
	
	end)
end
coroutine.wrap(CKXJEGR_fake_script)()
