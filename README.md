local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Weird Sus Grandma", HidePremium = false, SaveConfig = true, ConfigFolder = "☠️☠️☠️☠️☠️"})
local Tab = Window:MakeTab({
	Name = "Tp",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Button!",
	Callback = function()
      		print("button pressed")
	     game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0.602097094, 20.137886, 444.596985, -0.896335006, -1.05235117e-07, 0.443377465, -9.92332403e-08, 1, 3.67382178e-08, -0.443377465, -1.10680327e-08, -0.896335006)
	end    
})

