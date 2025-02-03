local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/UI-Libraries/main/RedzHub.lua"))()

-- Criação da janela do Hub
local Window = Library:CreateWindow("Toleto Hub", "Blox Fruits Sea 2")

Window:SetBackgroundColor(Color3.fromRGB(139, 69, 19)) -- Cor marrom para o fundo

-- Aba de Auto Farm
local AutoFarmTab = Window:CreateTab("Farm", true)
AutoFarmTab:CreateButton("Ativar Auto Farm", function()
    print("Auto Farm ativado!") -- Aqui entra o código do Auto Farm
end)

AutoFarmTab:CreateButton("Auto CDK", function()
    print("Auto CDK ativado!") -- Aqui entra o código do Auto CDK
end)

AutoFarmTab:CreateButton("Auto Buy Haki Seller", function()
    print("Comprando Haki Seller...") -- Aqui entra o código para comprar Haki
end)

AutoFarmTab:CreateButton("Auto Buy Sword Seller", function()
    print("Comprando Sword Seller...") -- Aqui entra o código para comprar espada
end)

-- Aba de Raids
local RaidsTab = Window:CreateTab("Raids", true)
RaidsTab:CreateButton("Auto Raid", function()
    print("Auto Raid iniciado!") -- Código do Auto Raid aqui
end)

RaidsTab:CreateButton("Auto Raid Pirata", function()
    print("Auto Raid Pirata iniciado!") -- Código do Auto Raid Pirata aqui
end)

-- Aba de Transformações
local TransformTab = Window:CreateTab("Transformações", true)
TransformTab:CreateButton("Auto V2 e V3", function()
    print("Auto V2 e V3 ativado!") -- Código do Auto V2 e V3
end)

TransformTab:CreateButton("Auto Skull Guitar", function()
    print("Auto Skull Guitar ativado!") -- Código do Auto Skull Guitar
end)

-- Aba de Teleport & ESP
local TeleportTab = Window:CreateTab("Teleport & ESP", true)
TeleportTab:CreateButton("Ativar ESP", function()
    print("ESP ativado!") -- Código do ESP aqui
end)

TeleportTab:CreateButton("Teleportar", function()
    print("Teleportando...") -- Código de teleport aqui
end)

-- Aba de Bosses
local BossTab = Window:
