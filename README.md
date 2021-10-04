
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
local Button3 = Instance.new("ImageButton")
local UIAspectRatioConstraint_4 = Instance.new("UIAspectRatioConstraint")
local BtnText_3 = Instance.new("TextLabel")
local Button3_2 = Instance.new("ImageButton")
local UIGradient_4 = Instance.new("UIGradient")
local UIAspectRatioConstraint_5 = Instance.new("UIAspectRatioConstraint")
local BtnText_4 = Instance.new("TextLabel")
local UIGradient_5 = Instance.new("UIGradient")
local Button3_3 = Instance.new("ImageButton")
local UIAspectRatioConstraint_6 = Instance.new("UIAspectRatioConstraint")
local BtnText_5 = Instance.new("TextLabel")
local Button3_4 = Instance.new("ImageButton")
local UIGradient_6 = Instance.new("UIGradient")
local UIAspectRatioConstraint_7 = Instance.new("UIAspectRatioConstraint")
local BtnText_6 = Instance.new("TextLabel")
local UIGradient_7 = Instance.new("UIGradient")
local Button3_5 = Instance.new("ImageButton")
local UIAspectRatioConstraint_8 = Instance.new("UIAspectRatioConstraint")
local BtnText_7 = Instance.new("TextLabel")
local UIGradient_8 = Instance.new("UIGradient")
local Button3_6 = Instance.new("ImageButton")
local UIAspectRatioConstraint_9 = Instance.new("UIAspectRatioConstraint")
local BtnText_8 = Instance.new("TextLabel")
local UIGradient_9 = Instance.new("UIGradient")
local Button3_7 = Instance.new("ImageButton")
local UIAspectRatioConstraint_10 = Instance.new("UIAspectRatioConstraint")
local BtnText_9 = Instance.new("TextLabel")
local UIGradient_10 = Instance.new("UIGradient")
local Button3_8 = Instance.new("ImageButton")
local UIAspectRatioConstraint_11 = Instance.new("UIAspectRatioConstraint")
local BtnText_10 = Instance.new("TextLabel")
local UIGradient_11 = Instance.new("UIGradient")
local Button3_9 = Instance.new("ImageButton")
local UIAspectRatioConstraint_12 = Instance.new("UIAspectRatioConstraint")
local BtnText_11 = Instance.new("TextLabel")
local UIGradient_12 = Instance.new("UIGradient")
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
ScrollingFrame.ScrollBarThickness = 0
ScrollingFrame.VerticalScrollBarPosition = Enum.VerticalScrollBarPosition.Left

Button1.Name = "Button 1 "
Button1.Parent = ScrollingFrame
Button1.AnchorPoint = Vector2.new(1, 1)
Button1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button1.BackgroundTransparency = 1.000
Button1.BorderSizePixel = 5
Button1.Position = UDim2.new(0.945403278, 0, 0.0691872388, 0)
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
Button2.Position = UDim2.new(0.945403278, 0, 0.133211643, 0)
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

Button3.Name = "Button 3"
Button3.Parent = ScrollingFrame
Button3.AnchorPoint = Vector2.new(1, 1)
Button3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button3.BackgroundTransparency = 1.000
Button3.Position = UDim2.new(0.945403278, 0, 0.197236031, 0)
Button3.Size = UDim2.new(0.882225692, 0, 0.0763209537, 0)
Button3.Image = "rbxassetid://2790382281"
Button3.ImageColor3 = Color3.fromRGB(26, 190, 190)
Button3.ScaleType = Enum.ScaleType.Slice
Button3.SliceCenter = Rect.new(4, 4, 252, 252)

UIAspectRatioConstraint_4.Parent = Button3
UIAspectRatioConstraint_4.AspectRatio = 3.042

BtnText_3.Name = "BtnText"
BtnText_3.Parent = Button3
BtnText_3.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_3.BackgroundTransparency = 1.000
BtnText_3.BorderSizePixel = 0
BtnText_3.Position = UDim2.new(0.498592883, 0, 0.488144726, 0)
BtnText_3.Size = UDim2.new(0.891457498, -5, 0.468874484, -5)
BtnText_3.Font = Enum.Font.GothamBlack
BtnText_3.Text = "UNIFORM"
BtnText_3.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_3.TextScaled = true
BtnText_3.TextSize = 14.000
BtnText_3.TextWrapped = true

