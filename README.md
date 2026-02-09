-- LocalScript: Desofuscador Universal para Roblox
-- Coloque em StarterGui ou ScreenGui

local Players = game:GetService("Players")
local Player = Players.LocalPlayer
local Mouse = Player:GetMouse()
local UserInputService = game:GetService("UserInputService")
local HttpService = game:GetService("HttpService")
local TweenService = game:GetService("TweenService")
local RunService = game:GetService("RunService")

-- Criar a Interface
local ScreenGui = Instance.new("ScreenGui")
ScreenGui.Name = "DeobfuscatorGUI"
ScreenGui.Parent = Player:WaitForChild("PlayerGui")

local MainFrame = Instance.new("Frame")
MainFrame.Name = "MainFrame"
MainFrame.Size = UDim2.new(0, 500, 0, 600)
MainFrame.Position = UDim2.new(0.5, -250, 0.5, -300)
MainFrame.BackgroundColor3 = Color3.fromRGB(25, 25, 35)
MainFrame.BorderSizePixel = 0
MainFrame.Active = true
MainFrame.Draggable = true
MainFrame.Parent = ScreenGui

-- Sombras
local UIStroke = Instance.new("UIStroke")
UIStroke.Thickness = 2
UIStroke.Color = Color3.fromRGB(60, 60, 80)
UIStroke.Parent = MainFrame

local UICorner = Instance.new("UICorner")
UICorner.CornerRadius = UDim.new(0, 8)
UICorner.Parent = MainFrame

-- Barra de Título
local TitleBar = Instance.new("Frame")
TitleBar.Name = "TitleBar"
TitleBar.Size = UDim2.new(1, 0, 0, 40)
TitleBar.BackgroundColor3 = Color3.fromRGB(35, 35, 45)
TitleBar.BorderSizePixel = 0
TitleBar.Parent = MainFrame

local TitleLabel = Instance.new("TextLabel")
TitleLabel.Name = "TitleLabel"
TitleLabel.Size = UDim2.new(0.8, 0, 1, 0)
TitleLabel.Position = UDim2.new(0, 10, 0, 0)
TitleLabel.BackgroundTransparency = 1
TitleLabel.TextColor3 = Color3.fromRGB(220, 220, 255)
TitleLabel.Text = "🧬 Deobfuscator Pro v2.0"
TitleLabel.TextSize = 18
TitleLabel.Font = Enum.Font.GothamBold
TitleLabel.TextXAlignment = Enum.TextXAlignment.Left
TitleLabel.Parent = TitleBar

local CloseButton = Instance.new("TextButton")
CloseButton.Name = "CloseButton"
CloseButton.Size = UDim2.new(0, 30, 0, 30)
CloseButton.Position = UDim2.new(1, -35, 0, 5)
CloseButton.BackgroundColor3 = Color3.fromRGB(255, 60, 60)
CloseButton.TextColor3 = Color3.new(1, 1, 1)
CloseButton.Text = "X"
CloseButton.TextSize = 14
CloseButton.Font = Enum.Font.GothamBold
CloseButton.Parent = TitleBar

local UICorner2 = Instance.new("UICorner")
UICorner2.CornerRadius = UDim.new(0, 6)
UICorner2.Parent = CloseButton

-- Área de Input
local InputFrame = Instance.new("Frame")
InputFrame.Name = "InputFrame"
InputFrame.Size = UDim2.new(1, -20, 0, 200)
InputFrame.Position = UDim2.new(0, 10, 0, 50)
InputFrame.BackgroundColor3 = Color3.fromRGB(30, 30, 40)
InputFrame.BorderSizePixel = 0
InputFrame.Parent = MainFrame

local InputLabel = Instance.new("TextLabel")
InputLabel.Name = "InputLabel"
InputLabel.Size = UDim2.new(1, 0, 0, 30)
InputLabel.BackgroundTransparency = 1
InputLabel.TextColor3 = Color3.fromRGB(180, 180, 220)
InputLabel.Text = "📥 CÓDIGO OFUSCADO:"
InputLabel.TextSize = 14
InputLabel.Font = Enum.Font.Gotham
InputLabel.TextXAlignment = Enum.TextXAlignment.Left
InputLabel.Parent = InputFrame

