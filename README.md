--Don't Fucking Skid It
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("VoidScripts", "Sentinel")

local AutoFarm= Window:NewTab("AutoFarm")
local AutoFarm = AutoFarm:NewSection("AutoFarm")

AutoFarm:NewToggle("AutoMine", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.Click:InvokeServer()
         end
    else
game:GetService("ReplicatedStorage").Remotes.Click:InvokeServer()
    end
end)

AutoFarm:NewToggle("AutoRebirth", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.Rebirth:FireServer()
         end
    else
game:GetService("ReplicatedStorage").Remotes.Rebirth:FireServer()
    end
end)


local Upgrades= Window:NewTab("Upgrades")
local Upgrades = Upgrades:NewSection("Upgrades")

Upgrades:NewToggle("Auto Ore Pay", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.upgradePlr:FireServer("Ore Pay")
         end
    else
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.upgradePlr:FireServer("")
         end
    end
end)

Upgrades:NewToggle("Pet Space", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.upgradePlr:FireServer("Pet Storage")
         end
    else
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.upgradePlr:FireServer("")
         end
    end
end)

Upgrades:NewToggle("Walkspeed", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.upgradePlr:FireServer("Player Speed")
         end
    else
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.upgradePlr:FireServer("")
         end
    end
end)

Upgrades:NewToggle("AutoClicker", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.upgradePlr:FireServer("Auto Click Speed")
         end
    else
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.upgradePlr:FireServer("")
         end
    end
end)

Upgrades:NewToggle("Pets Equipped", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.upgradePlr:FireServer("Pets Equipped")
         end
    else
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.upgradePlr:FireServer("")
         end
    end
end)

Upgrades:NewToggle("Drill Speed", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.upgradePlr:FireServer("Drill Speed")
         end
    else
game:GetService("ReplicatedStorage").Remotes.upgradePlr:FireServer("")
    end
end)

local AutoEgg= Window:NewTab("AutoEgg")
local AutoEgg = AutoEgg:NewSection("AutoEgg")

AutoEgg:NewButton("To Turn It Off you must leave", "ButtonInfo", function()
    print("Clicked")
end)

AutoEgg:NewToggle("Starter Egg 1x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Starter Egg",1)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Starter Egg",1)
    end
end)

AutoEgg:NewToggle("Starter Egg 3x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Starter Egg",2)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Starter Egg",1)
    end
end)

AutoEgg:NewToggle("Spotted Egg 1x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Spotted Egg",1)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Spotted Egg",1)
    end
end)

AutoEgg:NewToggle("Spotted Egg 3x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Spotted Egg",2)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Spotted Egg",1)
    end
end)


AutoEgg:NewToggle("Flower Egg 1x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Floral Egg",1)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Floral Egg",1)
    end
end)

AutoEgg:NewToggle("Flower Egg 3x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Floral Egg",2)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Floral Egg",1)
    end
end)

AutoEgg:NewToggle("Desert Egg 1x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Desert Egg",1)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Desert Egg",1)
    end
end)

AutoEgg:NewToggle("Desert Egg 3x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Desert Egg",2)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Desert Egg",1)
    end
end)

AutoEgg:NewToggle("Snow Egg 1x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Snow Egg",1)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Snow Egg",1)
    end
end)


AutoEgg:NewToggle("Snow Egg 3x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Snow Egg",2)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Snow Egg",1)
    end
end)


AutoEgg:NewToggle("Cave Egg 1x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Cave Egg",1)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Cave Egg",1)
    end
end)

AutoEgg:NewToggle("Cave Egg 3x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Cave Egg",2)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Cave Egg",1)
    end
end)



AutoEgg:NewToggle("Ocean Egg 1x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Ocean Egg",1)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Ocean Egg",1)
    end
end)


AutoEgg:NewToggle("Ocean Egg 3x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Ocean Egg",2)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Ocean Egg",1)
    end
end)


AutoEgg:NewToggle("Jungle Egg 1x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Jungle Egg",1)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Jungle Egg",1)
    end
end)

AutoEgg:NewToggle("Jungle Egg 3x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Jungle Egg",2)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Jungle Egg",1)
    end
end)

AutoEgg:NewToggle("Volcano Egg 1x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Volcano Egg",1)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Volcano Egg",1)
    end
end)


AutoEgg:NewToggle("Volcano Egg 3x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Volcano Egg",2)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Volcano Egg",1)
    end
end)


AutoEgg:NewToggle("Space Egg 1x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Space Egg",1)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Space Egg",1)
    end
end)


AutoEgg:NewToggle("Space Egg 3x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Space Egg",2)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Space Egg",1)
    end
end)


AutoEgg:NewToggle("Undead Egg 1x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Undead Egg",1)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Undead Egg",1)
    end
end)


AutoEgg:NewToggle("Undead Egg 3x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Undead Egg",2)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Undead Egg",1)
    end
end)


AutoEgg:NewToggle("Heavenly Egg 1x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Heavenly Egg",1)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Undead Egg",1)
    end
end)


AutoEgg:NewToggle("Heavenly Egg 3x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Heavenly Egg",2)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Heavenly Egg",1)
    end
end)


AutoEgg:NewToggle("Devil Egg 1x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Devil Egg",1)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Devil Egg",1)
    end
end)


AutoEgg:NewToggle("Devil Egg 3x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Devil Egg",2)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Devil Egg",1)
    end
end)


AutoEgg:NewToggle("Fossil Egg 1x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Fossil Egg",1)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Fossil Egg",1)
    end
end)

AutoEgg:NewToggle("Fossil Egg 3x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Fossil Egg",2)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Fossil Egg",1)
    end
end)


AutoEgg:NewToggle("Tentacle Egg 1x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Fossil Egg",1)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Fossil Egg",1)
    end
end)


AutoEgg:NewToggle("Tentacle Egg 3x", "ToggleInfo", function(state)
    if state then
        while wait() do
            game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Fossil Egg",2)
         end
    else
game:GetService("ReplicatedStorage").Remotes.buyEgg:InvokeServer("Fossil Egg",1)
    end
end)



local Misc = Window:NewTab("Misc")
local Misc = Misc:NewSection("Misc")

Misc:NewSlider("WalkSpeed", "SliderInfo", 500, 16, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

local Credits = Window:NewTab("Credits")
local Credits = Credits:NewSection("Credits")

Credits:NewButton("ツ឵឵#0498", "ButtonInfo", function()
    print("Clicked")
end)

Credits:NewButton("Join The Discord", "Click F9 To see te discord link", function()
    print("9DpVAEWdYH")
end)


