-- GREENVILLE
local Greenville = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local CreditsFrame = Instance.new("Frame")
local Title = Instance.new("TextLabel")
local Subtitle = Instance.new("TextLabel")
local Credits = Instance.new("Frame")
local CreditsTitle = Instance.new("TextLabel")
local sjonks = Instance.new("TextLabel")
local alohabeach = Instance.new("TextLabel")
local coola = Instance.new("TextLabel")
local Dorrow = Instance.new("TextLabel")
local alohabeach_2 = Instance.new("TextLabel")
local UpdateLog = Instance.new("Frame")
local UpdateLogTitle = Instance.new("TextLabel")
local v111 = Instance.new("TextLabel")
local v110 = Instance.new("TextLabel")
local Title_2 = Instance.new("TextLabel")
local SideBar = Instance.new("Frame")
local AutofarmButton = Instance.new("TextButton")
local ClientButton = Instance.new("TextButton")
local CreditsButton = Instance.new("TextButton")
local Close = Instance.new("TextButton")
local Minimise = Instance.new("TextButton")
local AutofarmFrame = Instance.new("Frame")
local GreenvilleFrame = Instance.new("Frame")
local GreenvilleAutofarm = Instance.new("TextButton")
local ClientFrame = Instance.new("Frame")
local ButtonImage = Instance.new("ImageLabel")
local ButtonButton = Instance.new("TextButton")

--Properties:

Greenville.Name = "Greenville"
Greenville.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Greenville.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

MainFrame.Name = "MainFrame"
MainFrame.Parent = Greenville
MainFrame.Active = true
MainFrame.AnchorPoint = Vector2.new(0.5, 0.5)
MainFrame.BackgroundColor3 = Color3.fromRGB(28, 29, 29)
MainFrame.Position = UDim2.new(0.5, 0, 0.461854637, 0)
MainFrame.Size = UDim2.new(0, 407, 0, 226)

CreditsFrame.Name = "CreditsFrame"
CreditsFrame.Parent = MainFrame
CreditsFrame.Active = true
CreditsFrame.BackgroundColor3 = Color3.fromRGB(39, 40, 41)
CreditsFrame.BorderColor3 = Color3.fromRGB(50, 83, 108)
CreditsFrame.BorderSizePixel = 0
CreditsFrame.Position = UDim2.new(0.212117419, 0, 0.0908032283, 0)
CreditsFrame.Size = UDim2.new(0.787882566, 0, 0.909196913, 0)

Title.Name = "Title"
Title.Parent = CreditsFrame
Title.AnchorPoint = Vector2.new(0.5, 0.5)
Title.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title.BackgroundTransparency = 1.000
Title.Position = UDim2.new(0.521829367, 0, 0.12930277, 0)
Title.Size = UDim2.new(1, 0, 0.132734478, 0)
Title.Font = Enum.Font.GothamBold
Title.Text = "Carhub"
Title.TextColor3 = Color3.fromRGB(255, 255, 255)
Title.TextSize = 26.000
Title.TextWrapped = true

Subtitle.Name = "Subtitle"
Subtitle.Parent = CreditsFrame
Subtitle.AnchorPoint = Vector2.new(0.5, 0.5)
Subtitle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Subtitle.BackgroundTransparency = 1.000
Subtitle.Position = UDim2.new(0.5, 0, 0.255836666, 0)
Subtitle.Size = UDim2.new(1, 0, 0.132734478, 0)
Subtitle.Font = Enum.Font.GothamBold
Subtitle.Text = "Greenville"
Subtitle.TextColor3 = Color3.fromRGB(255, 255, 255)
Subtitle.TextSize = 17.000
Subtitle.TextWrapped = true

Credits.Name = "Credits"
Credits.Parent = CreditsFrame
Credits.Active = true
Credits.BackgroundColor3 = Color3.fromRGB(29, 30, 30)
Credits.BorderColor3 = Color3.fromRGB(21, 22, 22)
Credits.BorderSizePixel = 0
Credits.Position = UDim2.new(0.0779622048, 0, 0.37071687, 0)
Credits.Size = UDim2.new(0.376188695, 0, 0.592831731, 0)