local InputTextBox = Instance.new("TextBox")
InputTextBox.Name = "InputTextBox"
InputTextBox.Size = UDim2.new(1, -10, 1, -40)
InputTextBox.Position = UDim2.new(0, 5, 0, 35)
InputTextBox.BackgroundColor3 = Color3.fromRGB(20, 20, 25)
InputTextBox.TextColor3 = Color3.fromRGB(220, 220, 255)
InputTextBox.Text = ""
InputTextBox.PlaceholderText = "Cole seu código ofuscado aqui..."
InputTextBox.TextSize = 12
InputTextBox.Font = Enum.Font.Code
InputTextBox.TextXAlignment = Enum.TextXAlignment.Left
InputTextBox.TextYAlignment = Enum.TextYAlignment.Top
InputTextBox.ClearTextOnFocus = false
InputTextBox.MultiLine = true
InputTextBox.TextWrapped = true
InputTextBox.ScrollingEnabled = true
InputTextBox.Parent = InputFrame

local UICorner3 = Instance.new("UICorner")
UICorner3.CornerRadius = UDim.new(0, 6)
UICorner3.Parent = InputTextBox

-- Área de Output
local OutputFrame = Instance.new("Frame")
OutputFrame.Name = "OutputFrame"
OutputFrame.Size = UDim2.new(1, -20, 0, 200)
OutputFrame.Position = UDim2.new(0, 10, 0, 340)
OutputFrame.BackgroundColor3 = Color3.fromRGB(30, 30, 40)
OutputFrame.BorderSizePixel = 0
OutputFrame.Parent = MainFrame

local OutputLabel = Instance.new("TextLabel")
OutputLabel.Name = "OutputLabel"
OutputLabel.Size = UDim2.new(1, 0, 0, 30)
OutputLabel.BackgroundTransparency = 1
OutputLabel.TextColor3 = Color3.fromRGB(180, 220, 180)
OutputLabel.Text = "📤 CÓDIGO DESOFUSCADO:"
OutputLabel.TextSize = 14
OutputLabel.Font = Enum.Font.Gotham
OutputLabel.TextXAlignment = Enum.TextXAlignment.Left
OutputLabel.Parent = OutputFrame

local OutputTextBox = Instance.new("TextBox")
OutputTextBox.Name = "OutputTextBox"
OutputTextBox.Size = UDim2.new(1, -10, 1, -40)
OutputTextBox.Position = UDim2.new(0, 5, 0, 35)
OutputTextBox.BackgroundColor3 = Color3.fromRGB(20, 25, 20)
OutputTextBox.TextColor3 = Color3.fromRGB(180, 255, 180)
OutputTextBox.Text = ""
OutputTextBox.TextSize = 12
OutputTextBox.Font = Enum.Font.Code
OutputTextBox.TextXAlignment = Enum.TextXAlignment.Left
OutputTextBox.TextYAlignment = Enum.TextYAlignment.Top
OutputTextBox.ClearTextOnFocus = false
OutputTextBox.MultiLine = true
OutputTextBox.TextWrapped = true
OutputTextBox.ScrollingEnabled = true
OutputTextBox.Parent = OutputFrame

local UICorner4 = Instance.new("UICorner")
UICorner4.CornerRadius = UDim.new(0, 6)
UICorner4.Parent = OutputTextBox

-- Botões
local ButtonFrame = Instance.new("Frame")
ButtonFrame.Name = "ButtonFrame"
ButtonFrame.Size = UDim2.new(1, -20, 0, 50)
ButtonFrame.Position = UDim2.new(0, 10, 0, 260)
ButtonFrame.BackgroundTransparency = 1
ButtonFrame.Parent = MainFrame

local DeobfuscateButton = Instance.new("TextButton")
DeobfuscateButton.Name = "DeobfuscateButton"
DeobfuscateButton.Size = UDim2.new(0.48, 0, 1, 0)
DeobfuscateButton.Position = UDim2.new(0, 0, 0, 0)
DeobfuscateButton.BackgroundColor3 = Color3.fromRGB(80, 120, 255)
DeobfuscateButton.TextColor3 = Color3.new(1, 1, 1)
DeobfuscateButton.Text = "🚀 DESOFUSCAR"
DeobfuscateButton.TextSize = 14
DeobfuscateButton.Font = Enum.Font.GothamBold
DeobfuscateButton.Parent = ButtonFrame

