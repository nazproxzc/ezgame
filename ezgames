local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "Huy Pro",
   LoadingTitle = "Huy Pro",
   LoadingSubtitle = "by Huy_Pro",
   ConfigurationSaving = {
      Enabled = false,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Example Hub"
   },
   Discord = {
      Enabled = false,
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },
})

local TPTab = Window:CreateTab("Farm", nil) -- Title, Image

local Button1 = TPTab:CreateButton({
   Name = "Collector Cash",
   Callback = function()
    local args = {
    [1] = 999999999999999999
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("UpdateAltStat"):FireServer(unpack(args))

})