CreditsTitle.Name = "CreditsTitle"
CreditsTitle.Parent = Credits
CreditsTitle.AnchorPoint = Vector2.new(0.5, 0.5)
CreditsTitle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CreditsTitle.BackgroundTransparency = 1.000
CreditsTitle.Position = UDim2.new(0.5, 0, 0.0590565056, 0)
CreditsTitle.Size = UDim2.new(1, 0, 0.132734478, 0)
CreditsTitle.Font = Enum.Font.GothamBold
CreditsTitle.Text = "Developers"
CreditsTitle.TextColor3 = Color3.fromRGB(255, 255, 255)
CreditsTitle.TextSize = 16.000
CreditsTitle.TextWrapped = true

sjonks.Name = "sjonks"
sjonks.Parent = Credits
sjonks.AnchorPoint = Vector2.new(0.5, 0.5)
sjonks.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
sjonks.BackgroundTransparency = 1.000
sjonks.Position = UDim2.new(0.5, 0, 0.436680853, 0)
sjonks.Size = UDim2.new(1, 0, 0.132734478, 0)
sjonks.Font = Enum.Font.Gotham
sjonks.Text = "sjonks"
sjonks.TextColor3 = Color3.fromRGB(255, 255, 255)
sjonks.TextSize = 16.000
sjonks.TextWrapped = true

alohabeach.Name = "alohabeach"
alohabeach.Parent = Credits
alohabeach.AnchorPoint = Vector2.new(0.5, 0.5)
alohabeach.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
alohabeach.BackgroundTransparency = 1.000
alohabeach.Position = UDim2.new(0.5, 0, 0.699376106, 0)
alohabeach.Size = UDim2.new(1, 0, 0.132734478, 0)
alohabeach.Font = Enum.Font.Gotham
alohabeach.Text = "alohabeach"
alohabeach.TextColor3 = Color3.fromRGB(255, 255, 255)
alohabeach.TextSize = 16.000
alohabeach.TextWrapped = true

coola.Name = "coola"
coola.Parent = Credits
coola.AnchorPoint = Vector2.new(0.5, 0.5)
coola.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
coola.BackgroundTransparency = 1.000
coola.Position = UDim2.new(0.5, 0, 0.56802845, 0)
coola.Size = UDim2.new(1, 0, 0.132734478, 0)
coola.Font = Enum.Font.Gotham
coola.Text = "coola"
coola.TextColor3 = Color3.fromRGB(255, 255, 255)
coola.TextSize = 16.000
coola.TextWrapped = true

Dorrow.Name = "Dorrow"
Dorrow.Parent = Credits
Dorrow.AnchorPoint = Vector2.new(0.5, 0.5)
Dorrow.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Dorrow.BackgroundTransparency = 1.000
Dorrow.Position = UDim2.new(0.5, 0, 0.305333227, 0)
Dorrow.Size = UDim2.new(1, 0, 0.132734478, 0)
Dorrow.Font = Enum.Font.Gotham
Dorrow.Text = "Dorrow"
Dorrow.TextColor3 = Color3.fromRGB(255, 255, 255)
Dorrow.TextSize = 16.000
Dorrow.TextWrapped = true

alohabeach_2.Name = "alohabeach"
alohabeach_2.Parent = Credits
alohabeach_2.AnchorPoint = Vector2.new(0.5, 0.5)
alohabeach_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
alohabeach_2.BackgroundTransparency = 1.000
alohabeach_2.Position = UDim2.new(0.5, 0, 0.830723643, 0)
alohabeach_2.Size = UDim2.new(1, 0, 0.132734478, 0)
alohabeach_2.Font = Enum.Font.Gotham
alohabeach_2.Text = "Walter"
alohabeach_2.TextColor3 = Color3.fromRGB(255, 255, 255)
alohabeach_2.TextSize = 16.000
alohabeach_2.TextWrapped = true

UpdateLog.Name = "UpdateLog"
UpdateLog.Parent = CreditsFrame
UpdateLog.Active = true
UpdateLog.BackgroundColor3 = Color3.fromRGB(29, 30, 30)
UpdateLog.BorderColor3 = Color3.fromRGB(21, 22, 22)
UpdateLog.BorderSizePixel = 0
UpdateLog.Position = UDim2.new(0.551972389, 0, 0.37071687, 0)
UpdateLog.Size = UDim2.new(0.376188695, 0, 0.592831731, 0)

