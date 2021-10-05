
local InsertedObjects = Instance.new("ScreenGui")
local ImageLabel = Instance.new("ImageLabel")
local CloseButton = Instance.new("ImageButton")
local UIGradient = Instance.new("UIGradient")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
local ScrollingFrame = Instance.new("ScrollingFrame")
local Button1 = Instance.new("ImageButton")
local BtnText = Instance.new("TextLabel")
local UIAspectRatioConstraint_2 = Instance.new("UIAspectRatioConstraint")
local UIGradient_2 = Instance.new("UIGradient")
local Button2 = Instance.new("ImageButton")
local BtnText_2 = Instance.new("TextLabel")
local UIAspectRatioConstraint_3 = Instance.new("UIAspectRatioConstraint")
local UIGradient_3 = Instance.new("UIGradient")
local Button2_2 = Instance.new("ImageButton")
local BtnText_3 = Instance.new("TextLabel")
local UIAspectRatioConstraint_4 = Instance.new("UIAspectRatioConstraint")
local UIGradient_4 = Instance.new("UIGradient")
local Button1_2 = Instance.new("ImageButton")
local BtnText_4 = Instance.new("TextLabel")
local UIAspectRatioConstraint_5 = Instance.new("UIAspectRatioConstraint")
local UIGradient_5 = Instance.new("UIGradient")
local ImageButton = Instance.new("ImageButton")

--Properties:

InsertedObjects.Name = "InsertedObjects"
InsertedObjects.Parent = game.CoreGui
InsertedObjects.ResetOnSpawn = false

ImageLabel.Parent = InsertedObjects
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.Position = UDim2.new(0.0394712277, 0, 0.104501605, 0)
ImageLabel.Size = UDim2.new(0, 755, 0, 492)
ImageLabel.Image = "http://www.roblox.com/asset/?id=7402946493"

CloseButton.Name = "CloseButton"
CloseButton.Parent = ImageLabel
CloseButton.AnchorPoint = Vector2.new(0.5, 0.5)
CloseButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CloseButton.BackgroundTransparency = 1.000
CloseButton.BorderSizePixel = 0
CloseButton.Position = UDim2.new(0.628071308, 0, 0.122769609, 0)
CloseButton.Size = UDim2.new(0.0927402824, 0, 0.0778043792, 0)
CloseButton.Image = "http://www.roblox.com/asset/?id=7400386959"

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 136, 255))}
UIGradient.Offset = Vector2.new(-0.349999994, 0)
UIGradient.Rotation = -135
UIGradient.Parent = CloseButton

UIAspectRatioConstraint.Parent = CloseButton
UIAspectRatioConstraint.AspectRatio = 2.000

ScrollingFrame.Parent = ImageLabel
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScrollingFrame.BackgroundTransparency = 1.000
ScrollingFrame.BorderSizePixel = 0
ScrollingFrame.Position = UDim2.new(0.36953643, 0, 0.380081296, 0)
ScrollingFrame.Size = UDim2.new(0, 195, 0, 243)
ScrollingFrame.ScrollBarThickness = 5

Button1.Name = "Button 1 "
Button1.Parent = ScrollingFrame
Button1.AnchorPoint = Vector2.new(1, 1)
Button1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button1.BackgroundTransparency = 1.000
Button1.BorderSizePixel = 5
Button1.Position = UDim2.new(0.945403278, 0, 0.0661384612, 0)
Button1.Size = UDim2.new(0.882225692, 0, 0.0763209537, 0)
Button1.Image = "rbxassetid://2790382281"
Button1.ImageColor3 = Color3.fromRGB(26, 190, 190)
Button1.ScaleType = Enum.ScaleType.Slice
Button1.SliceCenter = Rect.new(4, 4, 252, 252)