local CopyButton = Instance.new("TextButton")
CopyButton.Name = "CopyButton"
CopyButton.Size = UDim2.new(0.48, 0, 1, 0)
CopyButton.Position = UDim2.new(0.52, 0, 0, 0)
CopyButton.BackgroundColor3 = Color3.fromRGB(60, 180, 100)
CopyButton.TextColor3 = Color3.new(1, 1, 1)
CopyButton.Text = "📋 COPIAR TUDO"
CopyButton.TextSize = 14
CopyButton.Font = Enum.Font.GothamBold
CopyButton.Parent = ButtonFrame

local UICorner5 = Instance.new("UICorner")
UICorner5.CornerRadius = UDim.new(0, 8)
UICorner5.Parent = DeobfuscateButton

local UICorner6 = Instance.new("UICorner")
UICorner6.CornerRadius = UDim.new(0, 8)
UICorner6.Parent = CopyButton

-- Status Label
local StatusLabel = Instance.new("TextLabel")
StatusLabel.Name = "StatusLabel"
StatusLabel.Size = UDim2.new(1, -20, 0, 30)
StatusLabel.Position = UDim2.new(0, 10, 0, 550)
StatusLabel.BackgroundTransparency = 1
StatusLabel.TextColor3 = Color3.fromRGB(200, 200, 220)
StatusLabel.Text = "Pronto para desofuscar..."
StatusLabel.TextSize = 12
StatusLabel.Font = Enum.Font.Gotham
StatusLabel.Parent = MainFrame

-- Funções de Desofuscação
local Deobfuscator = {}

function Deobfuscator.decodeBase64(str)
    local success, result = pcall(function()
        return HttpService:JSONDecode(game:GetService("HttpService"):Base64Decode(str))
    end)
    return success and result or nil
end

function Deobfuscator.decodeStringChar(code)
    -- Decodifica padrões string.char(65,66,67)
    local pattern = "string%.char%(([^)]+)%)"
    
    local function replace(match)
        local numbers = {}
        for num in string.gmatch(match, "%d+") do
            table.insert(numbers, tonumber(num))
        end
        
        local chars = ""
        for _, num in ipairs(numbers) do
            chars = chars .. string.char(num)
        end
        
        return '"' .. chars .. '"'
    end
    
    local decoded = string.gsub(code, pattern, replace)
    return decoded
end

function Deobfuscator.extractURLs(code)
    local urls = {}
    local patterns = {
        'game:HttpGet%(["\']([^"\']+)["\']%)',
        'HttpGet%(["\']([^"\']+)["\']%)',
        '["\'](https?://[^"\']+)["\']'
    }
    
    for _, pattern in ipairs(patterns) do
        for url in string.gmatch(code, pattern) do
            table.insert(urls, url)
        end
    end
    
    return urls
end

function Deobfuscator.cleanVariables(code)
    -- Remove variáveis intermediárias desnecessárias
    local lines = {}
    for line in string.gmatch(code .. "\n", "(.-)\n") do
        -- Remove linhas como: local a = "b"; local c = a;
        if not string.match(line, "^local%s+%w+%s*=%s*%w+%s*$") then
            table.insert(lines, line)
        end
    end
    return table.concat(lines, "\n")
end

function Deobfuscator.decodeHex(code)
    -- Decodifica \x48\x65\x6C\x6C\x6F
    local function hexToChar(hex)
        return string.char(tonumber(hex, 16))
    end
    
    local decoded = string.gsub(code, "\\x(%x%x)", hexToChar)
    return decoded
end

function Deobfuscator.decodeUnicode(code)
    -- Decodifica \u0048\u0065\u006C\u006C\u006F
    local function uniToChar(uni)
        return utf8.char(tonumber(uni, 16))
    end
    
    local decoded = string.gsub(code, "\\u(%x%x%x%x)", uniToChar)
    return decoded
end

function Deobfuscator.findLoadstrings(code)
    -- Encontra e avalia loadstrings simples
    local loadstringPattern = 'loadstring%(["\']([^"\']+)["\']%)'
    
    local function evaluate(match)
        local success, result = pcall(loadstring, match)
        if success then
            return tostring(result)
        end
        return match
    end
    
    return string.gsub(code, loadstringPattern, evaluate)
end

function Deobfuscator.removeGarbage(code)
    -- Remove comentários e espaços extras
    code = string.gsub(code, "%-%-[^\n]*", "") -- Remove comentários de linha
    code = string.gsub(code, "%s+", " ") -- Remove espaços múltiplos
    code = string.gsub(code, "^%s+", "") -- Remove espaços no início
    code = string.gsub(code, "%s+$", "") -- Remove espaços no final
    return code