UpdateLogTitle.Name = "UpdateLogTitle"
UpdateLogTitle.Parent = UpdateLog
UpdateLogTitle.AnchorPoint = Vector2.new(0.5, 0.5)
UpdateLogTitle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
UpdateLogTitle.BackgroundTransparency = 1.000
UpdateLogTitle.Position = UDim2.new(0.5, 0, 0.132939532, 0)
UpdateLogTitle.Size = UDim2.new(1, 0, 0.132734478, 0)
UpdateLogTitle.Font = Enum.Font.GothamBold
UpdateLogTitle.Text = "Update Log"
UpdateLogTitle.TextColor3 = Color3.fromRGB(255, 255, 255)
UpdateLogTitle.TextSize = 16.000
UpdateLogTitle.TextWrapped = true

v111.Name = "v1.1.1"
v111.Parent = UpdateLog
v111.AnchorPoint = Vector2.new(0.5, 0.5)
v111.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
v111.BackgroundTransparency = 1.000
v111.Position = UDim2.new(0.5, 0, 0.354588568, 0)
v111.Size = UDim2.new(1, 0, 0.132734478, 0)
v111.Font = Enum.Font.Gotham
v111.Text = "1.1.1: New Hub UI Layout"
v111.TextColor3 = Color3.fromRGB(255, 255, 255)
v111.TextSize = 16.000
v111.TextWrapped = true

v110.Name = "v1.1.0"
v110.Parent = UpdateLog
v110.AnchorPoint = Vector2.new(0.5, 0.5)
v110.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
v110.BackgroundTransparency = 1.000
v110.Position = UDim2.new(0.5, 0, 0.765049934, 0)
v110.Size = UDim2.new(1, 0, 0.132734478, 0)
v110.Font = Enum.Font.Gotham
v110.Text = "1.1.0: Work on the new Hub begins!"
v110.TextColor3 = Color3.fromRGB(255, 255, 255)
v110.TextSize = 16.000
v110.TextWrapped = true

Title_2.Name = "Title"
Title_2.Parent = MainFrame
Title_2.AnchorPoint = Vector2.new(0.5, 0.5)
Title_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title_2.BackgroundTransparency = 1.000
Title_2.Position = UDim2.new(0.5, 0, 0.0476691984, 0)
Title_2.Size = UDim2.new(1, 0, 0.0862679258, 0)
Title_2.Font = Enum.Font.GothamBold
Title_2.Text = "Carhub"
Title_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_2.TextScaled = true
Title_2.TextSize = 14.000
Title_2.TextWrapped = true

SideBar.Name = "SideBar"
SideBar.Parent = MainFrame
SideBar.Active = true
SideBar.BackgroundColor3 = Color3.fromRGB(29, 30, 30)
SideBar.BorderColor3 = Color3.fromRGB(21, 22, 22)
SideBar.BorderSizePixel = 0
SideBar.Position = UDim2.new(0, 0, 0.122515656, 0)
SideBar.Size = UDim2.new(0.212117419, 0, 0.8774845, 0)

AutofarmButton.Name = "AutofarmButton"
AutofarmButton.Parent = SideBar
AutofarmButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AutofarmButton.BackgroundTransparency = 1.000
AutofarmButton.Position = UDim2.new(0, 0, 0.0500000007, 0)
AutofarmButton.Size = UDim2.new(1, 0, 0.100000001, 0)
AutofarmButton.Font = Enum.Font.GothamSemibold
AutofarmButton.Text = "Autofarm"
AutofarmButton.TextColor3 = Color3.fromRGB(255, 255, 255)
AutofarmButton.TextSize = 16.000
AutofarmButton.TextWrapped = true

ClientButton.Name = "ClientButton"
ClientButton.Parent = SideBar
ClientButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ClientButton.BackgroundTransparency = 1.000
ClientButton.Position = UDim2.new(0, 0, 0.200000003, 0)
ClientButton.Size = UDim2.new(1, 0, 0.100000001, 0)
ClientButton.Font = Enum.Font.GothamSemibold
ClientButton.Text = "Client"
ClientButton.TextColor3 = Color3.fromRGB(255, 255, 255)
ClientButton.TextSize = 16.000
ClientButton.TextWrapped = true

CreditsButton.Name = "CreditsButton"
CreditsButton.Parent = SideBar
CreditsButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CreditsButton.BackgroundTransparency = 1.000
CreditsButton.Position = UDim2.new(0, 0, 0.349999994, 0)
CreditsButton.Size = UDim2.new(1, 0, 0.100000001, 0)
CreditsButton.Font = Enum.Font.GothamSemibold
CreditsButton.Text = "Credits"
CreditsButton.TextColor3 = Color3.fromRGB(255, 255, 255)
CreditsButton.TextSize = 16.000
CreditsButton.TextWrapped = true

