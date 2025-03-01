 -- Carregar a Biblioteca
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

local Window = Fluent:CreateWindow({
    Title = "xeksingt hub X" .. Fluent.Version,
    TabWidth = 100, Size = UDim2.fromOffset(580, 460), Theme = "Cyan"
    })
    
    local Tabs = {
    Main = Window:AddTab({ Title = "Execultores" }),
    Settings = Window:AddTab({ Title = "Configurações", Icon = "settings" })
    }
    
    Tabs.Main:AddParagraph({ Title = "Credits:Xester_Boss", Content = "Version 1.0" })
   
   Tabs.Main:AddButton({ Title = "Project Ligma", Callback = function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Project-Ligma-28816"))()
end })

Tabs.Main:AddButton({ Title = "Rc7 Execultor", Callback = function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Rc7-Fake-28794"))()
end })

  local Tabs = {
    Main = Window:AddTab({ Title = "Scripts" }),
    }
    
    Tabs.Main:AddButton({ Title = "FE Fly", Callback = function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Fly-gui-v3-30439"))()
end })

Tabs.Main:AddButton({ Title = "Super Ring Part", Callback = function()
   loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Super-Ring-Part-V3-27438"))()
end })

Tabs.Main:AddButton({ Title = "Xester (Me)", Callback = function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Xester-15493"))()
end })

Tabs.Main:AddButton({ Title = "Infinity Yield SS (admin)", Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Infinite-Yield-FE-27010"))()
end})

Main = Window:AddTab({ Title = "Hubs" }),
}

Tabs.Main:AddButton({ Title = "tubers93 hub X", Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-tubers93-26163"))()
end})

Tabs.Main:AddButton({ Title = "c00kid hub X", Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-COOLKIDD-GUI-27826"))()
end})

Main = Window:AddTab({ Title = "Xit" }),
   }
