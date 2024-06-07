getgenv().SpamSkill = false
getgenv().AutoUseRaceV3 = true
getgenv().AutoUseRacev4 = true
getgenv().SpamSkillOnRaceV4 = false
getgenv().Invisible = true
getgenv().InCombatNoReset = true
getgenv().Team = "Marines" -- Marines
getgenv().TweenSpeed = 350 -- 350 max or Get Tp Back
 getgenv().Setting = { -- Select Weapon, Self Explain
        ["Melee"] = {["Enable"] = true,["Delay"] = 2,
          ["Skills"] = {
            ["Z"] = {["Enable"] = true,["HoldTime"] = 0.75,["TimeToNextSkill"] = 0,},
            [ "X"] = {["Enable"] = true,["HoldTime"] = 0, ["TimeToNextSkill"] = 0,},
            ["C"] = {["Enable"] = true,["HoldTime"] = 0, ["TimeToNextSkill"] = 0,},
            },
        },
        ["Blox Fruit"] = {["Enable"] = false, ["Delay"] = 1.25,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true, ["HoldTime"] = 1, ["TimeToNextSkill"] = 0,},
                ["X"] = { ["Enable"] = true, ["HoldTime"] = 0, ["TimeToNextSkill"] = 0,},
                ["C"] = { ["Enable"] = true, ["HoldTime"] = 0,["TimeToNextSkill"] = 0, },
                ["V"] = { ["Enable"] = true, ["HoldTime"] = 0,["TimeToNextSkill"] = 0,},
                ["F"] = {["Enable"] = true,["HoldTime"] = 0, ["TimeToNextSkill"] = 0,},
            },
        },
        ["Sword"] = { ["Enable"] = true, ["Delay"] = 0.7,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true,  ["HoldTime"] = 0.3,["TimeToNextSkill"] = 0,},
                ["X"] = {["Enable"] = true, ["HoldTime"] = 0, ["TimeToNextSkill"] = 0,},
            },
        },
        ["Gun"] = {["Enable"] = true, ["Delay"] = 0.7,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true,["HoldTime"] = 0,["TimeToNextSkill"] = 0,},
                ["X"] = {["Enable"] = true,["HoldTime"] = 0,["TimeToNextSkill"] = 0,
                },
            },
        }
    }
 loadstring(game:HttpGet('https://raw.githubusercontent.com/vinhuchi/temp-repos/main/FreeAutoBounty.lua'))()
