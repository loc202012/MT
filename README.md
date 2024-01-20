getgenv().Config = {
    ["Team"] = "Pirates", --// Marines, Pirates
    ["Webhook"] = {
        ["Enable"] = true, --// Enable if you have Webhook Url
        ["Url"] = "" --// Your webhook url
    },
    ["Skip"] = {
        ["V4"] = false, --// Skip V4
        ["Fruit"] = { --// Skip Fruit
            "Buddha-Buddha",
            "Portal-Portal"
        }
    },
    ["Chat"] = {
        ["Enable"] = true, --// Enable Chat
        ["Content"] = {"Hello Everyone I'm AfxcaxiRoblox", "Config By AfxcaxiRoblox} --// Content
    },
    ["Misc"] = {
        ["Hide If Low Health"] = true, --// Run
        ["Hide Health"] = {4000,5000}, --// Health for run
        ["Lock Camera"] = true, --// Lock Cam to target
        ["FPS Boost"] = true, --// Booster FPS
        ["White Screen"] = true, --// White Screen
        ["Bypass TP"] = true, --// Bypass TP 1 -> 2 hit
        ["Spam All Skill On V4"] = true, --// If you have v4, warn: change your weapon setting
        ["Gun Method"] = false --// Enable if you use gun
    },
    --// Copy Next
    ["Weapons"] = {
        ["Melee"] = {
            ["Enable"] = true,
            ["Delay"] = 2.5,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true, ["HoldTime"] = 0.1},
                ["X"] = {["Enable"] = true, ["HoldTime"] = 0.2},
                ["C"] = {["Enable"] = true, ["HoldTime"] = 0.7},
                ["V"] = {["Enable"] = false, ["HoldTime"] = 0}
            }
        },
        ["Blox Fruit"] = {
            ["Enable"] = true,
            ["Delay"] = 3,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true, ["HoldTime"] = 4},
                ["X"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["C"] = {["Enable"] = true, ["HoldTime"] = 0.2},
                ["V"] = {["Enable"] = false, ["HoldTime"] = 0.2},
                ["F"] = {["Enable"] = false, ["HoldTime"] = 0}
            }
        },
        --// Copy Next
        ["Sword"] = {
            ["Enable"] = false,
            ["Delay"] = 1.5,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true, ["HoldTime"] = 0.1},
                ["X"] = {["Enable"] = true, ["HoldTime"] = 1}
            } 
        },      
        ["Gun"] = {
            ["Enable"] = false,
            ["Delay"] = 1.2,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true, ["HoldTime"] = 0.1},
                ["X"] = {["Enable"] = true, ["HoldTime"] = 1}
            } 
        }
    }
}
repeat wait() until game:IsLoaded()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Minhtriettt/Hunt/main/AutoBountyV2.lua"))()