Button3_2.Name = "Button 3"
Button3_2.Parent = BtnText_3
Button3_2.AnchorPoint = Vector2.new(1, 1)
Button3_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button3_2.BackgroundTransparency = 1.000
Button3_2.Position = UDim2.new(0.945403278, 0, 3.17218471, 0)
Button3_2.Size = UDim2.new(0.882225692, 0, 0.0763209537, 0)
Button3_2.Image = "rbxassetid://2790382281"
Button3_2.ImageColor3 = Color3.fromRGB(26, 190, 190)
Button3_2.ScaleType = Enum.ScaleType.Slice
Button3_2.SliceCenter = Rect.new(4, 4, 252, 252)

UIGradient_4.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 136, 255))}
UIGradient_4.Offset = Vector2.new(-0.349999994, 0)
UIGradient_4.Rotation = -135
UIGradient_4.Parent = Button3_2

UIAspectRatioConstraint_5.Parent = Button3_2
UIAspectRatioConstraint_5.AspectRatio = 3.042

BtnText_4.Name = "BtnText"
BtnText_4.Parent = Button3_2
BtnText_4.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_4.BackgroundTransparency = 1.000
BtnText_4.BorderSizePixel = 0
BtnText_4.Position = UDim2.new(0.498592883, 0, 0.488144726, 0)
BtnText_4.Size = UDim2.new(0.891457498, -5, 0.468874484, -5)
BtnText_4.Font = Enum.Font.GothamBlack
BtnText_4.Text = "NOCLIP"
BtnText_4.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_4.TextScaled = true
BtnText_4.TextSize = 14.000
BtnText_4.TextWrapped = true

UIGradient_5.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(0.98, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient_5.Offset = Vector2.new(-0.349999994, 0)
UIGradient_5.Rotation = -135
UIGradient_5.Parent = Button3

Button3_3.Name = "Button 3"
Button3_3.Parent = ScrollingFrame
Button3_3.AnchorPoint = Vector2.new(1, 1)
Button3_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button3_3.BackgroundTransparency = 1.000
Button3_3.Position = UDim2.new(0.945403278, 0, 0.262276679, 0)
Button3_3.Size = UDim2.new(0.882225692, 0, 0.0763209537, 0)
Button3_3.Image = "rbxassetid://2790382281"
Button3_3.ImageColor3 = Color3.fromRGB(26, 190, 190)
Button3_3.ScaleType = Enum.ScaleType.Slice
Button3_3.SliceCenter = Rect.new(4, 4, 252, 252)

UIAspectRatioConstraint_6.Parent = Button3_3
UIAspectRatioConstraint_6.AspectRatio = 3.042

BtnText_5.Name = "BtnText"
BtnText_5.Parent = Button3_3
BtnText_5.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_5.BackgroundTransparency = 1.000
BtnText_5.BorderSizePixel = 0
BtnText_5.Position = UDim2.new(0.498592883, 0, 0.488144726, 0)
BtnText_5.Size = UDim2.new(0.891457498, -5, 0.468874484, -5)
BtnText_5.Font = Enum.Font.GothamBlack
BtnText_5.Text = "ESP"
BtnText_5.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_5.TextScaled = true
BtnText_5.TextSize = 14.000
BtnText_5.TextWrapped = true

Button3_4.Name = "Button 3"
Button3_4.Parent = Button3_3
Button3_4.AnchorPoint = Vector2.new(1, 1)
Button3_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button3_4.BackgroundTransparency = 1.000
Button3_4.Position = UDim2.new(0.945403278, 0, 1.41178334, 0)
Button3_4.Size = UDim2.new(0.882225692, 0, 0.0763209537, 0)
Button3_4.Image = "rbxassetid://2790382281"
Button3_4.ImageColor3 = Color3.fromRGB(26, 190, 190)
Button3_4.ScaleType = Enum.ScaleType.Slice
Button3_4.SliceCenter = Rect.new(4, 4, 252, 252)

UIGradient_6.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 136, 255))}
UIGradient_6.Offset = Vector2.new(-0.349999994, 0)
UIGradient_6.Rotation = -135
UIGradient_6.Parent = Button3_4

