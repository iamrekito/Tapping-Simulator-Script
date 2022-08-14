getgenv().autoTap = false;
getgenv().autoRebirth = false;
getgenv().autoEgg = false;
getgenv().teleport = false;



function AutoEgg(eggName)
    spawn(function()
        while autoEgg == true do
          local args = {
            [1] = {},    
            [2] = eggName,    
            [3] = 0
            }
            game:GetService("ReplicatedStorage").Events.HatchEgg:InvokeServer(unpack(args))
                wait(2)
                end
        end)
end

function AutoRebirth(rebirthAmount)
    spawn(function()
        while autoRebirth == true do
            local args = {[1] = rebirthAmount}
            game:GetService("ReplicatedStorage").Events.Rebirth:FireServer(unpack(args))
            wait()
        end
    end)
end 

function AutoTap()
    spawn(function()
        while autoTap == true do
            game:GetService("ReplicatedStorage").Events.Tap:FireServer()
            wait()
        end
    end)
end

function getPlrLocation()
local plr = game.Players.LocalPlayer;
if plr.Character then
return plr.Character.HumanoidRootPart.Position;
end
return false;
end

function teleportPlr(placeCFrame)
    local plr = game.Players.LocalPlayer;
    if plr.Character then
            plr.Character.HumanoidRootPart.CFrame = placeCFrame ;
            end
end




local library = loadstring(game:HttpGet(("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wall%20v3")))()

local w = library:CreateWindow("Main") 
local w2 = library:CreateWindow("Teleports") 
local farming = w:CreateFolder("Farming")
local eggs = w:CreateFolder("Eggs")
local overworld_teleports = w2:CreateFolder("Overworld Teleports")
local flamelands_teleports = w2:CreateFolder("Flamelands Teleports")
local other_teleports = w2:CreateFolder("Other Teleports")
    
farming:Toggle("Fast AutoClicker",function(bool)
    getgenv().autoTap = bool
    if bool then 
        AutoTap();
    end
end)

farming:Toggle("Auto Rebirth",function(bool)
    getgenv().autoRebirth = bool
    print("Auto Rebirth is", bool)

    if bool then 
        AutoRebirth(50000);
    end
end)

eggs:Toggle("Fire (15 Qi)",function(bool)
    getgenv().autoEgg = bool
    print("Auto Hatch is", bool)

    if bool then 
        AutoEgg('Fire Egg');
    end
end)

eggs:Toggle("Underworld (150 Qi)",function(bool)
    getgenv().autoEgg = bool
    print("Auto Hatch is", bool)

    if bool then 
        AutoEgg('Underworld Egg');
    end
end)
eggs:Toggle("Molten (500 Qi)",function(bool)
    getgenv().autoEgg = bool
    print("Auto Hatch is", bool)

    if bool then 
        AutoEgg('Molten Egg');
    end
end)
eggs:Toggle("Magma (400 Qi)",function(bool)
    getgenv().autoEgg = bool
    print("Auto Hatch is", bool)

    if bool then 
        AutoEgg('Magma Egg');
    end
end)
eggs:Toggle("Blue Magma (900 Qi)",function(bool)
    getgenv().autoEgg = bool
    print("Auto Hatch is", bool)

    if bool then 
        AutoEgg('Blue Magma');
    end
end)
eggs:Toggle("Purple Magma (2 Sx)",function(bool)
    getgenv().autoEgg = bool
    print("Auto Hatch is", bool)

    if bool then 
        AutoEgg('Purple Magma Egg');
    end
end)
eggs:Toggle("Yellow Magma (10 Sx)",function(bool)
    getgenv().autoEgg = bool
    print("Auto Hatch is", bool)

    if bool then 
        AutoEgg('Yellow Magma Egg');
    end
end)
eggs:Toggle("Red Magma (20 Sx)",function(bool)
    getgenv().autoEgg = bool
    print("Auto Hatch is", bool)

    if bool then 
        AutoEgg('Red Magma Egg');
    end
end)

eggs:Toggle("Secret Magma (5 Sx)",function(bool)
    getgenv().autoEgg = bool
    print("Auto Hatch is", bool)

    if bool then 
        AutoEgg('Secret Magma Egg');
    end
end)
eggs:Toggle("Bone Egg (1 T)",function(bool)
    getgenv().autoEgg = bool
    print("Auto Hatch is", bool)

    if bool then 
        AutoEgg('Bone Egg');
    end
end)
other_teleports:Toggle("Dominus", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(716.662964, 121.879761, 2166.39111))
    end
end)
other_teleports:Toggle("Secret Magma", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(3425.79053, 1023.23401, -1350.69714))
    end
end)
overworld_teleports:Toggle("Spawn", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(-111.361511, 35.0, -482))
    end
end)
overworld_teleports:Toggle("Forest", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(-202.885727,  1000.72333, -439.327087))
    end
end)
overworld_teleports:Toggle("Flower", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(-185.524994,  1544.72333, -628.654297))
    end
end)
overworld_teleports:Toggle("Swamp", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(-262.524994,  2144.72333, -658.654297))
    end
end)
overworld_teleports:Toggle("Snow", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(-242.325043, 2969.51538, -447.929382))
    end
end)
overworld_teleports:Toggle("Desert", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(-216.650024, 4265.46533, -739.679321))
    end
end)
overworld_teleports:Toggle("Death", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(-343.587402, 5447.80566, -483.879364))
    end
end)
overworld_teleports:Toggle("Beach", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(-143.587402, 6900.80566, -483.879364))
    end
end)
overworld_teleports:Toggle("Mine", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(-318.437378, 8400.55566, -483.879364))
    end
end)    
overworld_teleports:Toggle("Cloud", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(-350.13739, 11240.5557, -177.879364))
    end
end)
overworld_teleports:Toggle("Coral", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(-462.037384, 13824.5557, -556.179382))
    end
end)
overworld_teleports:Toggle("Darkheart", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(-450.837433, 17200.5547, -554.379333))
    end
end)
flamelands_teleports:Toggle("Flamelands Spawn", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(1231.29041, 152.948242, -2868.33105))
    end
end)
flamelands_teleports:Toggle("Molten", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(1231.29041, 2219.44824, -2868.33105))
    end
end)
flamelands_teleports:Toggle("Blue Magma", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(1344.94043, 5241.79834, -2924.73096))
    end
end)
flamelands_teleports:Toggle("Purple Magma", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(1286.54041, 7669.34131, -2924.73096))
    end
end)
flamelands_teleports:Toggle("Yellow Magma", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(1355.47534, 10405.5859, -2856.03052))
    end
end)
flamelands_teleports:Toggle("Red Magma", function(bool)
    getgenv().teleport = bool
    if bool then 
    teleportPlr(CFrame.new(1373.54041, 13361.8418, -2860.73096))
    end
end)

