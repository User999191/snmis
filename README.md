local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Weird Sus Grandma", HidePremium = false, SaveConfig = true, ConfigFolder = "☠️☠️☠️☠️☠️"})
local Tab = Window:MakeTab({
	Name = "Tp",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Bedroom",
	Callback = function()
      		print("button pressed")
	     game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0.602097094, 20.137886, 444.596985, -0.896335006, -1.05235117e-07, 0.443377465, -9.92332403e-08, 1, 3.67382178e-08, -0.443377465, -1.10680327e-08, -0.896335006)
	end    
})

Tab:AddButton({
	Name = "Kitchen",
	Callback = function()
      		print("button pressed")
	   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-21.8640194, 7.05120325, 351.97879, 0.0314038135, 5.40575833e-08, 0.999506831, -3.80795839e-08, 1, -5.28878239e-08, -0.999506831, -3.63999213e-08, 0.0314038135)
  	end    
})
Tab:AddButton({
	Name = "Generation",
	Callback = function()
      		print("button pressed")
	   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(16.3540058, 7.05120182, 404.920929, -0.19164823, -4.67164369e-08, 0.981463671, -3.17791873e-08, 1, 4.13932888e-08, -0.981463671, -2.32571669e-08, -0.19164823)
  	end    
   })

   Tab:AddButton({
	Name = "Go Out Side!!!",
	Callback = function()
      		print("button pressed")
	   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(95.0161209, 6.96599865, 341.283539, -0.070768714, 1.54773439e-08, 0.997492731, 3.40369191e-08, 1, -1.31014435e-08, -0.997492731, 3.30244099e-08, -0.070768714)
  	end    
})

   local Tab = Window:MakeTab({
	Name = "Player",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "37 speed",
	Callback = function()
      		print("button pressed")
	  humanoid.walkspeed = 37
  	end    
})
