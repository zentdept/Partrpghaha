--เอาไว้ใช้กับ_G.AutoFarm เช่น _G.PartRgbก็เปลี่ยนAutoFarmให้กลายเป็นPartRgb





spawn(function()
	game:GetService("RunService").Heartbeat:Connect(function()
		if _G.AutoFarm then
			if not game:GetService("Workspace"):FindFirstChild("LOL") then
				local LOL = Instance.new("Part")
				LOL.Name = "LOL"
				LOL.Parent = game.Workspace
				LOL.Anchored = true
				LOL.Transparency = 0
				LOL.Size = Vector3.new(20,-0.5,20)
				LOL.Material = "Neon"
			elseif game:GetService("Workspace"):FindFirstChild("LOL") then
				game.Workspace["LOL"].CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,-3.5,0)
			end
		else
			if game:GetService("Workspace"):FindFirstChild("LOL") then
				game:GetService("Workspace"):FindFirstChild("LOL"):Destroy()
			end
		end
	end)
end)


spawn(function()
    while wait() do
        if game.Workspace:FindFirstChild("LOL") then
            game.Workspace:FindFirstChild("LOL").Color = Color3.new(255/255,0/255,0/255)
            for i = 0,255,10 do
                wait(.1)
                if game.Workspace:FindFirstChild("LOL") then
                    game.Workspace:FindFirstChild("LOL").Color = Color3.new(255/255,i/255,0/255)
                end
            end
            for i = 255,0,-10 do
                wait(.1)
                if game.Workspace:FindFirstChild("LOL") then
                    game.Workspace:FindFirstChild("LOL").Color = Color3.new(i/255,255/255,0/255)
                end
            end
            for i = 0,255,10 do
                wait(.1)
                if game.Workspace:FindFirstChild("LOL") then
                    game.Workspace:FindFirstChild("LOL").Color = Color3.new(0/255,255/255,i/255)
                end
            end
            for i = 255,0,-10 do
                wait(.1)
                if game.Workspace:FindFirstChild("LOL") then
                    game.Workspace:FindFirstChild("LOL").Color = Color3.new(0/255,i/255,255/255)
                end
            end
            for i = 0,255,10 do
                wait(.1)
                if game.Workspace:FindFirstChild("LOL") then
                    game.Workspace:FindFirstChild("LOL").Color = Color3.new(i/255,0/255,255/255)
                end
            end
            for i = 255,0,-10 do
                wait(.1)
                if game.Workspace:FindFirstChild("LOL") then
                    game.Workspace:FindFirstChild("LOL").Color = Color3.new(255/255,0/255,i/255)
                end
            end
        end
    end
end)