BtnText.Name = "BtnText"
BtnText.Parent = Button1
BtnText.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText.BackgroundTransparency = 1.000
BtnText.BorderSizePixel = 0
BtnText.Position = UDim2.new(0.498592883, 0, 0.488144726, 0)
BtnText.Size = UDim2.new(0.891457498, -5, 0.468874484, -5)
BtnText.Font = Enum.Font.GothamBlack
BtnText.Text = "AUTO FARM CANDY"
BtnText.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText.TextScaled = true
BtnText.TextSize = 14.000
BtnText.TextWrapped = true

UIAspectRatioConstraint_2.Parent = Button1
UIAspectRatioConstraint_2.AspectRatio = 3.042

UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(0.98, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient_2.Offset = Vector2.new(-0.349999994, 0)
UIGradient_2.Rotation = -135
UIGradient_2.Parent = Button1

Button2.Name = "Button 2"
Button2.Parent = ScrollingFrame
Button2.AnchorPoint = Vector2.new(1, 1)
Button2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button2.BackgroundTransparency = 1.000
Button2.Position = UDim2.new(0.945403278, 0, 0.258211672, 0)
Button2.Size = UDim2.new(0.882225692, 0, 0.0763209537, 0)
Button2.Image = "rbxassetid://2790382281"
Button2.ImageColor3 = Color3.fromRGB(26, 190, 190)
Button2.ScaleType = Enum.ScaleType.Slice
Button2.SliceCenter = Rect.new(4, 4, 252, 252)

BtnText_2.Name = "BtnText"
BtnText_2.Parent = Button2
BtnText_2.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_2.BackgroundTransparency = 1.000
BtnText_2.BorderSizePixel = 0
BtnText_2.Position = UDim2.new(0.498592883, 0, 0.550041258, 0)
BtnText_2.Size = UDim2.new(0.891457498, -5, 0.59266752, -5)
BtnText_2.Font = Enum.Font.GothamBlack
BtnText_2.Text = "INVISIBLE"
BtnText_2.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_2.TextScaled = true
BtnText_2.TextSize = 5.000
BtnText_2.TextWrapped = true

UIAspectRatioConstraint_3.Parent = Button2
UIAspectRatioConstraint_3.AspectRatio = 3.042

UIGradient_3.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(0.98, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient_3.Offset = Vector2.new(-0.349999994, 0)
UIGradient_3.Rotation = -135
UIGradient_3.Parent = Button2

Button2_2.Name = "Button 2"
Button2_2.Parent = ScrollingFrame
Button2_2.AnchorPoint = Vector2.new(1, 1)
Button2_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button2_2.BackgroundTransparency = 1.000
Button2_2.Position = UDim2.new(0.944999993, 0, 0.193967462, 0)
Button2_2.Size = UDim2.new(0.882225692, 0, 0.0763209537, 0)
Button2_2.Image = "rbxassetid://2790382281"
Button2_2.ImageColor3 = Color3.fromRGB(26, 190, 190)
Button2_2.ScaleType = Enum.ScaleType.Slice
Button2_2.SliceCenter = Rect.new(4, 4, 252, 252)

BtnText_3.Name = "BtnText"
BtnText_3.Parent = Button2_2
BtnText_3.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_3.BackgroundTransparency = 1.000
BtnText_3.BorderSizePixel = 0
BtnText_3.Position = UDim2.new(0.498592883, 0, 0.550041258, 0)
BtnText_3.Size = UDim2.new(0.891457498, -5, 0.59266752, -5)
BtnText_3.Font = Enum.Font.GothamBlack
BtnText_3.Text = "FLY CAR (P)"
BtnText_3.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_3.TextScaled = true
BtnText_3.TextSize = 5.000
BtnText_3.TextWrapped = true

UIAspectRatioConstraint_4.Parent = Button2_2
UIAspectRatioConstraint_4.AspectRatio = 3.042

UIGradient_4.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(0.98, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient_4.Offset = Vector2.new(-0.349999994, 0)
UIGradient_4.Rotation = -135
UIGradient_4.Parent = Button2_2

Button1_2.Name = "Button 1 "
Button1_2.Parent = ScrollingFrame
Button1_2.AnchorPoint = Vector2.new(1, 1)
Button1_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button1_2.BackgroundTransparency = 1.000
Button1_2.BorderSizePixel = 5
Button1_2.Position = UDim2.new(0.944999993, 0, 0.129999995, 0)
Button1_2.Size = UDim2.new(0.882225692, 0, 0.0763209537, 0)
Button1_2.Image = "rbxassetid://2790382281"
Button1_2.ImageColor3 = Color3.fromRGB(26, 190, 190)
Button1_2.ScaleType = Enum.ScaleType.Slice
Button1_2.SliceCenter = Rect.new(4, 4, 252, 252)

BtnText_4.Name = "BtnText"
BtnText_4.Parent = Button1_2
BtnText_4.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_4.BackgroundTransparency = 1.000
BtnText_4.BorderSizePixel = 0
BtnText_4.Position = UDim2.new(0.498592883, 0, 0.488144726, 0)
BtnText_4.Size = UDim2.new(0.891457498, -5, 0.468874484, -5)
BtnText_4.Font = Enum.Font.GothamBlack
BtnText_4.Text = "COLLECT ALL CHEST"
BtnText_4.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_4.TextScaled = true
BtnText_4.TextSize = 14.000
BtnText_4.TextWrapped = true

UIAspectRatioConstraint_5.Parent = Button1_2
UIAspectRatioConstraint_5.AspectRatio = 3.042

UIGradient_5.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(0.98, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient_5.Offset = Vector2.new(-0.349999994, 0)
UIGradient_5.Rotation = -135
UIGradient_5.Parent = Button1_2

ImageButton.Parent = InsertedObjects
ImageButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageButton.BackgroundTransparency = 1.000
ImageButton.Position = UDim2.new(0.416326493, 0, 0, 0)
ImageButton.Size = UDim2.new(0, 123, 0, 60)
ImageButton.Image = "http://www.roblox.com/asset/?id=7529900564"

-- Scripts:

local function FLNFQO_fake_script() -- ImageLabel.LocalScript 
	local script = Instance.new('LocalScript', ImageLabel)

	
	local UIS = game:GetService('UserInputService')
	
	local frame = script.Parent
	
	
	
	local dragToggle = nil
	
	local dragSpeed = 0.25
	
	local dragStart = nil
	
	local startPos = nil
	
	
	
	local function updateInput(input)
	
		local delta = input.Position - dragStart
	
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
	
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	
	end
	
	
	
	frame.InputBegan:Connect(function(input)
	
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
	
			dragToggle = true
	
			dragStart = input.Position
	
			startPos = frame.Position
	
			input.Changed:Connect(function()
	
				if input.UserInputState == Enum.UserInputState.End then
	
					dragToggle = false
	
				end
	
			end)
	
		end
	
	end)
	
	
	
	UIS.InputChanged:Connect(function(input)
	
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
	
			if dragToggle then
	
				updateInput(input)
	
			end
	
		end
	
	end)
	
	
	
	
end
coroutine.wrap(FLNFQO_fake_script)()
local function PHUWDG_fake_script() -- ImageLabel.LocalScript 
	local script = Instance.new('LocalScript', ImageLabel)

	while true do
		script.Parent.BackgroundColor3 = Color3.new (255, 176, 0)
		wait(.7)
		script.Parent.BackgroundColor3 = Color3.new (0, 255, 0)
		wait(.7)
		script.Parent.BackgroundColor3 = Color3.new (255, 0, 0)
		wait(.7)
		script.Parent.BackgroundColor3 = Color3.new (170, 85, 0)
		wait(.7)
		script.Parent.BackgroundColor3 = Color3.new (106, 57, 9)
		wait(.7)
		script.Parent.BackgroundColor3 = Color3.new (0, 16, 176)
		wait(.7)
	end
end
coroutine.wrap(PHUWDG_fake_script)()
local function FCIPU_fake_script() -- CloseButton.LocalScript 
	local script = Instance.new('LocalScript', CloseButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(FCIPU_fake_script)()
local function AMVCBW_fake_script() -- CloseButton.ANIME 
	local script = Instance.new('LocalScript', CloseButton)

	local btn = script.Parent
	local uiGradient = btn:WaitForChild("UIGradient")
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.4, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local gradientRestoreTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(-0.35, 0)})
	local gradientAddTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(1, 0)})
	
	
	btn.MouseEnter:Connect(function()
		
		isHovering = true
		
		gradientAddTween:Play()
	end)
	
	btn.MouseLeave:Connect(function()
		
		isHovering = false
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Down:Connect(function()
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Up:Connect(function()
		
		if not isHovering then
			gradientRestoreTween:Play()
		else
			gradientAddTween:Play()
		end
	end)
end
coroutine.wrap(AMVCBW_fake_script)()
local function EBVOY_fake_script() -- Button1.METAB SCRIPT 
	local script = Instance.new('LocalScript', Button1)

	script.Parent.MouseButton1Down:connect(function()
	
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-426.94769287109, 122.1196975708, -421.42504882813)
	
		local vim = game:service'VirtualInputManager'
	
		while wait(.5) do
			vim:SendKeyEvent(true, "E", false, game)
		end
	
	
	while true do 
		wait()
		local UwU = game.Players.LocalPlayer.Character.HumanoidRootPart
		for i,v in pairs(game.workspace.DroppedCandyFolder:GetChildren()) do
			UwU.CFrame = v.CFrame
		end
		end
		end)
	
end
coroutine.wrap(EBVOY_fake_script)()
local function IDNH_fake_script() -- Button2.Button7Script 
	local script = Instance.new('LocalScript', Button2)

	local btn = script.Parent
	local uiGradient = btn:WaitForChild("UIGradient")
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.4, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local gradientRestoreTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(-0.35, 0)})
	local gradientAddTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(1, 0)})
	
	
	btn.MouseEnter:Connect(function()
		
		isHovering = true
		
		gradientAddTween:Play()
	end)
	
	btn.MouseLeave:Connect(function()
		
		isHovering = false
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Down:Connect(function()
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Up:Connect(function()
		
		if not isHovering then
			gradientRestoreTween:Play()
		else
			gradientAddTween:Play()
		end
	end)
end
coroutine.wrap(IDNH_fake_script)()
local function JMAVMKC_fake_script() -- Button2.METAB SCRIPT 
	local script = Instance.new('LocalScript', Button2)

	
	script.Parent.MouseButton1Down:connect(function()
	
	
		script.Parent.MouseButton1Down:connect(function()
			local player = game.Players.LocalPlayer
			position     = player.Character.HumanoidRootPart.Position
			wait(0.1)
			player.Character:MoveTo(position + Vector3.new(0, 1000000, 0))
			wait(0.1)
			humanoidrootpart = player.Character.HumanoidRootPart:clone()
			wait(0.1)
			player.Character.HumanoidRootPart:Destroy()
			humanoidrootpart.Parent = player.Character
			player.Character:MoveTo(position)
			wait()
		end)
		
		end)
	
	
	
	
	
end
coroutine.wrap(JMAVMKC_fake_script)()
local function WNBFCYT_fake_script() -- Button2_2.Button7Script 
	local script = Instance.new('LocalScript', Button2_2)

	local btn = script.Parent
	local uiGradient = btn:WaitForChild("UIGradient")
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.4, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local gradientRestoreTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(-0.35, 0)})
	local gradientAddTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(1, 0)})
	
	
	btn.MouseEnter:Connect(function()
		
		isHovering = true
		
		gradientAddTween:Play()
	end)
	
	btn.MouseLeave:Connect(function()
		
		isHovering = false
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Down:Connect(function()
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Up:Connect(function()
		
		if not isHovering then
			gradientRestoreTween:Play()
		else
			gradientAddTween:Play()
		end
	end)
end
coroutine.wrap(WNBFCYT_fake_script)()
local function ZSKKOMR_fake_script() -- Button2_2.METAB SCRIPT 
	local script = Instance.new('LocalScript', Button2_2)

	
	script.Parent.MouseButton1Down:connect(function()
	
		game.Workspace.Part.Anchored = true
		if game.Workspace.Part.Anchored == true then
			wait(10) 
			game.Workspace.Part.Anchored = false
	
			if game.Players.LocalPlayer.Character.Humanoid.Seated == true then  --[ Detects if your humanoid is currently sitting or not ]--
				if game.Players.LocalPlayer.Character.Humanoid.SeatPart.Anchored == true then --[ It then detects if the SeatPart is Anchored ]--
					game.Players.LocalPlayer.Character.Humanoid.SeatPart.Anchored = false --[ Changes the value to false so now the seat is UnAnchored ]--
				end
			end
	
			if game.Players.LocalPlayer.Character.Humanoid.Seated == true then
				game.Players.LocalPlayer.Humanoid.RootPart.Anchored = true
				game.Players.LocalPlayer.PlayerScripts.ControlScript.Disabled = true -- I think this disables you from moving though
			end
		end
	
		game:GetService('Players').LocalPlayer.Character.Humanoid.Name = "Humanoida"
		repeat wait()
		until game:GetService"Players".LocalPlayer and game:GetService"Players".LocalPlayer.Character and game:GetService"Players".LocalPlayer.Character:findFirstChild("UpperTorso") and game:GetService"Players".LocalPlayer.Character:findFirstChild("Humanoida")
		local mouse = game:GetService"Players".LocalPlayer:GetMouse()
		repeat wait() until mouse
		local plr = game:GetService"Players".LocalPlayer
		local torso = plr.Character.UpperTorso
		local flying = true
		local deb = true
		local ctrl = {f = 0, b = 0, l = 0, r = 0}
		local lastctrl = {f = 0, b = 0, l = 0, r = 0}
		local maxspeed = 100
		local speed = 0
	
		function Fly()
			local bg = Instance.new("BodyGyro", torso)
			bg.P = 9e4
			bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
			bg.cframe = torso.CFrame
			local bv = Instance.new("BodyVelocity", torso)
			bv.velocity = Vector3.new(0,0.1,0)
			bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
			repeat wait()
				--plr.Character.Humanoida.PlatformStand = true
				if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
					speed = speed+.5+(speed/maxspeed)
					if speed > maxspeed then
						speed = maxspeed
					end
				elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
					speed = speed-1
					if speed < 0 then
						speed = 0
					end
				end
				if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
					bv.velocity = ((game:GetService("Workspace").CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game:GetService("Workspace").CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game:GetService("Workspace").CurrentCamera.CoordinateFrame.p))*speed
					lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
				elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
					bv.velocity = ((game:GetService("Workspace").CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game:GetService("Workspace").CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game:GetService("Workspace").CurrentCamera.CoordinateFrame.p))*speed
				else
					bv.velocity = Vector3.new(0,0.1,0)
				end
				bg.cframe = game:GetService("Workspace").CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
			until not flying
			ctrl = {f = 0, b = 0, l = 0, r = 0}
			lastctrl = {f = 0, b = 0, l = 0, r = 0}
			speed = 0
			bg:Destroy()
			bv:Destroy()
			--plr.Character.Humanoida.PlatformStand = false
		end
		mouse.KeyDown:connect(function(key)
			if key:lower() == "p" then
				if flying then flying = false
				else
					flying = true
					Fly()
				end
			elseif key:lower() == "w" then
				ctrl.f = 1
			elseif key:lower() == "s" then
				ctrl.b = -1
			elseif key:lower() == "a" then
				ctrl.l = -1
			elseif key:lower() == "d" then
				ctrl.r = 1
			end
		end)
		mouse.KeyUp:connect(function(key)
			if key:lower() == "w" then
				ctrl.f = 0
			elseif key:lower() == "s" then
				ctrl.b = 0
			elseif key:lower() == "a" then
				ctrl.l = 0
			elseif key:lower() == "d" then
				ctrl.r = 0
			end
		end)
		Fly()
		end)
	
	
	
	
	
end
coroutine.wrap(ZSKKOMR_fake_script)()
local function MZDH_fake_script() -- Button1_2.ANIME 
	local script = Instance.new('LocalScript', Button1_2)

	local btn = script.Parent
	local uiGradient = btn:WaitForChild("UIGradient")
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.4, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local gradientRestoreTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(-0.35, 0)})
	local gradientAddTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(1, 0)})
	
	
	btn.MouseEnter:Connect(function()
		
		isHovering = true
		
		gradientAddTween:Play()
	end)
	
	btn.MouseLeave:Connect(function()
		
		isHovering = false
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Down:Connect(function()
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Up:Connect(function()
		
		if not isHovering then
			gradientRestoreTween:Play()
		else
			gradientAddTween:Play()
		end
	end)
end
coroutine.wrap(MZDH_fake_script)()
local function WEQHELR_fake_script() -- Button1_2.METAB SCRIPT 
	local script = Instance.new('LocalScript', Button1_2)

	
	
	
	
	
	toggle = false
	script.Parent.MouseButton1Down:connect(function()
	
		if toggle == true then 
			toggle = false 
		else
			toggle = true
		end
		if toggle == true then 
			script.Parent.ImageColor3 = Color3.fromRGB(0, 255, 0)
		end
		if toggle == false then 
			script.Parent.ImageColor3 = Color3.fromRGB(170, 0, 0)
		end
	
		if toggle == true then
			_G.Toggle = true
			while _G.Toggle do
				wait(2)
	
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-348.77319335938, 125.1031036377, -318.32928466797)
					wait(3)
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-813.97332763672, 121.34390258789, -759.89318847656)
					wait(3)
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-813.97332763672, 121.34390258789, -759.89318847656)
					wait(3)
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-546.83831787109, 106.13489532471, -883.93634033203)
					wait(3)
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-500.14877319336, 107.79285430908, -796.86901855469)
					wait(3)
				end
			end
		if toggle == false then 
			_G.Toggle = false
			while _G.Toggle do
				wait()
	
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-348.77319335938, 125.1031036377, -318.32928466797)
				wait(3)
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-813.97332763672, 121.34390258789, -759.89318847656)
				wait(3)
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-813.97332763672, 121.34390258789, -759.89318847656)
				wait(3)
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-546.83831787109, 106.13489532471, -883.93634033203)
				wait(3)
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-500.14877319336, 107.79285430908, -796.86901855469)
				wait(3)
			end
		end
		end)
	
	
	
	
	
	
	
	
end
coroutine.wrap(WEQHELR_fake_script)()
local function DLIPXU_fake_script() -- Button1_2.ANIME 
	local script = Instance.new('LocalScript', Button1_2)

	local btn = script.Parent
	local uiGradient = btn:WaitForChild("UIGradient")
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.4, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local gradientRestoreTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(-0.35, 0)})
	local gradientAddTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(1, 0)})
	
	
	btn.MouseEnter:Connect(function()
		
		isHovering = true
		
		gradientAddTween:Play()
	end)
	
	btn.MouseLeave:Connect(function()
		
		isHovering = false
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Down:Connect(function()
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Up:Connect(function()
		
		if not isHovering then
			gradientRestoreTween:Play()
		else
			gradientAddTween:Play()
		end
	end)
end
coroutine.wrap(DLIPXU_fake_script)()
local function IVXL_fake_script() -- ImageButton.LocalScript 
	local script = Instance.new('LocalScript', ImageButton)

	script.Parent.MouseButton1Click:connect(function()
		script.Parent.Parent.ImageLabel.Visible = not script.Parent.Parent.ImageLabel.Visible
	end)
	
end
coroutine.wrap(IVXL_fake_script)()
