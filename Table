getgenv().Blizzard = {
    Luarmor = { Key = "" },

    Startup = { 
        Hash = 0xAB0, 
        Intro = false, -- Removed Cause of Solara
        Delay = 0.5
    },
    --
    Logic = {
        ['Panic'] = { false, "I" },
        ['Hide Visuals'] = { false, "E" },
        ['Threads'] = {
            ['Main'] = "RenderStepped",
            ['Other'] = "RenderStepped"
        }
    }, --
    ["Resolver"] = { 
        ['Enabled'] = true, -- regular resolver detection
        ['Force'] = false,  -- if u always want the resolver on
        ['On Key'] = { true, "V"}, -- if u want to turn the resolver on with a key (manually)
        ['Show Force Label'] = { true, Color3.fromRGB(214, 184, 184) } -- shows if the resolver is on with on key
    },
    -- 
    ['Universal'] = {
        ["Enabled"] = false,  
        ["TeamCheck"] = false,
        ["Predict"] = true,
        ["HitChance"] = 300,
        ["Prediction"] = { 0.05, 0.11, 0.06 }, --[[ X, Y, Z ]]--
        ["AimBone"] = {"Head", "Torso", "Stomach"}, --[[ Head, Torso, Stomach ]]
        ["UseNearestAimBone"] = true,
        ["Box"] = { 
            ["Enabled"] = true, 
            ["Color"] = Color3.fromRGB(220, 198, 198),
            ["Size"] = { 
                ["X"] = 3, 
                ["Y"] = 4
            }, 
        },
        ["Chams"] = { 
            ["Enabled"] = false, 
            ["Color"] = Color3.fromRGB(181, 209, 228), 
            ["Outline"] = Color3.fromRGB(0, 0, 0), 
            ["Transparency"] = 0.1
        }
    },
    --
    ["Silent Aim"] = {
        ['Enabled'] = { true, ['Toggle Key'] = { false, "V"} },
        ['Sticky Mode'] = false,
        ['Target Mode'] = "FOV", -- Target, FOV
        ['Silent Mode'] = "Safe", -- Safe, Aggressive
        ['Target Sync'] = false, -- having this on will make your silent aim target your aimbot target if you're on target mode
        ['Target Bind'] = "Z",
        ['Hit Mode'] = "Circle", -- Circle, Box
        ['HitChance'] = 300,
        ['AntiFloor'] = false,
        ['HitParts'] = {
            ['Hit Type'] = " Nearest Point", -- Nearest Point, Nearest Part, Blank for hitbones
            ['Nearest Point Type'] = "Partial", -- Scalar, Generic, Absolute, Partial
            ['HitBones'] = {"HumanoidRootPart"},
            ['Scaling'] = {
                ['Min'] = 2.5,
                ['Max'] = 2.5,
            }
        },
        ['Anti Curve'] = {
            ['Enabled'] = false,
            ['Mode'] = "3D", -- 2D, 3D
            ['Angular Curve'] = 9.6,
        },
        ['Prediction'] = {
            ['Automatic'] = true,
            ['Ping Based'] = true,
            ['Velocity Type'] = "Regular", -- Regular, Linear, Rot, Angular
            --
            ['Prediction'] = { 0.4225, 0.4225, 0.4225 },
            --
            ['Ping Ranges'] = {
                ["20 - 30"] = { 0.11120, 0.11120, 0.11120 }, --[[ X,  Y,  Z ]]--
                ["30 - 40"] = { 0.11614, 0.11614, 0.11614 }, --[[ X,  Y,  Z ]]--
                ["40 - 50"] = { 0.12053, 0.12053, 0.12053 }, --[[ X,  Y,  Z ]]--
                ["50 - 60"] = { 0.12053, 0.12053, 0.12053 }, --[[ X,  Y,  Z ]]--
                ["60 - 70"] = { 0.12790, 0.12790, 0.12790 }, --[[ X,  Y,  Z ]]--
                ["70 - 80"] = { 0.12793, 0.12793, 0.12793 }, --[[ X,  Y,  Z ]]--
                ["80 - 90"] = { 0.129591, 0.129591, 0.129591 }, --[[ X,  Y,  Z ]]--
                ["90 - 100"] = { 0.13070, 0.13070, 0.13070 }, --[[ X,  Y,  Z ]]--
                ["100 - 110"] = { 0.13916, 0.13916, 0.13916 }, --[[ X,  Y,  Z ]]--
                ["110 - 120"] = { 0.14664, 0.14664, 0.14664 }, --[[ X,  Y,  Z ]]--
                ["120 - 130"] = { 0.14745, 0.14745, 0.14745 }, --[[ X,  Y,  Z ]]--
                ["130 - 140"] = { 0.150, 0.150, 0.150 }, --[[ X,  Y,  Z ]]--
                ["140 - 150"] = { 0.155, 0.155, 0.155 }, --[[ X,  Y,  Z ]]--
                ["150 - 160"] = { 0.1545, 0.1545, 0.1545 }, --[[ X,  Y,  Z ]]--
                ["160 - 170"] = { 0.1567, 0.1567, 0.1567 }, --[[ X,  Y,  Z ]]--
                ["170 - 180"] = { 0.1672, 0.1672, 0.1672 }, --[[ X,  Y,  Z ]]--
                ["180 - 190"] = { 0.1746, 0.1746, 0.1746 }, --[[ X,  Y,  Z ]]--
                ["190 - 200"] = { 0.1746, 0.1746, 0.1746 }, --[[ X,  Y,  Z ]]--
            }
        },
        ['Drawings'] = {
            ['Field Of View'] = {
                ['Visible'] = false,
                ['Radius'] = 140,
                ['Filled'] = false,
                ['Thickness'] = 1,
                ['Transparency'] = 0.25,
                ['Color'] = Color3.fromRGB(255, 0, 0)
            },
            ['Box Field Of View'] = {
                ['Visible'] = false,
                ['Prediction'] = false,
                ['Radius'] = {
                    ['Width'] = 1, 
                    ['Height'] = 2
                },
                ['Thickness'] = 3,
                ['Transparency'] = 1,
                ['Color'] = Color3.fromRGB(214, 205, 205),
                ['Focused Color'] = Color3.fromRGB(140, 164, 201),
            },
            ['Tracer'] = { -- only works with box fov
                ['Visible'] = false,
                ['Thickness'] = 1,
                ['Transparency'] = 1,
                ['Color'] = Color3.fromRGB(140, 164, 201)
            },
        },
        ['Conditions'] = {
            ['Wall'] = true,
            ['Friend'] = false,
            ['Knocked'] = true,
            ['Grabbed'] = true,
            ['Forcefield'] = true,
            ['Chat Focused'] = false,
            ['Tool Equipped'] = false,
        }
    },
    --
    ["Aimbot"] = {
        ['Enabled'] = { true, ['Toggle Key'] = { false, "J"} },
        ['Sticky Mode'] = true,
        ['Keybind'] = "C",
        ['Deadzone'] = false,
        ["AntiFloor"] = true,
        ['MouseHold'] = {
            ['Enabled'] = false,
            ['Keybind'] = "MouseButton2" -- HOLD ONLY
        },
        ['Smoothness'] = {
            ['X'] = 4,
            ['Y'] = 5,
            ["StickynessX"] = 1,
            ["StickynessY"] = 1,
        },
        ['Readjustment'] = {
            ['Enabled'] = false,
            ['Readjustment'] = { 8, 11, 11 }
        },
        ['HitParts'] = {
            ['HitBones'] = {"HumanoidRootPart"},
            ['Scaling'] = { 
                ['Min'] = 2.5,
                ['Max'] = 2.5,
            }
        }, 
        ['Prediction'] = {
            ['Enabled'] = true,
            ['Automatic'] = true,
            ['Ping Based'] = false,
            ['Velocity Type'] = "Regular", -- Regular, Linear, Rot, Angular
            --
            ['Prediction'] =  { 0.4225, 0.4225, 0.4225 },
            --
            ['Ping Ranges'] = {
                ["20 - 30"] = { 0.11120, 0.11120, 0.11120 }, --[[ X,  Y,  Z ]]--
                ["30 - 40"] = { 0.11614, 0.11614, 0.11614 }, --[[ X,  Y,  Z ]]--
                ["40 - 50"] = { 0.12053, 0.12053, 0.12053 }, --[[ X,  Y,  Z ]]--
                ["50 - 60"] = { 0.12053, 0.12053, 0.12053 }, --[[ X,  Y,  Z ]]--
                ["60 - 70"] = { 0.12790, 0.12790, 0.12790 }, --[[ X,  Y,  Z ]]--
                ["70 - 80"] = { 0.12793, 0.12793, 0.12793 }, --[[ X,  Y,  Z ]]--
                ["80 - 90"] = { 0.129591, 0.129591, 0.129591 }, --[[ X,  Y,  Z ]]--
                ["90 - 100"] = { 0.13070, 0.13070, 0.13070 }, --[[ X,  Y,  Z ]]--
                ["100 - 110"] = { 0.13916, 0.13916, 0.13916 }, --[[ X,  Y,  Z ]]--
                ["110 - 120"] = { 0.14664, 0.14664, 0.14664 }, --[[ X,  Y,  Z ]]--
                ["120 - 130"] = { 0.14745, 0.14745, 0.14745 }, --[[ X,  Y,  Z ]]--
                ["130 - 140"] = { 0.150, 0.150, 0.150 }, --[[ X,  Y,  Z ]]--
                ["140 - 150"] = { 0.155, 0.155, 0.155 }, --[[ X,  Y,  Z ]]--
                ["150 - 160"] = { 0.1545, 0.1545, 0.1545 }, --[[ X,  Y,  Z ]]--
                ["160 - 170"] = { 0.1567, 0.1567, 0.1567 }, --[[ X,  Y,  Z ]]--
                ["170 - 180"] = { 0.1672, 0.1672, 0.1672 }, --[[ X,  Y,  Z ]]--
                ["180 - 190"] = { 0.1746, 0.1746, 0.1746 }, --[[ X,  Y,  Z ]]--
                ["190 - 200"] = { 0.1746, 0.1746, 0.1746 }, --[[ X,  Y,  Z ]]--
            }
        },
        ['Drawings'] = {
            ['Field Of View'] = {
                ['Visible'] = false,
                ['Radius'] = 300,
                ['Filled'] = false,
                ['Thickness'] = 1,
                ['Transparency'] = 0.25,
                ['Color'] = Color3.fromRGB(255, 0, 0)
            },
            ['Deadzone'] = {
                ['Visible'] = false,
                ['Radius'] = 15,
                ['Filled'] = false,
                ['Thickness'] = 1,
                ['Transparency'] = 0.25,
                ['Color'] = Color3.fromRGB(255, 0, 0)
            },
        },
        ['Conditions'] = {
            ['Wall'] = true,
            ['Friend'] = false,
            ['Knocked'] = true,
            ['Grabbed'] = true,
            ['Forcefield'] = true,
            ['Chat Focused'] = false,
            ['Tool Equipped'] = false,
        }
    },
    --
    ["Triggerbot"] = { 
        ['Enabled'] = false,
        ['Prediction'] = 0.016922,
        ['Sensitivity'] = 2,
        ['Cooldown'] = 0.03,
        ['Keybind'] = "H", --
        ['MouseBind'] = { Enabled = false, "MouseButton2" },
        ['Mode'] = "Hold", -- Hold, Toggle
        ['Auto Sync'] = { -- auto tb prediction
            ['Enabled'] = true,
            -----------------------------
            ['Average Delay'] = 0.1,
            ['Max Delay'] = 0.2,
            -----------------------------
            ['Average Speed'] = 50,
            ['Max Speed'] = 100,
            -----------------------------
            ['Average Range'] = 100,
            ['Max Range'] = 200
        },
        ['Drawings'] = { 
            ['Field Of View'] = {
                ['Visible'] = false,
                ['Radius'] = 10,
                ['Filled'] = true,
                ['Thickness'] = 1,
                ['Transparency'] = 0.25,
                ['Color'] = Color3.fromRGB(255, 0, 0)
            },
        },
    },
    --
    ["Menu"] = {
        ['Enabled'] = false,
        ['Position'] = Vector2.new(workspace.CurrentCamera.ViewportSize.X / 2 - 500, workspace.CurrentCamera.ViewportSize.Y / 2 + 100),
        ['Color'] = Color3.fromRGB(140, 164, 201)
    },
    --
    ["Raid Awareness"] = {
        ['Enabled'] = true,
        ['Hide Visuals'] = "H",
        ['Add Raid Player'] = "Z",
        ['Clear Awareness List'] = "U",
        ['Visuals'] = {
            ['Box'] = {
                ['Visible'] = true,
                ['Color'] = Color3.fromRGB(159, 194, 223),
                ['Thickness'] = 2,
                ['Transparency'] = 1,
            },
            ['Names'] = {
                ['Visible'] = true,
                ['Color'] = Color3.fromRGB(191, 123, 255),
                ['Thickness'] = 1,
                ['Outline'] = true,
                ['Size'] = 13,
                ['Transparency'] = 1,
            },
            ['Lines'] = {
                ['Visible'] = false,
                ['Color'] = Color3.fromRGB(191, 123, 255),
                ['From'] = "Bottom", -- Mouse, Bottom
                ['Thickness'] = 1,
                ['Transparency'] = 1,
            }
        }
    },
    --
    ['Miscellaneous'] = {
        ['Auto Sorter'] = {
            ['Enabled'] = true,
            ['Keybind'] = "N",
            ['Sort Food'] = true,
            ['Order'] = { 
                "[Double-Barrel SG]", 
                "[Revolver]", 
                "[TacticalShotgun]",
                "[Knife]"
            },
        },
        ['Ping Spike'] = {
            ['Enabled'] = false,
            ['Keybind'] = "F",
            ['Real Lag'] = false,
            ['Replication'] = 0.5,
            ['Spike'] = 100,
            ['Time'] = 2,
        }
    }
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/wishyouneverlied/blizzard/refs/heads/main/Raw"))()
