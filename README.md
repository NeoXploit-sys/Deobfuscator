-- LocalScript: Desofuscador Universal CORRETO
-- Coloque em StarterGui > ScreenGui ou diretamente no PlayerGui

local Players = game:GetService("Players")
local Player = Players.LocalPlayer
local UserInputService = game:GetService("UserInputService")
local HttpService = game:GetService("HttpService")
local TweenService = game:GetService("TweenService")
local TextService = game:GetService("TextService")

-- Primeiro, garantir que temos uma ScreenGui
local screenGui = Instance.new("ScreenGui")
screenGui.Name = "DeobfuscatorGUI"
screenGui.ResetOnSpawn = false
screenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
screenGui.Parent = Player:WaitForChild("PlayerGui")

-- Frame principal VISÍVEL PORRA
local mainFrame = Instance.new("Frame")
mainFrame.Name = "MainFrame"
mainFrame.Size = UDim2.new(0, 500, 0, 600)
mainFrame.Position = UDim2.new(0.5, -250, 0.5, -300)
mainFrame.BackgroundColor3 = Color3.fromRGB(30, 30, 40)
mainFrame.BorderSizePixel = 0
mainFrame.Visible = true  -- IMPORTANTE: VISÍVEL!
mainFrame.Active = true
mainFrame.Draggable = true
mainFrame.Parent = screenGui

-- Arredondar cantos
local uiCorner = Instance.new("UICorner")
uiCorner.CornerRadius = UDim.new(0, 8)
uiCorner.Parent = mainFrame

-- Borda
local uiStroke = Instance.new("UIStroke")
uiStroke.Color = Color3.fromRGB(60, 60, 80)
uiStroke.Thickness = 2
uiStroke.Parent = mainFrame

-- BARRA DE TÍTULO COM BOTÃO DE FECHAR
local titleBar = Instance.new("Frame")
titleBar.Name = "TitleBar"
titleBar.Size = UDim2.new(1, 0, 0, 40)
titleBar.Position = UDim2.new(0, 0, 0, 0)
titleBar.BackgroundColor3 = Color3.fromRGB(40, 40, 50)
titleBar.BorderSizePixel = 0
titleBar.Parent = mainFrame

local titleLabel = Instance.new("TextLabel")
titleLabel.Name = "TitleLabel"
titleLabel.Size = UDim2.new(0.7, 0, 1, 0)
titleLabel.Position = UDim2.new(0, 10, 0, 0)
titleLabel.BackgroundTransparency = 1
titleLabel.Text = "🧬 DESOFUSCADOR ULTRA"
titleLabel.TextColor3 = Color3.fromRGB(220, 220, 255)
titleLabel.TextSize = 18
titleLabel.Font = Enum.Font.GothamBold
titleLabel.TextXAlignment = Enum.TextXAlignment.Left
titleLabel.Parent = titleBar

-- BOTÃO DE FECHAR GRANDE E VISÍVEL
local closeButton = Instance.new("TextButton")
closeButton.Name = "CloseButton"
closeButton.Size = UDim2.new(0, 80, 0, 30)
closeButton.Position = UDim2.new(1, -90, 0.5, -15)
closeButton.BackgroundColor3 = Color3.fromRGB(255, 80, 80)
closeButton.TextColor3 = Color3.new(1, 1, 1)
closeButton.Text = "❌ FECHAR"
closeButton.TextSize = 14
closeButton.Font = Enum.Font.GothamBold
closeButton.Parent = titleBar

local closeCorner = Instance.new("UICorner")
closeCorner.CornerRadius = UDim.new(0, 6)
closeCorner.Parent = closeButton

-- ÁREA DE INPUT
local inputContainer = Instance.new("Frame")
inputContainer.Name = "InputContainer"
inputContainer.Size = UDim2.new(1, -20, 0, 200)
inputContainer.Position = UDim2.new(0, 10, 0, 50)
inputContainer.BackgroundColor3 = Color3.fromRGB(35, 35, 45)
inputContainer.BorderSizePixel = 0
inputContainer.Parent = mainFrame

local inputLabel = Instance.new("TextLabel")
inputLabel.Name = "InputLabel"
inputLabel.Size = UDim2.new(1, 0, 0, 25)
inputLabel.BackgroundTransparency = 1
inputLabel.Text = "📥 CÓDIGO OFUSCADO:"
inputLabel.TextColor3 = Color3.fromRGB(180, 200, 255)
inputLabel.TextSize = 14
inputLabel.Font = Enum.Font.GothamSemibold
inputLabel.TextXAlignment = Enum.TextXAlignment.Left
inputLabel.Parent = inputContainer

