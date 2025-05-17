local OrionLib = loadstring(game:HttpGet(('https://pastebin.com/raw/WRUyYTdY')))()


local Window = OrionLib:MakeWindow({
    Name = "KAMUI X V0.1",
    HidePremium = false,
    SaveConfig = true,
    ConfigFolder = "Name" -- Put the name of your hub or script here!
})

print("Successfully executed.") -- Just a debug

local Tab = Window:MakeTab({
    Name = "Info",
    Icon = "rbxassetid://1",
    PremiumOnly = false
})

local Section = Tab:AddSection({
    Name = "Info"
})

local Section = Tab:AddSection({
    Name = "troll"
})

local playerName = game.Players.LocalPlayer.Name

Tab:AddButton({
    Name = "BEM VINDO.. playerName .. "! This is the best hub!",
    Callback = function()
    end
})

Tab:AddButton({
    Name = "Check out our official discord server in your clipboard.",
    Callback = function()
        setclipboard("https://discord.gg/r7A3c5YRDC")
        toclipboard("https://discord.gg/r7A3c5YRDC")
  end    
})

Tab:AddButton({
    Name = "Infinite Yield",
    Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
  end    
})


Tab:AddButton({
    Name = "Mao de deus",
    Callback = function()
  local args = {
    [1] = "God's Hand"
}

game:GetService("ReplicatedStorage").EquipSlapEvent:FireServer(unpack(args))
      


Tab:AddButton({
    Name = "audio fe",
    Callback = function()
        loadstring(jogo:HttpGet("https://raw.githubusercontent.com/ameicaa1/brookhaven-script/main/brookhaven%20script.lua")) ()"))()
  end    
})