Close.Name = "Close"
Close.Parent = MainFrame
Close.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Close.BackgroundTransparency = 1.000
Close.Position = UDim2.new(0.944506764, 0, 0, 0)
Close.Size = UDim2.new(0, 21, 0, 20)
Close.Text = "x"
Close.TextColor3 = Color3.fromRGB(255, 255, 255)
Close.TextScaled = true
Close.TextSize = 14.000
Close.TextWrapped = true

Minimise.Name = "Minimise"
Minimise.Parent = MainFrame
Minimise.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Minimise.BackgroundTransparency = 1.000
Minimise.Position = UDim2.new(0.892909706, 0, 0, 0)
Minimise.Size = UDim2.new(0, 21, 0, 20)
Minimise.Text = "-"
Minimise.TextColor3 = Color3.fromRGB(255, 255, 255)
Minimise.TextScaled = true
Minimise.TextSize = 14.000
Minimise.TextWrapped = true

AutofarmFrame.Name = "AutofarmFrame"
AutofarmFrame.Parent = MainFrame
AutofarmFrame.Active = true
AutofarmFrame.BackgroundColor3 = Color3.fromRGB(39, 40, 41)
AutofarmFrame.BorderColor3 = Color3.fromRGB(50, 83, 108)
AutofarmFrame.BorderSizePixel = 0
AutofarmFrame.Position = UDim2.new(0.212117419, 0, 0.0908032283, 0)
AutofarmFrame.Size = UDim2.new(0.787882566, 0, 0.909196913, 0)
AutofarmFrame.Visible = false

GreenvilleFrame.Name = "GreenvilleFrame"
GreenvilleFrame.Parent = AutofarmFrame
GreenvilleFrame.Active = true
GreenvilleFrame.BackgroundColor3 = Color3.fromRGB(29, 30, 30)
GreenvilleFrame.BorderColor3 = Color3.fromRGB(21, 22, 22)
GreenvilleFrame.BorderSizePixel = 0
GreenvilleFrame.Position = UDim2.new(0.261952996, 0, 0.324415714, 0)
GreenvilleFrame.Size = UDim2.new(0.482217342, 0, 0.34370172, 0)

GreenvilleAutofarm.Name = "GreenvilleAutofarm"
GreenvilleAutofarm.Parent = GreenvilleFrame
GreenvilleAutofarm.BackgroundColor3 = Color3.fromRGB(29, 30, 30)
GreenvilleAutofarm.BackgroundTransparency = 1.000
GreenvilleAutofarm.BorderColor3 = Color3.fromRGB(255, 255, 255)
GreenvilleAutofarm.Position = UDim2.new(0.0144037372, 0, 0.273401648, 0)
GreenvilleAutofarm.Size = UDim2.new(0.98559624, 0, 0.435959041, 0)
GreenvilleAutofarm.Font = Enum.Font.GothamSemibold
GreenvilleAutofarm.Text = "Autofarm"
GreenvilleAutofarm.TextColor3 = Color3.fromRGB(255, 255, 255)
GreenvilleAutofarm.TextSize = 16.000
GreenvilleAutofarm.TextWrapped = true

ClientFrame.Name = "ClientFrame"
ClientFrame.Parent = MainFrame
ClientFrame.Active = true
ClientFrame.BackgroundColor3 = Color3.fromRGB(39, 40, 41)
ClientFrame.BorderColor3 = Color3.fromRGB(50, 83, 108)
ClientFrame.BorderSizePixel = 0
ClientFrame.Position = UDim2.new(0.212117419, 0, 0.0908032283, 0)
ClientFrame.Size = UDim2.new(0.787882566, 0, 0.909196913, 0)
ClientFrame.Visible = false

ButtonImage.Name = "ButtonImage"
ButtonImage.Parent = Greenville
ButtonImage.AnchorPoint = Vector2.new(0.5, 0.5)
ButtonImage.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ButtonImage.Position = UDim2.new(0.0500000007, 0, 0.5, 0)
ButtonImage.Size = UDim2.new(0, 70, 0, 70)
ButtonImage.Visible = false
ButtonImage.Image = "rbxassetid://6780851735"

ButtonButton.Name = "ButtonButton"
ButtonButton.Parent = ButtonImage
ButtonButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ButtonButton.BackgroundTransparency = 1.000
ButtonButton.Size = UDim2.new(1, 0, 1, 0)
ButtonButton.Font = Enum.Font.SourceSans
ButtonButton.Text = ""
ButtonButton.TextColor3 = Color3.fromRGB(0, 0, 0)
ButtonButton.TextSize = 14.000

