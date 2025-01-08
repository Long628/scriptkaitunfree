-- Max level, godhuman, cdk, sgt
getgenv().Shutdown = true -- shutdown server it fail hop
getgenv().Configs = {
    ["Team"] = "Marines",
    ["Gun Farm"] = false, -- Disabled
    ["FPS Boost"] = {
        ["Enable"] = true,
        ["FPS Cap"] = 60,
    },
    ["Farm Boss Drops"] = {
        ["Enable"] = false,
        ["When x2 Exp Expired"] = false
    },
    ["Auto Evo Race"] = false,
    ["Awaken Fruit"] = false,
    ["Rainbow Haki"] = true,
    ["Hop Player Near"] = true,
    ["Skull Guitar"] = false,
    ["Find Fruit"] = true, -- Will find 1m+ fruit to unlock swan door to access third sea
    ["Cursed Dual Katana"] = true,
    ["Switch Melee"] = true,
    ["Eat Fruit"] = "", -- leave blank for none, put the fruit name like this example: Smoke Fruit, T-Rex Fruit, ...
    ["Snipe Fruit"] = "", -- leave blank for none, put the fruit name like this example: Smoke Fruit, T-Rex Fruit, ...
    ["Lock Fragment"] = 0,
    ["Buy Stuffs"] = true -- buso, geppo, soru, ken haki
}
repeat task.wait() pcall(function() loadstring(game:HttpGet("https://reviewphim.fun/Xero%20Hub/Blox%20Fruit/kaitun.lua"))() end) until getgenv().Check_Execute