UIAspectRatioConstraint_7.Parent = Button3_4
UIAspectRatioConstraint_7.AspectRatio = 3.042

BtnText_6.Name = "BtnText"
BtnText_6.Parent = Button3_4
BtnText_6.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_6.BackgroundTransparency = 1.000
BtnText_6.BorderSizePixel = 0
BtnText_6.Position = UDim2.new(0.498592883, 0, 0.488144726, 0)
BtnText_6.Size = UDim2.new(0.891457498, -5, 0.468874484, -5)
BtnText_6.Font = Enum.Font.GothamBlack
BtnText_6.Text = "ESP"
BtnText_6.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_6.TextScaled = true
BtnText_6.TextSize = 14.000
BtnText_6.TextWrapped = true

UIGradient_7.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(0.98, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient_7.Offset = Vector2.new(-0.349999994, 0)
UIGradient_7.Rotation = -135
UIGradient_7.Parent = Button3_3

Button3_5.Name = "Button 3"
Button3_5.Parent = ScrollingFrame
Button3_5.AnchorPoint = Vector2.new(1, 1)
Button3_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button3_5.BackgroundTransparency = 1.000
Button3_5.Position = UDim2.new(0.945403278, 0, 0.328333586, 0)
Button3_5.Size = UDim2.new(0.882225692, 0, 0.0763209537, 0)
Button3_5.Image = "rbxassetid://2790382281"
Button3_5.ImageColor3 = Color3.fromRGB(26, 190, 190)
Button3_5.ScaleType = Enum.ScaleType.Slice
Button3_5.SliceCenter = Rect.new(4, 4, 252, 252)

UIAspectRatioConstraint_8.Parent = Button3_5
UIAspectRatioConstraint_8.AspectRatio = 3.042

BtnText_7.Name = "BtnText"
BtnText_7.Parent = Button3_5
BtnText_7.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_7.BackgroundTransparency = 1.000
BtnText_7.BorderSizePixel = 0
BtnText_7.Position = UDim2.new(0.498592883, 0, 0.488144726, 0)
BtnText_7.Size = UDim2.new(0.891457498, -5, 0.468874484, -5)
BtnText_7.Font = Enum.Font.GothamBlack
BtnText_7.Text = "FLY"
BtnText_7.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_7.TextScaled = true
BtnText_7.TextSize = 14.000
BtnText_7.TextWrapped = true

UIGradient_8.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(0.98, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient_8.Offset = Vector2.new(-0.349999994, 0)
UIGradient_8.Rotation = -135
UIGradient_8.Parent = Button3_5

Button3_6.Name = "Button 3"
Button3_6.Parent = ScrollingFrame
Button3_6.AnchorPoint = Vector2.new(1, 1)
Button3_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button3_6.BackgroundTransparency = 1.000
Button3_6.Position = UDim2.new(0.940275073, 0, 0.393374234, 0)
Button3_6.Size = UDim2.new(0.882225692, 0, 0.0763209537, 0)
Button3_6.Image = "rbxassetid://2790382281"
Button3_6.ImageColor3 = Color3.fromRGB(26, 190, 190)
Button3_6.ScaleType = Enum.ScaleType.Slice
Button3_6.SliceCenter = Rect.new(4, 4, 252, 252)

UIAspectRatioConstraint_9.Parent = Button3_6
UIAspectRatioConstraint_9.AspectRatio = 3.042

BtnText_8.Name = "BtnText"
BtnText_8.Parent = Button3_6
BtnText_8.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_8.BackgroundTransparency = 1.000
BtnText_8.BorderSizePixel = 0
BtnText_8.Position = UDim2.new(0.498592883, 0, 0.488144726, 0)
BtnText_8.Size = UDim2.new(0.891457498, -5, 0.468874484, -5)
BtnText_8.Font = Enum.Font.GothamBlack
BtnText_8.Text = "ADMIN BUTTON 1"
BtnText_8.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_8.TextScaled = true
BtnText_8.TextSize = 14.000
BtnText_8.TextWrapped = true

UIGradient_9.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(0.98, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient_9.Offset = Vector2.new(-0.349999994, 0)
UIGradient_9.Rotation = -135
UIGradient_9.Parent = Button3_6

Button3_7.Name = "Button 3"
Button3_7.Parent = Button3_6
Button3_7.AnchorPoint = Vector2.new(1, 1)
Button3_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button3_7.BackgroundTransparency = 1.000
Button3_7.Position = UDim2.new(0.946087897, 0, 1.50751138, 0)
Button3_7.Size = UDim2.new(0.882225692, 0, 0.0763209537, 0)
Button3_7.Image = "rbxassetid://2790382281"
Button3_7.ImageColor3 = Color3.fromRGB(26, 190, 190)
Button3_7.ScaleType = Enum.ScaleType.Slice
Button3_7.SliceCenter = Rect.new(4, 4, 252, 252)

UIAspectRatioConstraint_10.Parent = Button3_7
UIAspectRatioConstraint_10.AspectRatio = 3.042

BtnText_9.Name = "BtnText"
BtnText_9.Parent = Button3_7
BtnText_9.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_9.BackgroundTransparency = 1.000
BtnText_9.BorderSizePixel = 0
BtnText_9.Position = UDim2.new(0.498592883, 0, 0.488144726, 0)
BtnText_9.Size = UDim2.new(0.891457498, -5, 0.468874484, -5)
BtnText_9.Font = Enum.Font.GothamBlack
BtnText_9.Text = "ADMIN MUSIC 1"
BtnText_9.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_9.TextScaled = true
BtnText_9.TextSize = 14.000
BtnText_9.TextWrapped = true

UIGradient_10.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(0.98, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient_10.Offset = Vector2.new(-0.349999994, 0)
UIGradient_10.Rotation = -135
UIGradient_10.Parent = Button3_7

Button3_8.Name = "Button 3"
Button3_8.Parent = ScrollingFrame
Button3_8.AnchorPoint = Vector2.new(1, 1)
Button3_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button3_8.BackgroundTransparency = 1.000
Button3_8.Position = UDim2.new(0.945403278, 0, 0.457398623, 0)
Button3_8.Size = UDim2.new(0.882225692, 0, 0.0763209537, 0)
Button3_8.Image = "rbxassetid://2790382281"
Button3_8.ImageColor3 = Color3.fromRGB(26, 190, 190)
Button3_8.ScaleType = Enum.ScaleType.Slice
Button3_8.SliceCenter = Rect.new(4, 4, 252, 252)

UIAspectRatioConstraint_11.Parent = Button3_8
UIAspectRatioConstraint_11.AspectRatio = 3.042

BtnText_10.Name = "BtnText"
BtnText_10.Parent = Button3_8
BtnText_10.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_10.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_10.BackgroundTransparency = 1.000
BtnText_10.BorderSizePixel = 0
BtnText_10.Position = UDim2.new(0.498592883, 0, 0.488144726, 0)
BtnText_10.Size = UDim2.new(0.891457498, -5, 0.468874484, -5)
BtnText_10.Font = Enum.Font.GothamBlack
BtnText_10.Text = "ADMIN BUTTON 2"
BtnText_10.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_10.TextScaled = true
BtnText_10.TextSize = 14.000
BtnText_10.TextWrapped = true

UIGradient_11.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(0.98, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient_11.Offset = Vector2.new(-0.349999994, 0)
UIGradient_11.Rotation = -135
UIGradient_11.Parent = Button3_8

Button3_9.Name = "Button 3"
Button3_9.Parent = ScrollingFrame
Button3_9.AnchorPoint = Vector2.new(1, 1)
Button3_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button3_9.BackgroundTransparency = 1.000
Button3_9.Position = UDim2.new(0.945403278, 0, 0.522439241, 0)
Button3_9.Size = UDim2.new(0.882225692, 0, 0.0763209537, 0)
Button3_9.Image = "rbxassetid://2790382281"
Button3_9.ImageColor3 = Color3.fromRGB(26, 190, 190)
Button3_9.ScaleType = Enum.ScaleType.Slice
Button3_9.SliceCenter = Rect.new(4, 4, 252, 252)

UIAspectRatioConstraint_12.Parent = Button3_9
UIAspectRatioConstraint_12.AspectRatio = 3.042

BtnText_11.Name = "BtnText"
BtnText_11.Parent = Button3_9
BtnText_11.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_11.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_11.BackgroundTransparency = 1.000
BtnText_11.BorderSizePixel = 0
BtnText_11.Position = UDim2.new(0.498592883, 0, 0.488144726, 0)
BtnText_11.Size = UDim2.new(0.891457498, -5, 0.468874484, -5)
BtnText_11.Font = Enum.Font.GothamBlack
BtnText_11.Text = "ADMIN BUTTON 3"
BtnText_11.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_11.TextScaled = true
BtnText_11.TextSize = 14.000
BtnText_11.TextWrapped = true

UIGradient_12.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(0.98, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient_12.Offset = Vector2.new(-0.349999994, 0)
UIGradient_12.Rotation = -135
UIGradient_12.Parent = Button3_9

ImageButton.Parent = InsertedObjects
ImageButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageButton.BackgroundTransparency = 1.000
ImageButton.Position = UDim2.new(0.416326493, 0, 0, 0)
ImageButton.Size = UDim2.new(0, 123, 0, 60)
ImageButton.Image = "http://www.roblox.com/asset/?id=7529900564"

-- Scripts:

local function QWNPUJG_fake_script() -- ImageLabel.LocalScript 
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
coroutine.wrap(QWNPUJG_fake_script)()
local function VCUNIKT_fake_script() -- ImageLabel.LocalScript 
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
coroutine.wrap(VCUNIKT_fake_script)()
local function EBWYYTO_fake_script() -- CloseButton.LocalScript 
	local script = Instance.new('LocalScript', CloseButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(EBWYYTO_fake_script)()
local function VNHKB_fake_script() -- CloseButton.ANIME 
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
coroutine.wrap(VNHKB_fake_script)()
local function LPRWJ_fake_script() -- Button1.ANIME 
	local script = Instance.new('LocalScript', Button1)

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
coroutine.wrap(LPRWJ_fake_script)()
local function VHVMV_fake_script() -- Button1.METAB SCRIPT 
	local script = Instance.new('LocalScript', Button1)

	
	script.Parent.MouseButton1Down:connect(function()
	
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-426.94769287109, 122.1196975708, -421.42504882813)
	
		local vim = game:service'VirtualInputManager'
	
		while wait(.5) do
			vim:SendKeyEvent(true, "E", false, game)
		end
	end)
	
	while true do 
		wait(0.5)
		local UwU = game.Players.LocalPlayer.Character.HumanoidRootPart
		for i,v in pairs(game.workspace.DroppedCandyFolder:GetChildren()) do
			UwU.CFrame = v.CFrame
		end
	end
	
	
	
end
coroutine.wrap(VHVMV_fake_script)()
local function CJSO_fake_script() -- Button2.Button7Script 
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
coroutine.wrap(CJSO_fake_script)()
local function WKTJOBL_fake_script() -- Button2.METAB SCRIPT 
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
coroutine.wrap(WKTJOBL_fake_script)()
local function QUXUCDM_fake_script() -- Button3.ANIME 
	local script = Instance.new('LocalScript', Button3)

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
coroutine.wrap(QUXUCDM_fake_script)()
local function LWKC_fake_script() -- Button3_2.ANIME 
	local script = Instance.new('LocalScript', Button3_2)

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
coroutine.wrap(LWKC_fake_script)()
local function HTAVBBE_fake_script() -- Button3_2.METAB SCRIPT 
	local script = Instance.new('LocalScript', Button3_2)

	
	script.Parent.MouseButton1Down:connect(function()
	
		game:GetService("Players").NocturneMoDz.PlayerGui.AnimationGui.Enabled = true
	end)
	
	
	
	
	
	
end
coroutine.wrap(HTAVBBE_fake_script)()
local function AQYO_fake_script() -- Button3.METAB SCRIPT 
	local script = Instance.new('LocalScript', Button3)

	
	script.Parent.MouseButton1Down:connect(function()
	
		for i,v in pairs(workspace:GetDescendants()) do
			if v:IsA("ClickDetector") then
				fireclickdetector(v)
			end
		end
	end)
	
	
	
	
	
	
end
coroutine.wrap(AQYO_fake_script)()
local function NYUTILX_fake_script() -- Button3_3.ANIME 
	local script = Instance.new('LocalScript', Button3_3)

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
coroutine.wrap(NYUTILX_fake_script)()
local function BGBKP_fake_script() -- Button3_3.METAB SCRIPT 
	local script = Instance.new('LocalScript', Button3_3)

	
	script.Parent.MouseButton1Down:connect(function()
	
	
			local CurrentCamera = workspace.CurrentCamera
			local LocalPlayer = game.Players.LocalPlayer
			local Camera = workspace.Camera
			local RunService = game:service('RunService')
			local Players = game:GetService("Players")
	
			local CreateInfo = function(Type, Player)
	
	
				local DrawingFunction = function() return false end
	
	
				--// To check what type they created.
	
				if Type == "Names" then
	
	
					--// Create the drawings.
	
					local Label = Drawing.new("Text")
	
					Label.Center = true
					Label.Outline = true
					Label.Font = Drawing.Fonts.Monospace
					Label.Size = 15
	
	
					--// Redo the function on line:32
	
					DrawingFunction = function()
	
	
						--// Make the checks to see if we can draw on the character without problems.
	
						if Player and Player.Character and Player.Character:WaitForChild("HumanoidRootPart") and Player.Character:FindFirstChild("Head") then
	
	
							--// This is too see where to put the drawing instances on line:42 or see if the player is OnScreen
	
							local Pos, Vis = CurrentCamera:WorldToViewportPoint(Player.Character.Head.CFrame.Position)
	
	
							--// Make the label invisible if the player is not OnScreen
	
							Label.Text = Player.Name
							Label.Color = Player.TeamColor.Color
	
							if Vis then
								Label.Visible = true
							else
								Label.Visible = false
							end
	
							Label.Position = Vector2.new(Pos.X, Pos.Y)
	
	
						else
	
							Label.Visible = false
	
						end
	
					end
	
				end
	
				RunService:BindToRenderStep("NameTags", 1, DrawingFunction)
	
			end
	
			for i,v in next, Players:GetPlayers() do
				if v ~= LocalPlayer then
					CreateInfo("Names", v)
				end
			end
	
			Players.PlayerAdded:connect(function(plr)
				CreateInfo("Names", plr)
			end)
		end)
	
end
coroutine.wrap(BGBKP_fake_script)()
local function GPOLC_fake_script() -- Button3_4.ANIME 
	local script = Instance.new('LocalScript', Button3_4)

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
coroutine.wrap(GPOLC_fake_script)()
local function KQPXCHV_fake_script() -- Button3_4.METAB SCRIPT 
	local script = Instance.new('LocalScript', Button3_4)

	
	script.Parent.MouseButton1Down:connect(function()
	
	
			local CurrentCamera = workspace.CurrentCamera
			local LocalPlayer = game.Players.LocalPlayer
			local Camera = workspace.Camera
			local RunService = game:service('RunService')
			local Players = game:GetService("Players")
	
			local CreateInfo = function(Type, Player)
	
	
				local DrawingFunction = function() return false end
	
	
				--// To check what type they created.
	
				if Type == "Names" then
	
	
					--// Create the drawings.
	
					local Label = Drawing.new("Text")
	
					Label.Center = true
					Label.Outline = true
					Label.Font = Drawing.Fonts.Monospace
					Label.Size = 15
	
	
					--// Redo the function on line:32
	
					DrawingFunction = function()
	
	
						--// Make the checks to see if we can draw on the character without problems.
	
						if Player and Player.Character and Player.Character:WaitForChild("HumanoidRootPart") and Player.Character:FindFirstChild("Head") then
	
	
							--// This is too see where to put the drawing instances on line:42 or see if the player is OnScreen
	
							local Pos, Vis = CurrentCamera:WorldToViewportPoint(Player.Character.Head.CFrame.Position)
	
	
							--// Make the label invisible if the player is not OnScreen
	
							Label.Text = Player.Name
							Label.Color = Player.TeamColor.Color
	
							if Vis then
								Label.Visible = true
							else
								Label.Visible = false
							end
	
							Label.Position = Vector2.new(Pos.X, Pos.Y)
	
	
						else
	
							Label.Visible = false
	
						end
	
					end
	
				end
	
				RunService:BindToRenderStep("NameTags", 1, DrawingFunction)
	
			end
	
			for i,v in next, Players:GetPlayers() do
				if v ~= LocalPlayer then
					CreateInfo("Names", v)
				end
			end
	
			Players.PlayerAdded:connect(function(plr)
				CreateInfo("Names", plr)
			end)
		end)
	
end
coroutine.wrap(KQPXCHV_fake_script)()
local function QFLCX_fake_script() -- Button3_5.ANIME 
	local script = Instance.new('LocalScript', Button3_5)

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
coroutine.wrap(QFLCX_fake_script)()
local function JACMW_fake_script() -- Button3_5.METAB SCRIPT 
	local script = Instance.new('LocalScript', Button3_5)

	script.Parent.MouseButton1Down:connect(function()
	
		loadstring(game:HttpGet("https://pastebin.com/raw/7rXZ9VNc", true))()
	end)
	
	
	
	
	
	
end
coroutine.wrap(JACMW_fake_script)()
local function GATHH_fake_script() -- Button3_6.ANIME 
	local script = Instance.new('LocalScript', Button3_6)

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
coroutine.wrap(GATHH_fake_script)()
local function COXOMD_fake_script() -- Button3_6.METAB SCRIPT 
	local script = Instance.new('LocalScript', Button3_6)

	script.Parent.MouseButton1Down:connect(function()
	
	
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-158.29211425781, 84.623199462891, -311.79965209961)
	
	end)
	
	
	
	
	
	
end
coroutine.wrap(COXOMD_fake_script)()
local function OKYA_fake_script() -- Button3_7.ANIME 
	local script = Instance.new('LocalScript', Button3_7)

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
coroutine.wrap(OKYA_fake_script)()
local function JGSN_fake_script() -- Button3_7.METAB SCRIPT 
	local script = Instance.new('LocalScript', Button3_7)

	script.Parent.MouseButton1Down:connect(function()
	
	
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-158.29211425781, 84.623199462891, -311.79965209961)
	
	end)
	
	
	
	
	
	
end
coroutine.wrap(JGSN_fake_script)()
local function RLNNWDG_fake_script() -- Button3_8.ANIME 
	local script = Instance.new('LocalScript', Button3_8)

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
coroutine.wrap(RLNNWDG_fake_script)()
local function NWSQZ_fake_script() -- Button3_8.METAB SCRIPT 
	local script = Instance.new('LocalScript', Button3_8)

	script.Parent.MouseButton1Down:connect(function()
	
	
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(64.809074401855, 133.03405761719, 27.204072952271)
	
	end)
	
	
	
	
	
	
end
coroutine.wrap(NWSQZ_fake_script)()
local function CRKCWMP_fake_script() -- Button3_9.ANIME 
	local script = Instance.new('LocalScript', Button3_9)

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
coroutine.wrap(CRKCWMP_fake_script)()
local function RTIQU_fake_script() -- Button3_9.METAB SCRIPT 
	local script = Instance.new('LocalScript', Button3_9)

	script.Parent.MouseButton1Down:connect(function()
	
	
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-41.137184143066, 118.86273193359, 253.73468017578)
	
	end)
	
	
	
	
	
	
end
coroutine.wrap(RTIQU_fake_script)()
local function TUNYXC_fake_script() -- ImageButton.LocalScript 
	local script = Instance.new('LocalScript', ImageButton)

	script.Parent.MouseButton1Click:connect(function()
		script.Parent.Parent.ImageLabel.Visible = not script.Parent.Parent.ImageLabel.Visible
	end)
	
end
coroutine.wrap(TUNYXC_fake_script)()
