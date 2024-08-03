getgenv().Settings = {
    Zelex = {
        Enabled = true,
        Prediction = 0.1398,
        Notifications = true,
        AimPart = "HumanoidRootPart",
        KoCheck = true,
        LookAt = false,
        Resolver = true,
        AutoAir = true,
        Highlight = true,
        GUI = true -- no GUI yet
    },
    Global = {
        Tool_Lock = false,
        Button = true
    },
    Camera = {
        SmoothCamSpeed = 0.05,
        ShakeIntensity = 0.1
    },
    Visuals = {
        No_Fog = false,
        Color_Correction = false,
        Korblox = true,
        Headless = true,
        LowGFX = false,
        Ambient = false,
    },
    Textures = { 
        Regular = false,
        Black = false,
        Sand = false 
    },
    Misc = {
        TrashTalk = false, -- click the button for trashtalk
        TrashTalk_On_KO = false
    },
    SpeedGlitch = {
        Macro = true, -- click the button for trashtalk
        Respawn = true
    },
    ESP = {
        enabled = true,
        highlight = true,
        outline = true
    },
    FOV = {
        showFOV = false,
        fill = false,
        size = 120,
        transparency = 0.1,
        thickness = 0.1,
        color = Color3.fromRGB(0,0,139)
    },
    FOVconfig = {
        circle = Drawing.new("Circle"),
        silentAim = {
            targetPart = "HumanoidRootPart",
            prediction = 0.1485436,
            isActive = true,
        }
    }
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/coolkid23319/Zelex/main/Zelex_loader.lua"))()