end

function Deobfuscator.beautify(code)
    -- Formata o código para melhor legibilidade
    local indent = 0
    local lines = {}
    local inString = false
    local stringChar = ""
    
    for line in string.gmatch(code .. "\n", "(.-)\n") do
        -- Controle de indentação
        local trimmed = string.match(line, "^%s*(.*)%s*$")
        
        if string.find(trimmed, "end$") or string.find(trimmed, "else$") or string.find(trimmed, "elseif") then
            indent = math.max(0, indent - 1)
        end
        
        local indentedLine = string.rep("    ", indent) .. trimmed
        table.insert(lines, indentedLine)
        
        if string.find(trimmed, "function%s") or string.find(trimmed, "if%s") or string.find(trimmed, "for%s") or string.find(trimmed, "while%s") then
            if not string.find(trimmed, "end$") then
                indent = indent + 1
            end
        end
    end
    
    return table.concat(lines, "\n")
end

function Deobfuscator.fullDeobfuscation(code)
    StatusLabel.Text = "🔍 Analisando código..."
    wait()
    
    -- Etapa 1: Decodificação básica
    StatusLabel.Text = "🔄 Decodificando Base64..."
    wait()
    
    -- Tentar decodificar como Base64 primeiro
    local success, base64decoded = pcall(function()
        return HttpService:Base64Decode(code)
    end)
    
    if success and #base64decoded > 0 then
        code = base64decoded
    end
    
    -- Etapa 2: Decodificar string.char()
    StatusLabel.Text = "🔤 Processando string.char()..."
    wait()
    code = Deobfuscator.decodeStringChar(code)
    
    -- Etapa 3: Decodificar hex/unicode
    StatusLabel.Text = "🔢 Decodificando hex/unicode..."
    wait()
    code = Deobfuscator.decodeHex(code)
    code = Deobfuscator.decodeUnicode(code)
    
    -- Etapa 4: Processar loadstrings
    StatusLabel.Text = "🔄 Avaliando loadstrings..."
    wait()
    code = Deobfuscator.findLoadstrings(code)
    
    -- Etapa 5: Extrair URLs
    StatusLabel.Text = "🌐 Extraindo URLs..."
    wait()
    local urls = Deobfuscator.extractURLs(code)
    if #urls > 0 then
        StatusLabel.Text = "📡 " .. #urls .. " URLs encontradas"
    end
    
    -- Etapa 6: Limpar variáveis
    StatusLabel.Text = "🧹 Limpando variáveis..."
    wait()
    code = Deobfuscator.cleanVariables(code)
    
    -- Etapa 7: Remover lixo
    StatusLabel.Text = "✨ Removendo comentários..."
    wait()
    code = Deobfuscator.removeGarbage(code)
    
    -- Etapa 8: Formatar
    StatusLabel.Text = "🎨 Formatando código..."
    wait()
    code = Deobfuscator.beautify(code)
    
    StatusLabel.Text = "✅ Desofuscação completa!"
    
    return code
end

-- Configurar Clipboard (funcionalidade de copiar)
local function setClipboard(text)
    -- Método 1: Usar SetClipboard se disponível
    if setclipboard then
        setclipboard(text)
        return true
    end
    
    -- Método 2: Usar API do Roblox se disponível
    if UserInputService.SetClipboard then
        UserInputService:SetClipboard(text)
        return true
    end
    
    -- Método 3: Fallback para TextBox
    local tempBox = Instance.new("TextBox")
    tempBox.Text = text
    tempBox.Parent = ScreenGui
    tempBox:CaptureFocus()
    tempBox:SelectAll()
    tempBox:ReleaseFocus()
    tempBox:Destroy()
    
    return true
end

-- Funções de UI
local function animateButton(button)
    local originalSize = button.Size
    local tweenInfo = TweenInfo.new(0.1, Enum.EasingStyle.Quad, Enum.EasingDirection.Out)
    
    local tween1 = TweenService:Create(button, tweenInfo, {Size = originalSize - UDim2.new(0, 10, 0, 5)})
    local tween2 = TweenService:Create(button, tweenInfo, {Size = originalSize})
    
    tween1:Play()
    tween1.Completed:Connect(function()
        tween2:Play()
    end)
end