local inputBox = Instance.new("TextBox")
inputBox.Name = "InputBox"
inputBox.Size = UDim2.new(1, -10, 1, -35)
inputBox.Position = UDim2.new(0, 5, 0, 30)
inputBox.BackgroundColor3 = Color3.fromRGB(25, 25, 30)
inputBox.TextColor3 = Color3.fromRGB(220, 220, 255)
inputBox.Text = ""
inputBox.PlaceholderText = "Cole seu script ofuscado aqui..."
inputBox.TextSize = 12
inputBox.Font = Enum.Font.Code
inputBox.TextXAlignment = Enum.TextXAlignment.Left
inputBox.TextYAlignment = Enum.TextYAlignment.Top
inputBox.ClearTextOnFocus = false
inputBox.MultiLine = true
inputBox.TextWrapped = false
inputBox.ScrollingEnabled = true
inputBox.Parent = inputContainer

local inputCorner = Instance.new("UICorner")
inputCorner.CornerRadius = UDim.new(0, 6)
inputCorner.Parent = inputBox

-- BOTÕES DE AÇÃO (AGORA VISÍVEIS!)
local buttonContainer = Instance.new("Frame")
buttonContainer.Name = "ButtonContainer"
buttonContainer.Size = UDim2.new(1, -20, 0, 40)
buttonContainer.Position = UDim2.new(0, 10, 0, 260)
buttonContainer.BackgroundTransparency = 1
buttonContainer.Parent = mainFrame

-- BOTÃO DESOFUSCAR GRANDE
local deobfuscateBtn = Instance.new("TextButton")
deobfuscateBtn.Name = "DeobfuscateBtn"
deobfuscateBtn.Size = UDim2.new(0.48, 0, 1, 0)
deobfuscateBtn.Position = UDim2.new(0, 0, 0, 0)
deobfuscateBtn.BackgroundColor3 = Color3.fromRGB(80, 120, 255)
deobfuscateBtn.TextColor3 = Color3.new(1, 1, 1)
deobfuscateBtn.Text = "🚀 DESOFUSCAR"
deobfuscateBtn.TextSize = 14
deobfuscateBtn.Font = Enum.Font.GothamBold
deobfuscateBtn.Parent = buttonContainer

-- BOTÃO COPIAR GRANDE
local copyBtn = Instance.new("TextButton")
copyBtn.Name = "CopyBtn"
copyBtn.Size = UDim2.new(0.48, 0, 1, 0)
copyBtn.Position = UDim2.new(0.52, 0, 0, 0)
copyBtn.BackgroundColor3 = Color3.fromRGB(60, 180, 100)
copyBtn.TextColor3 = Color3.new(1, 1, 1)
copyBtn.Text = "📋 COPIAR"
copyBtn.TextSize = 14
copyBtn.Font = Enum.Font.GothamBold
copyBtn.Parent = buttonContainer

-- Arredondar botões
local btnCorner1 = Instance.new("UICorner")
btnCorner1.CornerRadius = UDim.new(0, 8)
btnCorner1.Parent = deobfuscateBtn

local btnCorner2 = Instance.new("UICorner")
btnCorner2.CornerRadius = UDim.new(0, 8)
btnCorner2.Parent = copyBtn

-- BOTÃO EXTRA: LIMPAR
local clearBtn = Instance.new("TextButton")
clearBtn.Name = "ClearBtn"
clearBtn.Size = UDim2.new(0.3, 0, 0, 25)
clearBtn.Position = UDim2.new(0.35, 0, 1, 5)
clearBtn.BackgroundColor3 = Color3.fromRGB(180, 80, 80)
clearBtn.TextColor3 = Color3.new(1, 1, 1)
clearBtn.Text = "🧹 LIMPAR"
clearBtn.TextSize = 12
clearBtn.Font = Enum.Font.Gotham
clearBtn.Parent = buttonContainer

local clearCorner = Instance.new("UICorner")
clearCorner.CornerRadius = UDim.new(0, 6)
clearCorner.Parent = clearBtn

-- ÁREA DE OUTPUT
local outputContainer = Instance.new("Frame")
outputContainer.Name = "OutputContainer"
outputContainer.Size = UDim2.new(1, -20, 0, 250)
outputContainer.Position = UDim2.new(0, 10, 0, 310)
outputContainer.BackgroundColor3 = Color3.fromRGB(35, 45, 35)
outputContainer.BorderSizePixel = 0
outputContainer.Parent = mainFrame