-- Scripts:

local function LAPZGJX_fake_script() -- MainFrame.Engine 
	local script = Instance.new('LocalScript', MainFrame)

	local MainFrame = script.Parent
	local ClientButton = script.Parent.SideBar.ClientButton
	local CreditsButton = script.Parent.SideBar.CreditsButton
	local AutofarmButton = script.Parent.SideBar.AutofarmButton
	local AutofarmFrame = script.Parent.AutofarmFrame
	local ClientFrame = script.Parent.ClientFrame
	local CreditsFrame = script.Parent.CreditsFrame
	local CloseButton = script.Parent.Close
	local MainGui = script.Parent.Parent
	function loadgreenville()
		--Vars
		LocalPlayer = game:GetService("Players").LocalPlayer
		Camera = workspace.CurrentCamera
		RunService = game:GetService("RunService")
		VirtualUser = game:GetService("VirtualUser")
		MarketplaceService = game:GetService("MarketplaceService")
	
		--Get Current Vehicle
		function GetCurrentVehicle()
			return LocalPlayer.Character and LocalPlayer.Character:FindFirstChild("Humanoid") and LocalPlayer.Character.Humanoid.SeatPart and LocalPlayer.Character.Humanoid.SeatPart.Parent
		end
	
		--Metatables
		MT = getrawmetatable(game)
		Old_Index = MT.__index
		setreadonly(MT, false)
		MT.__index = newcclosure(function(self, K)
			if self:IsA("Sound") and self:IsDescendantOf(workspace.SessionVehicles) and AntiSkidMarkSounds then
				self:Stop()
				return
			end
			return Old_Index(self, K)
		end)
		setreadonly(MT, true)
	
		--Notification Handler
		function SendNotification(Title, Message, Duration)
			game.StarterGui:SetCore("SendNotification", {
				Title = Title;
				Text = Message;
				Duration = Duration;
			})
		end
	
		--Regular TP
		function TP(cframe)
			GetCurrentVehicle():SetPrimaryPartCFrame(cframe)
		end
	
		--Velocity TP
		function VelocityTP(cframe)
			TeleportSpeed = 500
			Car = GetCurrentVehicle()
			for I,V in pairs(GetCurrentVehicle():GetDescendants()) do
				if V:IsA("BodyGyro") then
					V:Destroy()
				end
			end
			local BodyGyro = Instance.new("BodyGyro", Car.PrimaryPart)
			BodyGyro.P = 5000
			BodyGyro.maxTorque = Vector3.new(9e9, 9e9, 9e9)
			BodyGyro.CFrame = Car.PrimaryPart.CFrame
			local BodyVelocity = Instance.new("BodyVelocity", Car.PrimaryPart)
			BodyVelocity.MaxForce = Vector3.new(9e9, 9e9, 9e9)
			BodyVelocity.Velocity = CFrame.new(Car.PrimaryPart.Position, cframe.p).LookVector * TeleportSpeed
			wait((Car.PrimaryPart.Position - cframe.p).Magnitude / TeleportSpeed)
			BodyVelocity.Velocity = Vector3.new()
			wait(0.1)
			BodyVelocity:Destroy()
			BodyGyro:Destroy()
		end
	
		--Auto Farm
		StartPosition = CFrame.new(Vector3.new(-1818, -79, -10685), Vector3.new(-880, -79, -10769))
		EndPosition = CFrame.new(Vector3.new(-965, -79, -10761), Vector3.new(-880, -79, -10769))
		AutoFarmFunc = coroutine.create(function()
			while wait() do
				if not AutoFarm then
					AutoFarmRunning = false
					coroutine.yield()
				end
				AutoFarmRunning = true
				pcall(function()
					if not GetCurrentVehicle() and tick() - (LastNotif or 0) > 5 then
						LastNotif = tick()
						SendNotification("Aloha Scripts", "Please Enter A Vehicle!")
					else
						TP(StartPosition + (TouchTheRoad and Vector3.new() or Vector3.new(0, 1, 0)))
						VelocityTP(EndPosition + (TouchTheRoad and Vector3.new() or Vector3.new(0, 1, 0)))
						TP(EndPosition + (TouchTheRoad and Vector3.new() or Vector3.new(0, 1, 0)))
						VelocityTP(StartPosition + (TouchTheRoad and Vector3.new() or Vector3.new(0, 1, 0)))
					end
				end)
			end
		end)
	
		--Anti AFK
		AntiAFK = true
		LocalPlayer.Idled:Connect(function()
			VirtualUser:CaptureController()
			VirtualUser:ClickButton2(Vector2.new(), Camera.CFrame)
		end)
	
		--UI
		local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/GreenDeno/Venyx-UI-Library/main/source.lua"))()
		local venyx = library.new(MarketplaceService:GetProductInfo(game.PlaceId).Name)
	
		--Themes
		local themes = {
			Background = Color3.fromRGB(24, 24, 24),
			Glow = Color3.fromRGB(0, 0, 0),
			Accent = Color3.fromRGB(10, 10, 10),
			LightContrast = Color3.fromRGB(20, 20, 20),
			DarkContrast = Color3.fromRGB(14, 14, 14),
			TextColor = Color3.fromRGB(255, 255, 255)
		}
	
		--Pages
		local page1 = venyx:addPage("Main")
		local page2 = venyx:addPage("Other")
	
		--Page 1
		local FirstSection1 = page1:addSection("Auto Farm")
		local FirstSection2 = page1:addSection("Options")
	
		FirstSection1:addToggle(
			"Enabled",
			nil,
			function(value)
				AutoFarm = value
				if value and not AutoFarmRunning then
					coroutine.resume(AutoFarmFunc)
				end
			end
		)
		FirstSection2:addToggle(
			"Touch The Ground",
			nil,
			function(value)
				TouchTheRoad = value
			end
		)
		FirstSection2:addToggle(
			"Anti Skid Mark Sounds",
			nil,
			function(value)
				AntiSkidMarkSounds = value
			end
		)
	
		--Page 2
		local SecondSection1 = page2:addSection("Info")
		local SecondSection2 = page2:addSection("Settings")
	
		SecondSection2:addToggle(
			"Anti AFK",
			true,
			function(value)
				AntiAFK = value
			end
		)
		SecondSection2:addKeybind(
			"Toggle Keybind",
			Enum.KeyCode.RightShift,
			function()
				venyx:toggle()
			end,
			function(key)
				Keybind = key.KeyCode.Name
			end
		)
		for theme, color in pairs(themes) do
			SecondSection2:addColorPicker(
				theme,
				color,
				function(color3)
					venyx:setTheme(theme, color3)
				end
			)
		end
	
		--load
		venyx:SelectPage(venyx.pages[1], true)
	end
	ClientButton.MouseButton1Click:Connect(function()
		AutofarmFrame.Visible = false
		CreditsFrame.Visible = false
		ClientFrame.Visible = true
	end)
	
	CreditsButton.MouseButton1Click:Connect(function()
		AutofarmFrame.Visible = false
		CreditsFrame.Visible = true
		ClientFrame.Visible = false
	end)
	
	AutofarmButton.MouseButton1Click:Connect(function()
		AutofarmFrame.Visible = true
		CreditsFrame.Visible = false
		ClientFrame.Visible = false
	end)
	script.Parent.AutofarmFrame.GreenvilleFrame.GreenvilleAutofarm.MouseButton1Click:Connect(function()
		loadgreenville()
	end)
	MainFrame.Draggable = true
	
	CloseButton.MouseButton1Click:Connect(function()
		MainGui:Destroy()
	end)
end
coroutine.wrap(LAPZGJX_fake_script)()
local function WOWU_fake_script() -- MainFrame.KeyBind 
	local script = Instance.new('LocalScript', MainFrame)

	local FrameObject = script.Parent
	local Open = true
	local Minimise = script.Parent.Minimise
	local UserInputService = game:GetService("UserInputService")
	local ButtonImage = script.Parent.Parent.ButtonImage
	local ButtonButton = ButtonImage.ButtonButton
	
	Minimise.MouseButton1Click:Connect(function()
		FrameObject.Visible = false
		Open = false
		ButtonImage.Visible = true
	end)
	
	UserInputService.InputBegan:Connect(function(KeyCode)
		if KeyCode.KeyCode == Enum.KeyCode.RightShift then
			if Open then
				FrameObject.Visible = false
				Open = false
			else
				Open = true
				FrameObject.Visible = true
			end
		end
	end)
	
	ButtonImage.ButtonButton.MouseButton1Click:Connect(function()
		FrameObject.Visible = true
		Open = true
		ButtonImage.Visible = false
	end)
	
	
end
coroutine.wrap(WOWU_fake_script)()