local function showNotification(message, color)
    StatusLabel.TextColor3 = color or Color3.fromRGB(220, 220, 255)
    StatusLabel.Text = message
    
    -- Reset após 3 segundos
    delay(3, function()
        if StatusLabel.Text == message then
            StatusLabel.Text = "Pronto para desofuscar..."
            StatusLabel.TextColor3 = Color3.fromRGB(200, 200, 220)
        end
    end)
end

-- Conectar Eventos
CloseButton.MouseButton1Click:Connect(function()
    ScreenGui:Destroy()
end)

DeobfuscateButton.MouseButton1Click:Connect(function()
    animateButton(DeobfuscateButton)
    
    local inputCode = InputTextBox.Text
    if #inputCode < 10 then
        showNotification("❌ Código muito curto!", Color3.fromRGB(255, 100, 100))
        return
    end
    
    -- Executar em thread separada para não travar
    spawn(function()
        local startTime = tick()
        
        local success, result = pcall(function()
            return Deobfuscator.fullDeobfuscation(inputCode)
        end)
        
        local elapsedTime = tick() - startTime
        
        if success then
            OutputTextBox.Text = result
            showNotification(string.format("✅ Desofuscado em %.2f segundos | %d caracteres", elapsedTime, #result), Color3.fromRGB(100, 255, 100))
            
            -- Auto-copiar se for pequeno
            if #result < 10000 then
                setClipboard(result)
                showNotification("📋 Auto-copiado para clipboard!", Color3.fromRGB(100, 200, 255))
            end
        else
            showNotification("❌ Erro: " .. tostring(result):sub(1, 100), Color3.fromRGB(255, 100, 100))
        end
    end)
end)

CopyButton.MouseButton1Click:Connect(function()
    animateButton(CopyButton)
    
    local outputCode = OutputTextBox.Text
    if #outputCode == 0 then
        showNotification("❌ Nada para copiar!", Color3.fromRGB(255, 100, 100))
        return
    end
    
    if setClipboard(outputCode) then
        showNotification("📋 Código copiado para clipboard!", Color3.fromRGB(100, 255, 100))
    else
        showNotification("⚠️ Não foi possível copiar automaticamente", Color3.fromRGB(255, 200, 100))
    end
end)

-- Hotkey para abrir/fechar
UserInputService.InputBegan:Connect(function(input, processed)
    if not processed then
        if input.KeyCode == Enum.KeyCode.F7 then
            ScreenGui.Enabled = not ScreenGui.Enabled
        elseif input.KeyCode == Enum.KeyCode.F8 then
            -- Auto-focus na input box
            InputTextBox:CaptureFocus()
        end
    end
end)

-- Tooltip para botões
local function addTooltip(button, text)
    local tooltip = Instance.new("TextLabel")
    tooltip.Name = "Tooltip"
    tooltip.Size = UDim2.new(0, 200, 0, 30)
    tooltip.Position = UDim2.new(0.5, -100, 1, 5)
    tooltip.BackgroundColor3 = Color3.fromRGB(40, 40, 50)
    tooltip.TextColor3 = Color3.new(1, 1, 1)
    tooltip.Text = text
    tooltip.TextSize = 12
    tooltip.Visible = false
    tooltip.Parent = button
    
    local uic = Instance.new("UICorner")
    uic.CornerRadius = UDim.new(0, 4)
    uic.Parent = tooltip
    
    button.MouseEnter:Connect(function()
        tooltip.Visible = true
    end)
    
    button.MouseLeave:Connect(function()
        tooltip.Visible = false
    end)
end

addTooltip(DeobfuscateButton, "Desofusca Base64, string.char(), hex, unicode, loadstrings")
addTooltip(CopyButton, "Copia o código desofuscado para a área de transferência")
addTooltip(CloseButton, "Fecha a interface (F7 para reabrir)")

-- Exemplo de código ofuscado para teste
InputTextBox.PlaceholderText = [[
-- Cole seu código ofuscado aqui...
-- Exemplo:
local a = string.char(72,101,108,108,111,32,87,111,114,108,100,33)
print(a)

-- Ou Base64:
local b = "SGVsbG8gV29ybGQh"
local c = game:HttpGet("https://example.com/script.lua")
]]

-- Status inicial
showNotification("✅ Desofuscador carregado! Pressione F7 para mostrar/esconder", Color3.fromRGB(100, 255, 100))

print("Desofuscador Universal carregado!")
print("Hotkeys: F7 = Mostrar/Esconder | F8 = Focar na input box")