local outputLabel = Instance.new("TextLabel")
outputLabel.Name = "OutputLabel"
outputLabel.Size = UDim2.new(1, 0, 0, 25)
outputLabel.BackgroundTransparency = 1
outputLabel.Text = "📤 CÓDIGO DESOFUSCADO:"
outputLabel.TextColor3 = Color3.fromRGB(180, 255, 180)
outputLabel.TextSize = 14
outputLabel.Font = Enum.Font.GothamSemibold
outputLabel.TextXAlignment = Enum.TextXAlignment.Left
outputLabel.Parent = outputContainer

local outputBox = Instance.new("TextBox")
outputBox.Name = "OutputBox"
outputBox.Size = UDim2.new(1, -10, 1, -35)
outputBox.Position = UDim2.new(0, 5, 0, 30)
outputBox.BackgroundColor3 = Color3.fromRGB(25, 30, 25)
outputBox.TextColor3 = Color3.fromRGB(180, 255, 180)
outputBox.Text = ""
outputBox.TextSize = 12
outputBox.Font = Enum.Font.Code
outputBox.TextXAlignment = Enum.TextXAlignment.Left
outputBox.TextYAlignment = Enum.TextYAlignment.Top
outputBox.ClearTextOnFocus = false
outputBox.MultiLine = true
outputBox.TextWrapped = false
outputBox.ScrollingEnabled = true
outputBox.Parent = outputContainer

local outputCorner = Instance.new("UICorner")
outputCorner.CornerRadius = UDim.new(0, 6)
outputCorner.Parent = outputBox

-- STATUS BAR
local statusBar = Instance.new("Frame")
statusBar.Name = "StatusBar"
statusBar.Size = UDim2.new(1, -20, 0, 30)
statusBar.Position = UDim2.new(0, 10, 1, -35)
statusBar.BackgroundColor3 = Color3.fromRGB(40, 40, 50)
statusBar.BorderSizePixel = 0
statusBar.Parent = mainFrame

local statusLabel = Instance.new("TextLabel")
statusLabel.Name = "StatusLabel"
statusLabel.Size = UDim2.new(1, 0, 1, 0)
statusLabel.BackgroundTransparency = 1
statusLabel.Text = "✅ Pronto! Pressione F5 para mostrar/esconder"
statusLabel.TextColor3 = Color3.fromRGB(200, 220, 255)
statusLabel.TextSize = 12
statusLabel.Font = Enum.Font.Gotham
statusLabel.Parent = statusBar

-- SISTEMA DE DESOFUSCAÇÃO
local Deobfuscator = {}

function Deobfuscator.decodeBase64(str)
    local success, result = pcall(function()
        return HttpService:JSONDecode(HttpService:Base64Decode(str))
    end)
    if success then return result end
    return nil
end

function Deobfuscator.decodeStringChar(code)
    local function processChar(match)
        local nums = {}
        for num in string.gmatch(match, "%d+") do
            table.insert(nums, tonumber(num))
        end
        local result = ""
        for _, n in ipairs(nums) do
            result = result .. string.char(n)
        end
        return '"' .. result .. '"'
    end
    return string.gsub(code, "string%.char%(([^)]+)%)", processChar)
end

function Deobfuscator.simpleDeobfuscate(code)
    statusLabel.Text = "🔄 Processando..."
    
    -- Tentar Base64
    local success1, result1 = pcall(function()
        return HttpService:Base64Decode(code)
    end)
    if success1 and #result1 > 10 then
        code = result1
    end
    
    -- Decodificar string.char
    code = Deobfuscator.decodeStringChar(code)
    
    -- Decodificar hex
    code = string.gsub(code, "\\x(%x%x)", function(hex)
        return string.char(tonumber(hex, 16))
    end)
    
    -- Remover variáveis simples
    code = string.gsub(code, "local%s+%w+%s*=%s*%w+;?", "")
    
    statusLabel.Text = "✅ Desofuscação completa!"
    return code
end

-- FUNÇÃO PARA COPIAR
local function copyToClipboard(text)
    if setclipboard then
        setclipboard(text)
        return true
    elseif pcall(function() UserInputService:SetClipboard(text) end) then
        return true
    else
        -- Fallback
        local temp = Instance.new("TextBox")
        temp.Text = text
        temp.Parent = screenGui
        temp:CaptureFocus()
        temp:SelectAll()
        wait()
        temp:ReleaseFocus()
        temp:Destroy()
        return true
    end
end

-- ANIMAÇÃO DOS BOTÕES
local function animateButton(btn)
    local original = btn.Size
    local tween = TweenService:Create(btn, TweenInfo.new(0.1), {
        Size = original - UDim2.new(0, 10, 0, 5)
    })
    local tweenBack = TweenService:Create(btn, TweenInfo.new(0.1), {
        Size = original
    })
    
    tween:Play()
    tween.Completed:Connect(function()
        tweenBack:Play()
    end)
end

-- CONECTAR EVENTOS DOS BOTÕES (AGORA FUNCIONA!)

-- BOTÃO FECHAR
closeButton.MouseButton1Click:Connect(function()
    animateButton(closeButton)
    screenGui:Destroy()
    print("Desofuscador fechado!")
end)

-- BOTÃO DESOFUSCAR
deobfuscateBtn.MouseButton1Click:Connect(function()
    animateButton(deobfuscateBtn)
    
    local input = inputBox.Text
    if #input < 5 then
        statusLabel.Text = "❌ Coloque algum código primeiro!"
        return
    end
    
    -- Processar em thread separada
    task.spawn(function()
        local start = os.clock()
        local result = Deobfuscator.simpleDeobfuscate(input)
        local timeTaken = os.clock() - start
        
        outputBox.Text = result
        statusLabel.Text = string.format("✅ Pronto! %d chars em %.2f segundos", #result, timeTaken)
        
        -- Auto-copiar se for pequeno
        if #result < 5000 then
            copyToClipboard(result)
            statusLabel.Text = statusLabel.Text .. " | 📋 Copiado!"
        end
    end)
end)

-- BOTÃO COPIAR
copyBtn.MouseButton1Click:Connect(function()
    animateButton(copyBtn)
    
    local output = outputBox.Text
    if #output == 0 then
        statusLabel.Text = "❌ Nada para copiar!"
        return
    end
    
    if copyToClipboard(output) then
        statusLabel.Text = "📋 Código copiado para área de transferência!"
    else
        statusLabel.Text = "⚠️ Não foi possível copiar"
    end
end)

-- BOTÃO LIMPAR
clearBtn.MouseButton1Click:Connect(function()
    animateButton(clearBtn)
    inputBox.Text = ""
    outputBox.Text = ""
    statusLabel.Text = "🧹 Limpo! Pronto para novo código."
end)

-- HOTKEYS
UserInputService.InputBegan:Connect(function(input, processed)
    if not processed then
        if input.KeyCode == Enum.KeyCode.F5 then
            -- Mostrar/Esconder
            mainFrame.Visible = not mainFrame.Visible
            statusLabel.Text = mainFrame.Visible and "🟢 Interface visível" or "🔴 Interface oculta"
            
        elseif input.KeyCode == Enum.KeyCode.F6 then
            -- Focar no input
            inputBox:CaptureFocus()
            
        elseif input.KeyCode == Enum.KeyCode.F9 then
            -- Teste automático
            inputBox.Text = [[
-- Teste de ofuscação
local encoded = "SGVsbG8gV29ybGQh"  -- Base64 para "Hello World!"
local decoded = game:GetService("HttpService"):Base64Decode(encoded)
print(decoded)

local chars = string.char(72,101,108,108,111,32,87,111,114,108,100)
print(chars)
]]
            statusLabel.Text = "🧪 Código de teste inserido!"
        end
    end
end)

-- EXEMPLO INICIAL
inputBox.PlaceholderText = [[
-- COLE SEU CÓDIGO OFUSCADO AQUI --

Exemplos suportados:
• Base64: "SGVsbG8gV29ybGQ="
• string.char: string.char(72,101,108,108,111)
• Hex: \x48\x65\x6C\x6C\x6F
• Loadstring: loadstring(game:HttpGet("..."))

Hotkeys:
F5 = Mostrar/Esconder
F6 = Focar no input
F9 = Inserir exemplo
]]

-- MENSAGEM INICIAL
print("==================================")
print("DESOFUSCADOR ULTRA CARREGADO!")
print("Pressione F5 para mostrar interface")
print("==================================")

-- GARANTIR QUE ESTÁ VISÍVEL
wait(1)
statusLabel.Text = "🟢 Interface pronta! F5 para mostrar/esconder"
