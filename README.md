--carregar a biblioteca
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

local Window = Fluent:CreateWindow({
    Title = "adm hub " .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Dark"
})

local Tabs = {
    Main = Window:AddTab({ Title = "Script" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}
--parágrafos
Tabs.Main:AddParagraph({ Title = "davi", Content = "e bem aqui" })
--Botoes
Tabs.Main:AddButton({ Title = "Button", Callback = function() 
print ("loadstring(game:HttpGet("https://raw.githubusercontent.com/HeyGyt/infjump/main/main"))()
end)")
 end })
