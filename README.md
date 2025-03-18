local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TitleLabel = Instance.new("TextLabel")
local Button1 = Instance.new("TextButton")
local Button2 = Instance.new("TextButton")
local Button3 = Instance.new("TextButton")
local Button4 = Instance.new("TextButton")
local Button5 = Instance.new("TextButton")

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.Position = UDim2.new(0.25, 0, 0.25, 0)
Frame.Size = UDim2.new(0.5, 0, 0.5, 0)

TitleLabel.Parent = Frame
TitleLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TitleLabel.Size = UDim2.new(1, 0, 0.1, 0)
TitleLabel.Text = "Brookhaven Features"
TitleLabel.TextScaled = true

Button1.Parent = Frame
Button1.BackgroundColor3 = Color3.fromRGB(0, 170, 0)
Button1.Position = UDim2.new(0.1, 0, 0.2, 0)
Button1.Size = UDim2.new(0.8, 0, 0.1, 0)
Button1.Text = "Feature 1"
Button1.MouseButton1Click:Connect(function()
    -- Add functionality for Feature 1
end)

Button2.Parent = Frame
Button2.BackgroundColor3 = Color3.fromRGB(0, 170, 0)
Button2.Position = UDim2.new(0.1, 0, 0.35, 0)
Button2.Size = UDim2.new(0.8, 0, 0.1, 0)
Button2.Text = "Feature 2"
Button2.MouseButton1Click:Connect(function()
    -- Add functionality for Feature 2
end)

Button3.Parent = Frame
Button3.BackgroundColor3 = Color3.fromRGB(0, 170, 0)
Button3.Position = UDim2.new(0.1, 0, 0.5, 0)
Button3.Size = UDim2.new(0.8, 0, 0.1, 0)
Button3.Text = "Feature 3"
Button3.MouseButton1Click:Connect(function()
    -- Add functionality for Feature 3
end)

Button4.Parent = Frame
Button4.BackgroundColor3 = Color3.fromRGB(0, 170, 0)
Button4.Position = UDim2.new(0.1, 0, 0.65, 0)
Button4.Size = UDim2.new(0.8, 0, 0.1, 0)
Button4.Text = "Feature 4"
Button4.MouseButton1Click:Connect(function()
    -- Add functionality for Feature 4
end)

Button5.Parent = Frame
Button5.BackgroundColor3 = Color3.fromRGB(0, 170, 0)
Button5.Position = UDim2.new(0.1, 0, 0.8, 0)
Button5.Size = UDim2.new(0.8, 0, 0.1, 0)
Button5.Text = "Feature 5"
Button5.MouseButton1Click:Connect(function()
    -- Add functionality for Feature 5
end)
.
