local ReplicatedStorage = game:GetService("ReplicatedStorage")
local GiveSpins = ReplicatedStorage:WaitForChild("GiveSpins")

-- Botão de girar
local button = script.Parent:WaitForChild("SpinButton")

button.MouseButton1Click:Connect(function()
	GiveSpins:FireServer()
end)
