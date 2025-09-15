local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "Kat_funpay",
   Icon = 0, --
   LoadingTitle = "@Abvgdeqfe",
   LoadingSubtitle = "by skexx😁🥰",
   ShowText = "Rayfield",
   Theme = "Dark",

   ToggleUIKeybind = "Q", -- 
   DisableRayfieldPrompts = false,
   DisableBuildWarnings = false, 

   ConfigurationSaving = {
      Enabled = true,
      FolderName = KAT,
      FileName = "Kat Hub"
   },

   Discord = {
      Enabled = true, 
      Invite = "noinvitelink", -- 
      RememberJoins = true 
   },

   KeySystem = true, 
   KeySettings = {
      Title = "kat system",
      Subtitle = "KEY SYSTEM",
      Note = "key is free777",
      FileName = "Key", 
      SaveKey = true,
      GrabKeyFromSite = false,
      Key = {"free777"}
   }
})

Rayfield:Notify({
   Title = "Notification",
   Content = "Build 1.40",
   Duration = 6.5,
   Image = 4483362458,
})

local Tab = Window:CreateTab("Scripts", 4483362458)
local Section = Tab:CreateSection("scripts")
local Button = Tab:CreateButton({
   Name = "Rivals",
   Callback = function()
   loadstring(game:HttpGet(('https://raw.githubusercontent.com/VisioneducationOfLuaCoding/Ambrion/refs/heads/main/RivalsVersion3'),true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "MM2",
   Callback = function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/OnyxHub-New/OnyxHub/refs/heads/main/mm2'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Grow a garden",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/Kenniel123/Grow-a-garden/refs/heads/main/Grow%20A%20Garden"))("t.me/Cherruscript")
   end,
})

local Button = Tab:CreateButton({
   Name = "99 night in the forest farm diamonds",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/Rx1m/CpsHub/refs/heads/main/Cpsnerfv2"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "99 night in the forest",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/VapeVoidware/VW-Add/main/nightsintheforest.lua", true))()
   end,
})


local Button = Tab:CreateButton({
   Name = "Fling things and people",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/NameHubScript/_/refs/heads/main/f"))("t.me/Cherruscript")
   end,
})

local Button = Tab:CreateButton({
   Name = "INK GAME",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/wefwef127382/inkgames.github.io/refs/heads/main/ringta.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "DOORS",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/Iliankytb/Iliankytb/main/NewBestDoorsScriptIliankytb"))("t.me/KolerotScripts")
   end,
})

local Button = Tab:CreateButton({
   Name = "Rivals 2.0",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/blackowl1231/Z3US/refs/heads/main/main.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Forsaken",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/fuckg1thub/NeptX/refs/heads/main/NeptZ/Forsaken/source.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "murder vs sheriff (good anti cheat)",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/TheRealAvrwm/Projects/main/Xeno%20MVSD%20script.lua", true))() 
   end,
})

local Button = Tab:CreateButton({
   Name = "Steal a braimrot (Makal Hub)",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/DoliScriptz/MakalHub/refs/heads/main/loader.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Bee Swarm (good scriptw)",
   Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Yomkaa/YOXI-HUB/refs/heads/main/loader",true))() 
   end,
})

local Button = Tab:CreateButton({
   Name = "Button Example",
   Callback = function()
   
   end,
})

local Tab = Window:CreateTab("Simple Scripts", 4483362458)

local Button = Tab:CreateButton({
   Name = "infinity yield",
   Callback = function()
   loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
   end,
})

local Tab = Window:CreateTab("Information", 4483362458)

local Section = Tab:CreateSection("😎")

local Paragraph = Tab:CreateParagraph({Title = "Hi", Content = "Build 1.40 next update idk this script can kick you for using cheats, so be careful"})

Rayfield:LoadConfiguration()
