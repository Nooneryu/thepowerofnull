local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

  

local Window = Rayfield:CreateWindow({
   Name = "power of null",
   Icon = 0, -- Icon in Topbar. Can use Lucide Icons (string) or Roblox Image (number). 0 to use no icon (default).
   LoadingTitle = "SCRIPT ",
   LoadingSubtitle =https://docs.sirius.menu/rayfield/configuration/themes

   DisableRayfieldPrompts = false,
   DisableBuildWarnings = false, -- Prevents Rayfield from warning when the script has a ve with the interface

   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "OP FUCKGROUND"
   },

   Discord = {
      Enabled = false, -- Prompt the user to join your Discord server if their executor supports it
      Invite = "noninvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },

 KeySystem = true, -- Set this to true to use our key system
   KeySettings = {
      Title = "Key System",
      Subtitle = "Key System",
      Note = "U only can get this by chat with null", -- Use this to tell the user how to get a key
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {""} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

local Tab = Window:CreateTab("Main", 4483362458) -- Title, Image

-- Create Input Field
local Input = Tab:CreateInput({
   Name = "Enter Npc Name Kills Npc Use Sword Of Wicked",
   CurrentValue = "", -- Default value is empty
   PlaceholderText = "Type Npc here...",
   RemoveNameAfterFocusLost = false, -- Keeps the text after focus is lost
   Flag = "Input1", -- Unique flag identifier
   Callback = function(Text)
      if Name ~= "" then
	  while wait() do
	local args = {
    	[1] = "Input",
    	[2] = "WickednessSword of the Wicked",
    	[3] = 0,
    	[4] = "WeaveEvent",
    	[5] = workspace.NPCs:FindFirstChild(Text).HumanoidRootPart
	}

         -- Assuming you have access to this RemoteFunction
         game:GetService("Players").LocalPlayer.Character.Combat.RemoteEvent:FireServer(unpack(args))
		 end
      end
   end,
})

local Toggle = Tab:CreateToggle({
   Name = "Reality Dagger R Spam",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(CurrentValue)
   if CurrentValue then
        _G.loop2 = true
while _G.loop2 do
    local args = {
        [1] = "Input",
        [2] = "Reality KnifeReality Dagger",
        [3] = 0,
        [4] = "Stunner"
    }
    
    game:GetService("Players").LocalPlayer.Character.Combat.RemoteEvent:FireServer(unpack(args))
wait()
end
    else
        _G.loop2 = false
    end
   end,
})

local Toggle = Tab:CreateToggle({
   Name = "Everwinter m1 Spam",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(CurrentValue)
   if CurrentValue then
        _G.loop2 = true
while _G.loop2 do
local args = {
    [1] = "Input",
    [2] = "FrigpyreusEverwinter Blade",
    [3] = 6,
    [4] = "Bladestorm",
    [5] = Vector3.new(2914.81396484375, -13.31732177734375, 3138.40771484375)
}

game:GetService("Players").LocalPlayer.Character.Combat.RemoteEvent:FireServer(unpack(args))
wait()
end
    else
        _G.loop2 = false
    end
   end,
})

local Toggle = Tab:CreateToggle({
   Name = "Star Aura Needed Lord of Federation",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(CurrentValue)
   if CurrentValue then
        _G.loop2 = true
while _G.loop2 do
local args = {
    [1] = "Input",
    [2] = "Lord of the Federation",
    [3] = 20,
    [4] = "Galaxy"
}

game:GetService("Players").LocalPlayer.Character.Combat.RemoteEvent:FireServer(unpack(args))
wait()
end
    else
        _G.loop2 = false
    end
   end,
})

local Toggle = Tab:CreateToggle({
   Name = "Kill Aura Needed Lord of Federation",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(CurrentValue)
   if CurrentValue then
        _G.loop2 = true
while _G.loop2 do
local args = {
    [1] = "Input",
    [2] = "Lord of the Federation",
    [3] = 20,
    [4] = "Pull"
}

game:GetService("Players").LocalPlayer.Character.Combat.RemoteEvent:FireServer(unpack(args))
wait()
end
    else
        _G.loop2 = false
    end
   end,
})

local Toggle = Tab:CreateToggle({
   Name = "Loadout Spam",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(CurrentValue)
   if CurrentValue then
        _G.loop2 = true
while _G.loop2 do
local args = {
    [1] = "LoadoutChange",
    [2] = 1
}

game:GetService("ReplicatedStorage").RemoteEvent:FireServer(unpack(args))
wait()
end
    else
        _G.loop2 = false
    end
   end,
})

local Toggle = Tab:CreateToggle({
   Name = "wheel of death",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(CurrentValue)
   if CurrentValue then
        _G.loop2 = true
while _G.loop2 do
local args = {
    [1] = "Input",
    [2] = "Crimson Scythe",
    [3] = 3,
    [4] = "Wheel"
}

game:GetService("Players").LocalPlayer.Character.Combat.RemoteEvent:FireServer(unpack(args))
wait()
end
    else
        _G.loop2 = false
    end
   end,
})


local Toggle = Tab:CreateToggle({
   Name = "Fed Chest Spam",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(CurrentValue)
   if CurrentValue then
        _G.loop2 = true
while _G.loop2 do
    local args = {
        [1] = "ChangeEquipment",
        [2] = 4289
    }
    
    game:GetService("ReplicatedStorage").RemoteEvent:FireServer(unpack(args))
    wait() 
    local args = {
        [1] = "ChangeEquipment",
        [2] = 4289,
        [3] = true
    }
    
    game:GetService("ReplicatedStorage").RemoteEvent:FireServer(unpack(args))
wait()
end
    else
        _G.loop2 = false
    end
   end,
})

-- Variables for spamming logic
local player = game:GetService("Players").LocalPlayer
local isSpammingEnabledR = false
local isSpammingEnabledF = false
local isSpammingEnabledTrowel = false
local isSpammingEnabledLMBDarkmatter = false
local isHoldingR = false
local isHoldingF = false
local isHoldingTrowel = false
local isHoldingLMBDarkmatter = false

-- Function to fire the "R" remote
local function fireRemoteR()
    local mouse = player:GetMouse()
    local mousePosition = mouse.Hit.Position
    local args = {
        [1] = "Input",
        [2] = "MoriMemento Mori",
        [3] = 9,
        [4] = "R",
        [5] = mousePosition
    }
    player.Character.Combat.RemoteEvent:FireServer(unpack(args))
end

-- Function to fire the "F" remote
local function fireRemoteF()
    local mouse = player:GetMouse()
    local mousePosition = mouse.Hit.Position
    local args = {
        [1] = "Input",
        [2] = "MoriMemento Mori",
        [3] = 11.25,
        [4] = "F",
        [5] = mousePosition
    }
    player.Character.Combat.RemoteEvent:FireServer(unpack(args))
end

-- Function to fire the "Trowel" remote (LMB)
local function fireRemoteTrowel()
    local mouse = player:GetMouse()
    local mousePosition = mouse.Hit.Position
    local args = {
        [1] = "Input",
        [2] = "Trowel",
        [3] = 1.65,
        [4] = "Trowel",
        [5] = mousePosition
    }
    player.Character.Combat.RemoteEvent:FireServer(unpack(args))
end

-- Function to fire the "MatterDarkmatter Fists" remote (LMB)
local function fireRemoteDarkmatter()
    local args = {
        [1] = "Input",
        [2] = "MatterDarkmatter Fists",
        [3] = 7,
        [4] = "Pound"
    }
    player.Character.Combat.RemoteEvent:FireServer(unpack(args))
end

-- Start/Stop functions for spamming remotes
local function startSpammingR()
    isHoldingR = true
    while isHoldingR and isSpammingEnabledR do
        fireRemoteR()
        task.wait(0.1)
    end
end

local function stopSpammingR()
    isHoldingR = false
end

local function startSpammingF()
    isHoldingF = true
    while isHoldingF and isSpammingEnabledF do
        fireRemoteF()
        task.wait(0.1)
    end
end

local function stopSpammingF()
    isHoldingF = false
end

local function startSpammingTrowel()
    isHoldingTrowel = true
    while isHoldingTrowel and isSpammingEnabledTrowel do
        fireRemoteTrowel()
        task.wait(0.1)
    end
end

local function stopSpammingTrowel()
    isHoldingTrowel = false
end

local function startSpammingDarkmatter()
    isHoldingLMBDarkmatter = true
    while isHoldingLMBDarkmatter and isSpammingEnabledLMBDarkmatter do
        fireRemoteDarkmatter()
        task.wait(0.1)
    end
end

local function stopSpammingDarkmatter()
    isHoldingLMBDarkmatter = false
end

-- Rayfield Toggles
local ToggleR = Tab:CreateToggle({
    Name = "Memento Mori (R)",
    CurrentValue = false,
    Flag = "SpammingToggleR",
    Callback = function(Value)
        isSpammingEnabledR = Value
    end
})

local ToggleF = Tab:CreateToggle({
    Name = "Memento Mori Firing (F)",
    CurrentValue = false,
    Flag = "SpammingToggleF",
    Callback = function(Value)
        isSpammingEnabledF = Value
    end
})

local Button = Tab:CreateButton({
   Name = "Memento OF FIRE",
   Interact = 'Click',
   Callback = function()
  -- Function to generate a directional vector based on avatar's facing direction with spread
local function getShotVector(offsetAngle)
    local character = game:GetService("Players").LocalPlayer.Character
    local rootPart = character and character:FindFirstChild("HumanoidRootPart")

    if rootPart then
        local rotation = CFrame.Angles(0, math.rad(offsetAngle), 0) -- Yaw rotation for spread
        return (rootPart.CFrame * rotation).LookVector * math.random(8, 12) -- Apply rotation and scale
    else
        return Vector3.new(0, 0, 0) -- Default if rootPart is not found
    end
end

-- Fire shots in a 360-degree spread, repeated 3 times
for i = 1, 3 do -- Fire 3 times
    for angle = 0, 360, 20 do -- Spread shots every 36 degrees
        local args = {
            [1] = "Input",
            [2] = "MoriMemento Mori",
            [3] = 2,
            [4] = "LMB",
            [5] = getShotVector(angle) -- Get vector for each angle
        }

        game:GetService("Players").LocalPlayer.Character.Combat.RemoteEvent:FireServer(unpack(args))
    end
    wait() -- Add a small delay between rounds
end
   end,
})

local ToggleTrowel = Tab:CreateToggle({
    Name = "Fortnite Build Mode (Trowel - LMB)",
    CurrentValue = false,
    Flag = "SpammingToggleTrowel",
    Callback = function(Value)
        isSpammingEnabledTrowel = Value
    end
})

local ToggleDarkmatter = Tab:CreateToggle({
    Name = "Loud ASS NOISE (Darkmatter - LMB)",
    CurrentValue = false,
    Flag = "SpammingToggleDarkmatter",
    Callback = function(Value)
        isSpammingEnabledLMBDarkmatter = Value
    end
})

-- Input Handlers
game:GetService("UserInputService").InputBegan:Connect(function(input, gameProcessed)
    if gameProcessed then return end
    if input.KeyCode == Enum.KeyCode.R and isSpammingEnabledR then
        startSpammingR()
    elseif input.KeyCode == Enum.KeyCode.F and isSpammingEnabledF then
        startSpammingF()
    elseif input.UserInputType == Enum.UserInputType.MouseButton1 then
        if isSpammingEnabledTrowel then
            startSpammingTrowel()
        elseif isSpammingEnabledLMBDarkmatter then
            startSpammingDarkmatter()
        end
    end
end)

game:GetService("UserInputService").InputEnded:Connect(function(input)
    if input.KeyCode == Enum.KeyCode.R then
        stopSpammingR()
    elseif input.KeyCode == Enum.KeyCode.F then
        stopSpammingF()
    elseif input.UserInputType == Enum.UserInputType.MouseButton1 then
        stopSpammingTrowel()
        stopSpammingDarkmatter()
    end
end)

local Input = Tab:CreateInput({
   Name = "Enter Levels Store",
   CurrentValue = "", -- Default value is empty
   PlaceholderText = "Enter Levels To Store",
   RemoveTextAfterFocusLost = false, -- Keeps the text after focus is lost
   Flag = "Input1", -- Unique flag identifier
   Callback = function(Value)
      -- The function that takes place when the input is changed
      -- The variable (Text) is a string for the value in the text box
      if Value ~= "" then
    local args = {
        [1] = "StowLevel",
        [2] = Value
    }

    game:GetService("ReplicatedStorage").RemoteEvent:FireServer(unpack(args))
      end
   end,
})

local Input = Tab:CreateInput({
   Name = "Enter Levels Retrieve",
   CurrentValue = "", -- Default value is empty
   PlaceholderText = "Enter Levels To Retrieve",
   RemoveTextAfterFocusLost = false, -- Keeps the text after focus is lost
   Flag = "Input1", -- Unique flag identifier
   Callback = function(Value)
      -- The function that takes place when the input is changed
      -- The variable (Text) is a string for the value in the text box
      if Value ~= "" then
    local args = {
        [1] = "RetrieveLevel",
        [2] = Value
    }

    game:GetService("ReplicatedStorage").RemoteEvent:FireServer(unpack(args))
      end
   end,
})

local Button = Tab:CreateButton({
   Name = "Phase Artifical Hood",
   Callback = function()
    for i = 1, 30 do
            local args = {
                [1] = "Input",
                [2] = "ArtiphaseArtificer's Hood",
                [3] = 6,
                [4] = "Phase"
            }
            game:GetService("Players").LocalPlayer.Character.Combat.RemoteEvent:FireServer(unpack(args))
        end
   end,
})

local Button = Tab:CreateButton({
   Name = "Stunner Reality Dagger",
   Callback = function()
    for i = 1, 60 do
            local args = {
                [1] = "Input",
                [2] = "Reality KnifeReality Dagger",
                [3] = 8,
                [4] = "Stunner"
            }
            game:GetService("Players").LocalPlayer.Character.Combat.RemoteEvent:FireServer(unpack(args))
        end
   end,
})

local Button = Tab:CreateButton({
   Name = "Reality - Reality Dagger",
   Callback = function()
    for i = 1, 70 do
            local args = {
                [1] = "Input",
                [2] = "Reality KnifeReality Dagger",
                [3] = 8,
                [4] = "Reality"
            }
            game:GetService("Players").LocalPlayer.Character.Combat.RemoteEvent:FireServer(unpack(args))
        end
   end,
})

local Toggle = Tab:CreateToggle({
   Name = "INF BLOCK",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(CurrentValue)
   if CurrentValue then
        _G.loop2 = true
while _G.loop2 do
local args = {
    [1] = "Input",
    [2] = "Golden Scion Shield",
    [3] = 0,
    [4] = "Block"
}

game:GetService("Players").LocalPlayer.Character.Combat.RemoteEvent:FireServer(unpack(args))
wait()
end
    else
        _G.loop2 = false
    end
   end,
})


local Toggle = Tab:CreateToggle({
   Name = "ELIMINATOR RINGS",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(CurrentValue)
   if CurrentValue then
        _G.loop2 = true
while _G.loop2 do
local args = {
    [1] = "Input",
    [2] = "The Eliminator",
    [3] = 0.6734006734006734,
    [4] = "Toss"
}

game:GetService("Players").LocalPlayer.Character.Combat.RemoteEvent:FireServer(unpack(args))
wait()
end
    else
        _G.loop2 = false
    end
   end,
})

local Toggle = Tab:CreateToggle({
   Name = "Pull Npcs",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(CurrentValue)
   if CurrentValue then
        _G.loop2 = true
while _G.loop2 do
local args = {
    [1] = "Input",
    [2] = "Aureus XDominus Aureus",
    [3] = 5,
    [4] = "Flash"
}

game:GetService("Players").LocalPlayer.Character.Combat.RemoteEvent:FireServer(unpack(args))
wait()
end
    else
        _G.loop2 = false
    end
   end,
})

local Button = Tab:CreateButton({
   Name = "Lag People Rb 1",
   Interact = 'Click',
   Callback = function()
   local args = {
    [1] = "Input",
    [2] = "Aureus XDominus Aureus",
    [3] = 5,
    [4] = "Retribe"
}

game:GetService("Players").LocalPlayer.Character.Combat.RemoteEvent:FireServer(unpack(args))
   end,
})

-- Variables for spamming logic
local player = game:GetService("Players").LocalPlayer
local isSpammingEnabledR = false
local isSpammingEnabledF = false
local isSpammingEnabledTrowel = false
local isSpammingEnabledLMBDarkmatter = false
local isSpammingEnabledCrescendo = false
local isSpammingEnabledArmedesF = false
local isSpammingEnabledMementoLMB = false -- New toggle for LMB remote
local isSpammingEnabledArmedesR = false -- Updated toggle name for ArmedesR
local isHoldingR = false
local isHoldingF = false
local isHoldingTrowel = false
local isHoldingLMBDarkmatter = false
local isHoldingCrescendo = false
local isHoldingArmedesF = false
local isHoldingMementoLMB = false
local isHoldingArmedesR = false -- Updated toggle name for ArmedesR

-- Function to fire the "R" remote (Memento Mori)
local function fireRemoteR()
    local mouse = player:GetMouse()
    local mousePosition = mouse.Hit.Position
    local args = {
        [1] = "Input",
        [2] = "MoriMemento Mori",
        [3] = 9,
        [4] = "R",
        [5] = mousePosition
    }
    player.Character.Combat.RemoteEvent:FireServer(unpack(args))
end

-- Function to fire the "F" remote (Memento Mori)
local function fireRemoteF()
    local mouse = player:GetMouse()
    local mousePosition = mouse.Hit.Position
    local args = {
        [1] = "Input",
        [2] = "MoriMemento Mori",
        [3] = 11.25,
        [4] = "F",
        [5] = mousePosition
    }
    player.Character.Combat.RemoteEvent:FireServer(unpack(args))
end

-- Function to fire the "Trowel" remote (LMB)
local function fireRemoteTrowel()
    local mouse = player:GetMouse()
    local mousePosition = mouse.Hit.Position
    local args = {
        [1] = "Input",
        [2] = "Trowel",
        [3] = 1.65,
        [4] = "Trowel",
        [5] = mousePosition
    }
    player.Character.Combat.RemoteEvent:FireServer(unpack(args))
end

-- Function to fire the "MatterDarkmatter Fists" remote (LMB)
local function fireRemoteDarkmatter()
    local args = {
        [1] = "Input",
        [2] = "MatterDarkmatter Fists",
        [3] = 7,
        [4] = "Pound"
    }
    player.Character.Combat.RemoteEvent:FireServer(unpack(args))
end

-- Function to fire the "Crescendo" remote (R)
local function fireRemoteCrescendo()
    local args = {
        [1] = "Input",
        [2] = "Crescendo",
        [3] = 11,
        [4] = "Laser"
    }
    player.Character.Combat.RemoteEvent:FireServer(unpack(args))
end

-- Function to fire the "Armedes" remote (F)
local function fireRemoteArmedesF()
    local args = {
        [1] = "Input",
        [2] = "ArmedesDuke of the Fallen Federation",
        [3] = 12,
        [4] = "Laser"
    }
    player.Character.Combat.RemoteEvent:FireServer(unpack(args))
end

-- Function to fire the new "Memento Mori LMB" remote (at mouse position)
local function fireRemoteMementoLMB()
    local mouse = player:GetMouse()
    local mousePosition = mouse.Hit.Position
    local args = {
        [1] = "Input",
        [2] = "MoriMemento Mori",
        [3] = 2,
        [4] = "LMB",
        [5] = mousePosition
    }
    player.Character.Combat.RemoteEvent:FireServer(unpack(args))
end

-- Function to fire the updated "Armedes - Meteors" remote (R)
local function fireRemoteArmedesR()
    local args = {
        [1] = "Input",
        [2] = "ArmedesDuke of the Fallen Federation",
        [3] = 20,
        [4] = "Meteors"
    }
    player.Character.Combat.RemoteEvent:FireServer(unpack(args))
end

-- Start/Stop functions for spamming remotes
local function startSpammingR()
    isHoldingR = true
    while isHoldingR and isSpammingEnabledR do
        fireRemoteR()
        task.wait(0.1)
    end
end

local function stopSpammingR()
    isHoldingR = false
end

local function startSpammingF()
    isHoldingF = true
    while isHoldingF and isSpammingEnabledF do
        fireRemoteF()
        task.wait(0.1)
    end
end

local function stopSpammingF()
    isHoldingF = false
end

local function startSpammingTrowel()
    isHoldingTrowel = true
    while isHoldingTrowel and isSpammingEnabledTrowel do
        fireRemoteTrowel()
        task.wait(0.1)
    end
end

local function stopSpammingTrowel()
    isHoldingTrowel = false
end

local function startSpammingDarkmatter()
    isHoldingLMBDarkmatter = true
    while isHoldingLMBDarkmatter and isSpammingEnabledLMBDarkmatter do
        fireRemoteDarkmatter()
        task.wait(0.1)
    end
end

local function stopSpammingDarkmatter()
    isHoldingLMBDarkmatter = false
end

local function startSpammingCrescendo()
    isHoldingCrescendo = true
    while isHoldingCrescendo and isSpammingEnabledCrescendo do
        fireRemoteCrescendo()
        task.wait(0.1)
    end
end

local function stopSpammingCrescendo()
    isHoldingCrescendo = false
end

local function startSpammingArmedesF()
    isHoldingArmedesF = true
    while isHoldingArmedesF and isSpammingEnabledArmedesF do
        fireRemoteArmedesF()
        task.wait(0.1)
    end
end

local function stopSpammingArmedesF()
    isHoldingArmedesF = false
end

local function startSpammingMementoLMB()
    isHoldingMementoLMB = true
    while isHoldingMementoLMB and isSpammingEnabledMementoLMB do
        fireRemoteMementoLMB()
        task.wait(0.1)
    end
end

local function stopSpammingMementoLMB()
    isHoldingMementoLMB = false
end

local function startSpammingArmedesR()
    isHoldingArmedesR = true
    while isHoldingArmedesR and isSpammingEnabledArmedesR do
        fireRemoteArmedesR()
        task.wait(0.1)
    end
end

local function stopSpammingArmedesR()
    isHoldingArmedesR = false
end

-- Rayfield Toggles
local ToggleR = Tab:CreateToggle({
    Name = "Memento Mori (R)",
    CurrentValue = false,
    Flag = "SpammingToggleR",
    Callback = function(Value)
        isSpammingEnabledR = Value
    end
})

local ToggleF = Tab:CreateToggle({
    Name = "Memento Mori (F)",
    CurrentValue = false,
    Flag = "SpammingToggleF",
    Callback = function(Value)
        isSpammingEnabledF = Value
    end
})

local ToggleTrowel = Tab:CreateToggle({
    Name = "Trowel (LMB)",
    CurrentValue = false,
    Flag = "SpammingToggleTrowel",
    Callback = function(Value)
        isSpammingEnabledTrowel = Value
    end
})

local ToggleDarkmatter = Tab:CreateToggle({
    Name = "Darkmatter Fists (LMB)",
    CurrentValue = false,
    Flag = "SpammingToggleDarkmatter",
    Callback = function(Value)
        isSpammingEnabledLMBDarkmatter = Value
    end
})

local ToggleCrescendo = Tab:CreateToggle({
    Name = "Crescendo (R)",
    CurrentValue = false,
    Flag = "SpammingToggleCrescendo",
    Callback = function(Value)
        isSpammingEnabledCrescendo = Value
    end
})

local ToggleArmedesF = Tab:CreateToggle({
    Name = "Armedes (F)",
    CurrentValue = false,
    Flag = "SpammingToggleArmedesF",
    Callback = function(Value)
        isSpammingEnabledArmedesF = Value
    end
})

local ToggleMementoLMB = Tab:CreateToggle({
    Name = "Memento Mori (LMB - At Mouse)",
    CurrentValue = false,
    Flag = "SpammingToggleMementoLMB",
    Callback = function(Value)
        isSpammingEnabledMementoLMB = Value
    end
})

local ToggleArmedesR = Tab:CreateToggle({
    Name = "Armedes Meteors (R)",
    CurrentValue = false,
    Flag = "SpammingToggleArmedesR",
    Callback = function(Value)
        isSpammingEnabledArmedesR = Value
    end
})

-- Input Handlers
game:GetService("UserInputService").InputBegan:Connect(function(input, gameProcessed)
    if gameProcessed then return end
    if input.KeyCode == Enum.KeyCode.R and isSpammingEnabledR then
        startSpammingR()
    elseif input.KeyCode == Enum.KeyCode.F and isSpammingEnabledF then
        startSpammingF()
    elseif input.UserInputType == Enum.UserInputType.MouseButton1 then
        if isSpammingEnabledTrowel then
            startSpammingTrowel()
        elseif isSpammingEnabledLMBDarkmatter then
            startSpammingDarkmatter()
        elseif isSpammingEnabledMementoLMB then
            startSpammingMementoLMB()
        elseif isSpammingEnabledArmedesR then
            startSpammingArmedesR()
        end
    end
end)

game:GetService("UserInputService").InputEnded:Connect(function(input)
    if input.KeyCode == Enum.KeyCode.R then
        stopSpammingR()
        stopSpammingArmedesR()
    elseif input.KeyCode == Enum.KeyCode.F then
        stopSpammingF()
        stopSpammingArmedesF()
    elseif input.UserInputType == Enum.UserInputType.MouseButton1 then
        stopSpammingTrowel()
        stopSpammingDarkmatter()
        stopSpammingMementoLMB()
    end
end)






