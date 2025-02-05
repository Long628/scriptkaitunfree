-- Max level, godhuman, cdk, sgt
getgenv().Shutdown = false -- Turn on if u are farming bulk accounts
getgenv().Configs = {
    ["Team"] = "Marines",
    ["Gun Farm"] = false, -- Disabled
    ["FPS Boost"] = {
        ["Enable"] = false,
        ["FPS Cap"] = 30,
    },
    ["Farm Boss Drops"] = {
        ["Enable"] = false,
        ["When x2 Exp Expired"] = false
    },
    ["Awaken Fruit"] = true,
    ["Rainbow Haki"] = true,
    ["Hop Player Near"] = true,
    ["Skull Guitar"] = true,
    ["Find Fruit"] = false, -- Will find 1m+ fruit to unlock swan door to access third sea
    ["Cursed Dual Katana"] = true,
    ["Switch Melee"] = true,
    ["Eat Fruit"] = "", -- leave blank for none, put the fruit name like this example: Smoke Fruit, T-Rex Fruit, ...
    ["Snipe Fruit"] = "", -- leave blank for none, put the fruit name like this example: Smoke Fruit, T-Rex Fruit, ...
    ["Lock Fragment"] = 0,
    ["Buy Stuffs"] = true -- buso, geppo, soru, ken haki
}
repeat task.wait() pcall(function() loadstring(game:HttpGet("https://raw.githubusercontent.com/verudous/Xero-Hub/refs/heads/main/kaitun.lua"))() end) until getgenv().Check_Execute
