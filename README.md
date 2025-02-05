getgenv().simple_settings = {
["MASTERY"] = { -- Settings related to leveling up weapon or skill mastery
["ACTIVE"] = true, -- Enable or disable mastery leveling (true = enabled, false = disabled)
["METHOD"] = "Half", -- Method for gaining mastery, "Half"[300] or "Full"[600]
},
["OBJECTIVE"] = { -- Goals for farming and unlocking features
["GODHUMAN"] = true, -- Automatically unlock the "Godhuman" fighting style
["RACE-V3"] = true, -- Automatically upgrade character race to V3 if possible Human, Mink, (Fishman, Ghoul, Cyborg) soon
["FRAGMENT"] = 100000, -- Limit number of fragments to collect
-- SWORD
["CANVANDER"] = true,
["BUDDY-SWORD"] = true,
["CURSED-DUAL-KATANA"] = true,
["SHARK-ANCHOR"] = true, -- soon..
--GUN
["ACIDUM-RIFLE"] = true,
["VENOM-BOW"] = true,
["SOUL-GUITAR"] = true,
},
["FRUITPURCHASE"] = true, -- Automatically purchase fruits based on priority list
["PRIORITYFRUIT"] = { -- List of preferred fruits to purchase or eat in order of priority
[1] = "Dragon-Dragon",
[2] = "Flame-Flame",
[3] = "Rumble-Rumble",
[4] = "Human-Human: Buddha",
[5] = "Dark-Dark",
},
["FPSCAP"] = 30, -- Limit the frame rate to optimize performance
["LOWTEXTURE"] = true -- Reduce graphic quality for better performance
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/simple-hubs/contents/refs/heads/main/bloxfruit-kaitan-main.lua"))()
