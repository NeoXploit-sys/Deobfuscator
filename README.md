--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 146 | Scripts: 21 | Modules: 0 | Tags: 0
local G2L = {};

-- StarterGui.BABFT.SagittariusHubBABFT
G2L["1"] = Instance.new("ScreenGui", gethui());
G2L["1"]["IgnoreGuiInset"] = true;
G2L["1"]["Name"] = [[SagittariusHubBABFT]];
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround
G2L["2"] = Instance.new("ImageLabel", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2"]["ImageTransparency"] = 0.12;
G2L["2"]["ImageColor3"] = Color3.fromRGB(62, 62, 62);
G2L["2"]["Image"] = [[rbxassetid://80936186679829]];
G2L["2"]["Size"] = UDim2.new(0, 550, 0, 309);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["BackgroundTransparency"] = 1;
G2L["2"]["Name"] = [[BackGround]];
G2L["2"]["Position"] = UDim2.new(0.22309, 0, 0.16865, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.UICorner
G2L["3"] = Instance.new("UICorner", G2L["2"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.TextLabel
G2L["4"] = Instance.new("TextLabel", G2L["2"]);
G2L["4"]["TextWrapped"] = true;
G2L["4"]["BorderSizePixel"] = 0;
G2L["4"]["TextSize"] = 14;
G2L["4"]["TextScaled"] = true;
G2L["4"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4"]["BackgroundTransparency"] = 1;
G2L["4"]["Size"] = UDim2.new(0, 362, 0, 29);
G2L["4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4"]["Text"] = [[Sagittarius Hub | Build a Boat For Treasure]];
G2L["4"]["Position"] = UDim2.new(0.17091, 0, 0.00324, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.TextLabel.ImageLabel
G2L["5"] = Instance.new("ImageLabel", G2L["4"]);
G2L["5"]["BorderSizePixel"] = 0;
G2L["5"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5"]["Image"] = [[rbxassetid://129737406374971]];
G2L["5"]["Size"] = UDim2.new(0, 63, 0, 50);
G2L["5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5"]["BackgroundTransparency"] = 1;
G2L["5"]["Position"] = UDim2.new(-0.29183, 0, -0.39472, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages
G2L["6"] = Instance.new("Frame", G2L["2"]);
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6"]["Size"] = UDim2.new(0, 456, 0, 277);
G2L["6"]["Position"] = UDim2.new(0.17091, 0, 0.10032, 0);
G2L["6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["Name"] = [[Pages]];
G2L["6"]["BackgroundTransparency"] = 1;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Home
G2L["7"] = Instance.new("Frame", G2L["6"]);
G2L["7"]["Visible"] = false;
G2L["7"]["BorderSizePixel"] = 0;
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7"]["Size"] = UDim2.new(0, 456, 0, 277);
G2L["7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["Name"] = [[Home]];
G2L["7"]["BackgroundTransparency"] = 1;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Home.List
G2L["8"] = Instance.new("ScrollingFrame", G2L["7"]);
G2L["8"]["Active"] = true;
G2L["8"]["BorderSizePixel"] = 0;
G2L["8"]["Name"] = [[List]];
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8"]["Size"] = UDim2.new(0, 456, 0, 277);
G2L["8"]["ScrollBarImageColor3"] = Color3.fromRGB(108, 108, 108);
G2L["8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8"]["BackgroundTransparency"] = 1;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Home.List.UIListLayout
G2L["9"] = Instance.new("UIListLayout", G2L["8"]);
G2L["9"]["Padding"] = UDim.new(0, 10);
G2L["9"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Home.List.DCLink
G2L["a"] = Instance.new("TextButton", G2L["8"]);
G2L["a"]["TextWrapped"] = true;
G2L["a"]["BorderSizePixel"] = 0;
G2L["a"]["TextSize"] = 14;
G2L["a"]["TextScaled"] = true;
G2L["a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a"]["BackgroundTransparency"] = 1;
G2L["a"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a"]["Text"] = [[Discord Link]];
G2L["a"]["Name"] = [[DCLink]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Home.List.DCLink.UICorner
G2L["b"] = Instance.new("UICorner", G2L["a"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Home.List.DCLink.UIStroke
G2L["c"] = Instance.new("UIStroke", G2L["a"]);
G2L["c"]["Thickness"] = 2;
G2L["c"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Home.List.IY
G2L["d"] = Instance.new("TextButton", G2L["8"]);
G2L["d"]["TextWrapped"] = true;
G2L["d"]["BorderSizePixel"] = 0;
G2L["d"]["TextSize"] = 14;
G2L["d"]["TextScaled"] = true;
G2L["d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["d"]["BackgroundTransparency"] = 1;
G2L["d"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d"]["Text"] = [[IY]];
G2L["d"]["Name"] = [[IY]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Home.List.IY.LocalScript
G2L["e"] = Instance.new("LocalScript", G2L["d"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Home.List.IY.UICorner
G2L["f"] = Instance.new("UICorner", G2L["d"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Home.List.IY.UIStroke
G2L["10"] = Instance.new("UIStroke", G2L["d"]);
G2L["10"]["Thickness"] = 2;
G2L["10"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["10"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Farm
G2L["11"] = Instance.new("Frame", G2L["6"]);
G2L["11"]["BorderSizePixel"] = 0;
G2L["11"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["11"]["Size"] = UDim2.new(0, 456, 0, 277);
G2L["11"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["Name"] = [[Farm]];
G2L["11"]["BackgroundTransparency"] = 1;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Farm.List
G2L["12"] = Instance.new("ScrollingFrame", G2L["11"]);
G2L["12"]["Active"] = true;
G2L["12"]["BorderSizePixel"] = 0;
G2L["12"]["Name"] = [[List]];
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["12"]["Size"] = UDim2.new(0, 456, 0, 277);
G2L["12"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["BackgroundTransparency"] = 1;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Farm.List.UIListLayout
G2L["13"] = Instance.new("UIListLayout", G2L["12"]);
G2L["13"]["Padding"] = UDim.new(0, 10);
G2L["13"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Farm.List.AutoReedem
G2L["14"] = Instance.new("TextButton", G2L["12"]);
G2L["14"]["TextWrapped"] = true;
G2L["14"]["BorderSizePixel"] = 0;
G2L["14"]["TextSize"] = 14;
G2L["14"]["TextScaled"] = true;
G2L["14"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["14"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["14"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["14"]["BackgroundTransparency"] = 1;
G2L["14"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["14"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["14"]["Text"] = [[Auto-Reedem]];
G2L["14"]["Name"] = [[AutoReedem]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Farm.List.AutoReedem.UICorner
G2L["15"] = Instance.new("UICorner", G2L["14"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Farm.List.AutoReedem.UIStroke
G2L["16"] = Instance.new("UIStroke", G2L["14"]);
G2L["16"]["Thickness"] = 2;
G2L["16"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["16"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Farm.List.AutoReedem.TextButton
G2L["17"] = Instance.new("TextButton", G2L["14"]);
G2L["17"]["BorderSizePixel"] = 0;
G2L["17"]["TextSize"] = 14;
G2L["17"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["17"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
G2L["17"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["17"]["Size"] = UDim2.new(0, 37, 0, 33);
G2L["17"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["17"]["Text"] = [[]];
G2L["17"]["Position"] = UDim2.new(0.89066, 0, 0, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Farm.List.AutoReedem.TextButton.LocalScript
G2L["18"] = Instance.new("LocalScript", G2L["17"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Farm.List.AutoReedem.TextButton.UICorner
G2L["19"] = Instance.new("UICorner", G2L["17"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Farm.List.AutoReedem.TextButton.UIStroke
G2L["1a"] = Instance.new("UIStroke", G2L["17"]);
G2L["1a"]["Thickness"] = 2;
G2L["1a"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["1a"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Farm.List.AutoFarm
G2L["1b"] = Instance.new("TextButton", G2L["12"]);
G2L["1b"]["TextWrapped"] = true;
G2L["1b"]["BorderSizePixel"] = 0;
G2L["1b"]["TextSize"] = 14;
G2L["1b"]["TextScaled"] = true;
G2L["1b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1b"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["1b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1b"]["BackgroundTransparency"] = 1;
G2L["1b"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["1b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1b"]["Text"] = [[Auto-Farm]];
G2L["1b"]["Name"] = [[AutoFarm]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Farm.List.AutoFarm.UICorner
G2L["1c"] = Instance.new("UICorner", G2L["1b"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Farm.List.AutoFarm.UIStroke
G2L["1d"] = Instance.new("UIStroke", G2L["1b"]);
G2L["1d"]["Thickness"] = 2;
G2L["1d"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["1d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Farm.List.AutoFarm.TextButton
G2L["1e"] = Instance.new("TextButton", G2L["1b"]);
G2L["1e"]["BorderSizePixel"] = 0;
G2L["1e"]["TextSize"] = 14;
G2L["1e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1e"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
G2L["1e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1e"]["Size"] = UDim2.new(0, 37, 0, 34);
G2L["1e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["Text"] = [[]];
G2L["1e"]["Position"] = UDim2.new(0.89066, 0, -0.0303, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Farm.List.AutoFarm.TextButton.LocalScript
G2L["1f"] = Instance.new("LocalScript", G2L["1e"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Farm.List.AutoFarm.TextButton.UICorner
G2L["20"] = Instance.new("UICorner", G2L["1e"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Farm.List.AutoFarm.TextButton.UIStroke
G2L["21"] = Instance.new("UIStroke", G2L["1e"]);
G2L["21"]["Thickness"] = 2;
G2L["21"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["21"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Scripts
G2L["22"] = Instance.new("Frame", G2L["6"]);
G2L["22"]["Visible"] = false;
G2L["22"]["BorderSizePixel"] = 0;
G2L["22"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["22"]["Size"] = UDim2.new(0, 456, 0, 277);
G2L["22"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["22"]["Name"] = [[Scripts]];
G2L["22"]["BackgroundTransparency"] = 1;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Scripts.ScrollingFrame
G2L["23"] = Instance.new("ScrollingFrame", G2L["22"]);
G2L["23"]["Active"] = true;
G2L["23"]["BorderSizePixel"] = 0;
G2L["23"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["23"]["Size"] = UDim2.new(0, 456, 0, 277);
G2L["23"]["ScrollBarImageColor3"] = Color3.fromRGB(108, 108, 108);
G2L["23"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["23"]["BackgroundTransparency"] = 1;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Scripts.ScrollingFrame.UIListLayout
G2L["24"] = Instance.new("UIListLayout", G2L["23"]);
G2L["24"]["Padding"] = UDim.new(0, 10);
G2L["24"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Scripts.ScrollingFrame.
G2L["25"] = Instance.new("TextButton", G2L["23"]);
G2L["25"]["TextWrapped"] = true;
G2L["25"]["BorderSizePixel"] = 0;
G2L["25"]["TextSize"] = 14;
G2L["25"]["TextScaled"] = true;
G2L["25"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["25"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["25"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["25"]["BackgroundTransparency"] = 1;
G2L["25"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["25"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["25"]["Text"] = [[Fly]];
G2L["25"]["Name"] = [[]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Scripts.ScrollingFrame..UICorner
G2L["26"] = Instance.new("UICorner", G2L["25"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Scripts.ScrollingFrame..UIStroke
G2L["27"] = Instance.new("UIStroke", G2L["25"]);
G2L["27"]["Thickness"] = 2;
G2L["27"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["27"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Scripts.ScrollingFrame.TextButton
G2L["28"] = Instance.new("TextButton", G2L["23"]);
G2L["28"]["TextWrapped"] = true;
G2L["28"]["BorderSizePixel"] = 0;
G2L["28"]["TextSize"] = 14;
G2L["28"]["TextScaled"] = true;
G2L["28"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["28"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["28"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["28"]["BackgroundTransparency"] = 1;
G2L["28"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["28"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["28"]["Text"] = [[Anti-AFK]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Scripts.ScrollingFrame.TextButton.UICorner
G2L["29"] = Instance.new("UICorner", G2L["28"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Scripts.ScrollingFrame.TextButton.UIStroke
G2L["2a"] = Instance.new("UIStroke", G2L["28"]);
G2L["2a"]["Thickness"] = 2;
G2L["2a"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["2a"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Scripts.ScrollingFrame.TextButton
G2L["2b"] = Instance.new("TextButton", G2L["23"]);
G2L["2b"]["TextWrapped"] = true;
G2L["2b"]["BorderSizePixel"] = 0;
G2L["2b"]["TextSize"] = 14;
G2L["2b"]["TextScaled"] = true;
G2L["2b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2b"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["2b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2b"]["BackgroundTransparency"] = 1;
G2L["2b"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["2b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2b"]["Text"] = [[Black Hole]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Scripts.ScrollingFrame.TextButton.UICorner
G2L["2c"] = Instance.new("UICorner", G2L["2b"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Scripts.ScrollingFrame.TextButton.UIStroke
G2L["2d"] = Instance.new("UIStroke", G2L["2b"]);
G2L["2d"]["Thickness"] = 2;
G2L["2d"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["2d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Scripts.ScrollingFrame.TextButton
G2L["2e"] = Instance.new("TextButton", G2L["23"]);
G2L["2e"]["TextWrapped"] = true;
G2L["2e"]["BorderSizePixel"] = 0;
G2L["2e"]["TextSize"] = 14;
G2L["2e"]["TextScaled"] = true;
G2L["2e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2e"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["2e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2e"]["BackgroundTransparency"] = 1;
G2L["2e"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["2e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2e"]["Text"] = [[Super Ring Parts]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Scripts.ScrollingFrame.TextButton.UICorner
G2L["2f"] = Instance.new("UICorner", G2L["2e"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Scripts.ScrollingFrame.TextButton.UIStroke
G2L["30"] = Instance.new("UIStroke", G2L["2e"]);
G2L["30"]["Thickness"] = 2;
G2L["30"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["30"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.AutoBuy
G2L["31"] = Instance.new("Frame", G2L["6"]);
G2L["31"]["Visible"] = false;
G2L["31"]["BorderSizePixel"] = 0;
G2L["31"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["31"]["Size"] = UDim2.new(0, 456, 0, 277);
G2L["31"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["31"]["Name"] = [[AutoBuy]];
G2L["31"]["BackgroundTransparency"] = 1;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.AutoBuy.ScrollingFrame
G2L["32"] = Instance.new("ScrollingFrame", G2L["31"]);
G2L["32"]["Active"] = true;
G2L["32"]["BorderSizePixel"] = 0;
G2L["32"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["32"]["Size"] = UDim2.new(0, 456, 0, 277);
G2L["32"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["32"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["32"]["BackgroundTransparency"] = 1;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.AutoBuy.ScrollingFrame.TextButton
G2L["33"] = Instance.new("TextButton", G2L["32"]);
G2L["33"]["TextWrapped"] = true;
G2L["33"]["BorderSizePixel"] = 0;
G2L["33"]["TextSize"] = 14;
G2L["33"]["TextScaled"] = true;
G2L["33"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["33"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["33"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["33"]["BackgroundTransparency"] = 1;
G2L["33"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["33"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["33"]["Text"] = [[Buy Blocks]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.AutoBuy.ScrollingFrame.TextButton.UICorner
G2L["34"] = Instance.new("UICorner", G2L["33"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.AutoBuy.ScrollingFrame.TextButton.UIStroke
G2L["35"] = Instance.new("UIStroke", G2L["33"]);
G2L["35"]["Thickness"] = 2;
G2L["35"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["35"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.AutoBuy.ScrollingFrame.UIListLayout
G2L["36"] = Instance.new("UIListLayout", G2L["32"]);
G2L["36"]["Padding"] = UDim.new(0, 10);
G2L["36"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.AutoBuy.ScrollingFrame.TextButton
G2L["37"] = Instance.new("TextButton", G2L["32"]);
G2L["37"]["TextWrapped"] = true;
G2L["37"]["BorderSizePixel"] = 0;
G2L["37"]["TextSize"] = 14;
G2L["37"]["TextScaled"] = true;
G2L["37"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["37"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["37"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["37"]["BackgroundTransparency"] = 1;
G2L["37"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["37"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["37"]["Text"] = [[	Buy Chests]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.AutoBuy.ScrollingFrame.TextButton.UICorner
G2L["38"] = Instance.new("UICorner", G2L["37"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.AutoBuy.ScrollingFrame.TextButton.UIStroke
G2L["39"] = Instance.new("UIStroke", G2L["37"]);
G2L["39"]["Thickness"] = 2;
G2L["39"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["39"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.AutoBuy.ScrollingFrame.TextButton
G2L["3a"] = Instance.new("TextButton", G2L["32"]);
G2L["3a"]["TextWrapped"] = true;
G2L["3a"]["BorderSizePixel"] = 0;
G2L["3a"]["TextSize"] = 14;
G2L["3a"]["TextScaled"] = true;
G2L["3a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3a"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["3a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3a"]["BackgroundTransparency"] = 1;
G2L["3a"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["3a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3a"]["Text"] = [[Buy Tools]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.AutoBuy.ScrollingFrame.TextButton.UICorner
G2L["3b"] = Instance.new("UICorner", G2L["3a"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.AutoBuy.ScrollingFrame.TextButton.UIStroke
G2L["3c"] = Instance.new("UIStroke", G2L["3a"]);
G2L["3c"]["Thickness"] = 2;
G2L["3c"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["3c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.AutoBuy.ScrollingFrame.TextLabel
G2L["3d"] = Instance.new("TextLabel", G2L["32"]);
G2L["3d"]["TextWrapped"] = true;
G2L["3d"]["BorderSizePixel"] = 0;
G2L["3d"]["TextSize"] = 14;
G2L["3d"]["TextXAlignment"] = Enum.TextXAlignment.Right;
G2L["3d"]["TextScaled"] = true;
G2L["3d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3d"]["BackgroundTransparency"] = 1;
G2L["3d"]["Size"] = UDim2.new(0, 200, 0, 50);
G2L["3d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3d"]["Text"] = [[Soon!]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Tools
G2L["3e"] = Instance.new("Frame", G2L["6"]);
G2L["3e"]["Visible"] = false;
G2L["3e"]["BorderSizePixel"] = 0;
G2L["3e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3e"]["Size"] = UDim2.new(0, 456, 0, 277);
G2L["3e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3e"]["Name"] = [[Tools]];
G2L["3e"]["BackgroundTransparency"] = 1;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Tools.List
G2L["3f"] = Instance.new("ScrollingFrame", G2L["3e"]);
G2L["3f"]["Active"] = true;
G2L["3f"]["BorderSizePixel"] = 0;
G2L["3f"]["Name"] = [[List]];
G2L["3f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3f"]["Size"] = UDim2.new(0, 456, 0, 277);
G2L["3f"]["ScrollBarImageColor3"] = Color3.fromRGB(108, 108, 108);
G2L["3f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3f"]["BackgroundTransparency"] = 1;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Tools.List.UIListLayout
G2L["40"] = Instance.new("UIListLayout", G2L["3f"]);
G2L["40"]["Padding"] = UDim.new(0, 10);
G2L["40"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Tools.List.TPTool
G2L["41"] = Instance.new("TextButton", G2L["3f"]);
G2L["41"]["TextWrapped"] = true;
G2L["41"]["BorderSizePixel"] = 0;
G2L["41"]["TextSize"] = 14;
G2L["41"]["TextScaled"] = true;
G2L["41"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["41"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["41"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["41"]["BackgroundTransparency"] = 1;
G2L["41"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["41"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["41"]["Text"] = [[TP Tool]];
G2L["41"]["Name"] = [[TPTool]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Tools.List.TPTool.UICorner
G2L["42"] = Instance.new("UICorner", G2L["41"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Tools.List.TPTool.UIStroke
G2L["43"] = Instance.new("UIStroke", G2L["41"]);
G2L["43"]["Thickness"] = 2;
G2L["43"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["43"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Tools.List.TPTool.LocalScript
G2L["44"] = Instance.new("LocalScript", G2L["41"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Tools.List.Telekineses
G2L["45"] = Instance.new("TextButton", G2L["3f"]);
G2L["45"]["TextWrapped"] = true;
G2L["45"]["BorderSizePixel"] = 0;
G2L["45"]["TextSize"] = 14;
G2L["45"]["TextScaled"] = true;
G2L["45"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["45"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["45"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["45"]["BackgroundTransparency"] = 1;
G2L["45"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["45"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["45"]["Text"] = [[Telekineses]];
G2L["45"]["Name"] = [[Telekineses]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Tools.List.Telekineses.UICorner
G2L["46"] = Instance.new("UICorner", G2L["45"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Tools.List.Telekineses.UIStroke
G2L["47"] = Instance.new("UIStroke", G2L["45"]);
G2L["47"]["Thickness"] = 2;
G2L["47"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["47"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Tools.List.Telekineses.LocalScript
G2L["48"] = Instance.new("LocalScript", G2L["45"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens
G2L["49"] = Instance.new("Frame", G2L["6"]);
G2L["49"]["Visible"] = false;
G2L["49"]["BorderSizePixel"] = 0;
G2L["49"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["49"]["Size"] = UDim2.new(0, 456, 0, 278);
G2L["49"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["49"]["Name"] = [[Itens]];
G2L["49"]["BackgroundTransparency"] = 1;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame
G2L["4a"] = Instance.new("ScrollingFrame", G2L["49"]);
G2L["4a"]["Active"] = true;
G2L["4a"]["BorderSizePixel"] = 0;
G2L["4a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4a"]["Size"] = UDim2.new(0, 456, 0, 277);
G2L["4a"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4a"]["BackgroundTransparency"] = 1;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton
G2L["4b"] = Instance.new("TextButton", G2L["4a"]);
G2L["4b"]["TextWrapped"] = true;
G2L["4b"]["BorderSizePixel"] = 0;
G2L["4b"]["TextSize"] = 14;
G2L["4b"]["TextScaled"] = true;
G2L["4b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4b"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["4b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4b"]["BackgroundTransparency"] = 1;
G2L["4b"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["4b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4b"]["Text"] = [[Get Portal]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton.UICorner
G2L["4c"] = Instance.new("UICorner", G2L["4b"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton.UIStroke
G2L["4d"] = Instance.new("UIStroke", G2L["4b"]);
G2L["4d"]["Thickness"] = 2;
G2L["4d"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["4d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.UIListLayout
G2L["4e"] = Instance.new("UIListLayout", G2L["4a"]);
G2L["4e"]["Padding"] = UDim.new(0, 10);
G2L["4e"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton
G2L["4f"] = Instance.new("TextButton", G2L["4a"]);
G2L["4f"]["TextWrapped"] = true;
G2L["4f"]["BorderSizePixel"] = 0;
G2L["4f"]["TextSize"] = 14;
G2L["4f"]["TextScaled"] = true;
G2L["4f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4f"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["4f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4f"]["BackgroundTransparency"] = 1;
G2L["4f"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["4f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4f"]["Text"] = [[Get Chilltrill709 Plushie]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton.UICorner
G2L["50"] = Instance.new("UICorner", G2L["4f"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton.UIStroke
G2L["51"] = Instance.new("UIStroke", G2L["4f"]);
G2L["51"]["Thickness"] = 2;
G2L["51"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["51"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton.LocalScript
G2L["52"] = Instance.new("LocalScript", G2L["4f"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton
G2L["53"] = Instance.new("TextButton", G2L["4a"]);
G2L["53"]["TextWrapped"] = true;
G2L["53"]["BorderSizePixel"] = 0;
G2L["53"]["TextSize"] = 14;
G2L["53"]["TextScaled"] = true;
G2L["53"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["53"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["53"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["53"]["BackgroundTransparency"] = 1;
G2L["53"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["53"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["53"]["Text"] = [[Get FireWorks]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton.UICorner
G2L["54"] = Instance.new("UICorner", G2L["53"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton.UIStroke
G2L["55"] = Instance.new("UIStroke", G2L["53"]);
G2L["55"]["Thickness"] = 2;
G2L["55"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["55"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton.LocalScript
G2L["56"] = Instance.new("LocalScript", G2L["53"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton
G2L["57"] = Instance.new("TextButton", G2L["4a"]);
G2L["57"]["TextWrapped"] = true;
G2L["57"]["BorderSizePixel"] = 0;
G2L["57"]["TextSize"] = 14;
G2L["57"]["TextScaled"] = true;
G2L["57"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["57"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["57"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["57"]["BackgroundTransparency"] = 1;
G2L["57"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["57"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["57"]["Text"] = [[Get Neon]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton.UICorner
G2L["58"] = Instance.new("UICorner", G2L["57"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton.UIStroke
G2L["59"] = Instance.new("UIStroke", G2L["57"]);
G2L["59"]["Thickness"] = 2;
G2L["59"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["59"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton
G2L["5a"] = Instance.new("TextButton", G2L["4a"]);
G2L["5a"]["TextWrapped"] = true;
G2L["5a"]["BorderSizePixel"] = 0;
G2L["5a"]["TextSize"] = 14;
G2L["5a"]["TextScaled"] = true;
G2L["5a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5a"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["5a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5a"]["BackgroundTransparency"] = 1;
G2L["5a"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["5a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5a"]["Text"] = [[Get Gear Plushie]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton.UICorner
G2L["5b"] = Instance.new("UICorner", G2L["5a"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton.UIStroke
G2L["5c"] = Instance.new("UIStroke", G2L["5a"]);
G2L["5c"]["Thickness"] = 2;
G2L["5c"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["5c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton.LocalScript
G2L["5d"] = Instance.new("LocalScript", G2L["5a"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton
G2L["5e"] = Instance.new("TextButton", G2L["4a"]);
G2L["5e"]["TextWrapped"] = true;
G2L["5e"]["BorderSizePixel"] = 0;
G2L["5e"]["TextSize"] = 14;
G2L["5e"]["TextScaled"] = true;
G2L["5e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5e"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["5e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5e"]["BackgroundTransparency"] = 1;
G2L["5e"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["5e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5e"]["Text"] = [[Get Golden Harpoon]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton.UICorner
G2L["5f"] = Instance.new("UICorner", G2L["5e"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton.UIStroke
G2L["60"] = Instance.new("UIStroke", G2L["5e"]);
G2L["60"]["Thickness"] = 2;
G2L["60"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["60"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc
G2L["61"] = Instance.new("Frame", G2L["6"]);
G2L["61"]["Visible"] = false;
G2L["61"]["BorderSizePixel"] = 0;
G2L["61"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["61"]["Size"] = UDim2.new(0, 456, 0, 277);
G2L["61"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["61"]["Name"] = [[Misc]];
G2L["61"]["BackgroundTransparency"] = 1;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List
G2L["62"] = Instance.new("ScrollingFrame", G2L["61"]);
G2L["62"]["Active"] = true;
G2L["62"]["BorderSizePixel"] = 0;
G2L["62"]["Name"] = [[List]];
G2L["62"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["62"]["Size"] = UDim2.new(0, 456, 0, 277);
G2L["62"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["62"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["62"]["BackgroundTransparency"] = 1;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.Remove Water
G2L["63"] = Instance.new("TextButton", G2L["62"]);
G2L["63"]["TextWrapped"] = true;
G2L["63"]["BorderSizePixel"] = 0;
G2L["63"]["TextSize"] = 14;
G2L["63"]["TextScaled"] = true;
G2L["63"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["63"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["63"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["63"]["BackgroundTransparency"] = 1;
G2L["63"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["63"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["63"]["Text"] = [[Remove Water]];
G2L["63"]["Name"] = [[Remove Water]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.Remove Water.UICorner
G2L["64"] = Instance.new("UICorner", G2L["63"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.Remove Water.UIStroke
G2L["65"] = Instance.new("UIStroke", G2L["63"]);
G2L["65"]["Thickness"] = 2;
G2L["65"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["65"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.Remove Water.LocalScript
G2L["66"] = Instance.new("LocalScript", G2L["63"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.UIListLayout
G2L["67"] = Instance.new("UIListLayout", G2L["62"]);
G2L["67"]["Padding"] = UDim.new(0, 10);
G2L["67"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.NoFog
G2L["68"] = Instance.new("TextButton", G2L["62"]);
G2L["68"]["TextWrapped"] = true;
G2L["68"]["BorderSizePixel"] = 0;
G2L["68"]["TextSize"] = 14;
G2L["68"]["TextScaled"] = true;
G2L["68"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["68"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["68"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["68"]["BackgroundTransparency"] = 1;
G2L["68"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["68"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["68"]["Text"] = [[	No-Fog]];
G2L["68"]["Name"] = [[NoFog]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.NoFog.LocalScript
G2L["69"] = Instance.new("LocalScript", G2L["68"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.NoFog.UICorner
G2L["6a"] = Instance.new("UICorner", G2L["68"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.NoFog.UIStroke
G2L["6b"] = Instance.new("UIStroke", G2L["68"]);
G2L["6b"]["Thickness"] = 2;
G2L["6b"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["6b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.Fullbright
G2L["6c"] = Instance.new("TextButton", G2L["62"]);
G2L["6c"]["TextWrapped"] = true;
G2L["6c"]["BorderSizePixel"] = 0;
G2L["6c"]["TextSize"] = 14;
G2L["6c"]["TextScaled"] = true;
G2L["6c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6c"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["6c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6c"]["BackgroundTransparency"] = 1;
G2L["6c"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["6c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6c"]["Text"] = [[Fullbright]];
G2L["6c"]["Name"] = [[Fullbright]];
G2L["6c"]["Position"] = UDim2.new(-0.00439, 0, 0.15523, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.Fullbright.LocalScript
G2L["6d"] = Instance.new("LocalScript", G2L["6c"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.Fullbright.UICorner
G2L["6e"] = Instance.new("UICorner", G2L["6c"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.Fullbright.UIStroke
G2L["6f"] = Instance.new("UIStroke", G2L["6c"]);
G2L["6f"]["Thickness"] = 2;
G2L["6f"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["6f"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.ESP
G2L["70"] = Instance.new("TextButton", G2L["62"]);
G2L["70"]["TextWrapped"] = true;
G2L["70"]["BorderSizePixel"] = 0;
G2L["70"]["TextSize"] = 14;
G2L["70"]["TextScaled"] = true;
G2L["70"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["70"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["70"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["70"]["BackgroundTransparency"] = 1;
G2L["70"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["70"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["70"]["Text"] = [[ESP Players]];
G2L["70"]["Name"] = [[ESP]];
G2L["70"]["Position"] = UDim2.new(-0.00439, 0, 0.15523, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.ESP.UICorner
G2L["71"] = Instance.new("UICorner", G2L["70"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.ESP.UIStroke
G2L["72"] = Instance.new("UIStroke", G2L["70"]);
G2L["72"]["Thickness"] = 2;
G2L["72"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["72"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.TextButton
G2L["73"] = Instance.new("TextButton", G2L["62"]);
G2L["73"]["TextWrapped"] = true;
G2L["73"]["BorderSizePixel"] = 0;
G2L["73"]["TextSize"] = 14;
G2L["73"]["TextScaled"] = true;
G2L["73"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["73"]["BackgroundColor3"] = Color3.fromRGB(2, 4, 50);
G2L["73"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["73"]["BackgroundTransparency"] = 1;
G2L["73"]["Size"] = UDim2.new(0, 439, 0, 33);
G2L["73"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["73"]["Text"] = [[Anti-Lag]];
G2L["73"]["Position"] = UDim2.new(-0.00439, 0, 0.15523, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.TextButton.LocalScript
G2L["74"] = Instance.new("LocalScript", G2L["73"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.TextButton.UICorner
G2L["75"] = Instance.new("UICorner", G2L["73"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.TextButton.UIStroke
G2L["76"] = Instance.new("UIStroke", G2L["73"]);
G2L["76"]["Thickness"] = 2;
G2L["76"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["76"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons
G2L["77"] = Instance.new("Frame", G2L["2"]);
G2L["77"]["BorderSizePixel"] = 0;
G2L["77"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["77"]["Size"] = UDim2.new(0, 92, 0, 278);
G2L["77"]["Position"] = UDim2.new(0, 0, 0.10032, 0);
G2L["77"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["77"]["Name"] = [[Buttons]];
G2L["77"]["BackgroundTransparency"] = 1;


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.Home
G2L["78"] = Instance.new("TextButton", G2L["77"]);
G2L["78"]["TextWrapped"] = true;
G2L["78"]["BorderSizePixel"] = 0;
G2L["78"]["TextSize"] = 14;
G2L["78"]["TextScaled"] = true;
G2L["78"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["78"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["78"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["78"]["BackgroundTransparency"] = 1;
G2L["78"]["Size"] = UDim2.new(0, 92, 0, 23);
G2L["78"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["78"]["Text"] = [[Home]];
G2L["78"]["Name"] = [[Home]];
G2L["78"]["Position"] = UDim2.new(0, 0, 0.00284, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.Home.LocalScript
G2L["79"] = Instance.new("LocalScript", G2L["78"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.Farm
G2L["7a"] = Instance.new("TextButton", G2L["77"]);
G2L["7a"]["TextWrapped"] = true;
G2L["7a"]["BorderSizePixel"] = 0;
G2L["7a"]["TextSize"] = 14;
G2L["7a"]["TextScaled"] = true;
G2L["7a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7a"]["BackgroundTransparency"] = 1;
G2L["7a"]["Size"] = UDim2.new(0, 92, 0, 23);
G2L["7a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7a"]["Text"] = [[Farm]];
G2L["7a"]["Name"] = [[Farm]];
G2L["7a"]["Position"] = UDim2.new(0, 0, 0.09814, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.Farm.LocalScript
G2L["7b"] = Instance.new("LocalScript", G2L["7a"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.Scripts
G2L["7c"] = Instance.new("TextButton", G2L["77"]);
G2L["7c"]["TextWrapped"] = true;
G2L["7c"]["BorderSizePixel"] = 0;
G2L["7c"]["TextSize"] = 14;
G2L["7c"]["TextScaled"] = true;
G2L["7c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7c"]["BackgroundTransparency"] = 1;
G2L["7c"]["Size"] = UDim2.new(0, 92, 0, 23);
G2L["7c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7c"]["Text"] = [[Scripts]];
G2L["7c"]["Name"] = [[Scripts]];
G2L["7c"]["Position"] = UDim2.new(0, 0, 0.17257, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.Scripts.LocalScript
G2L["7d"] = Instance.new("LocalScript", G2L["7c"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.Itens
G2L["7e"] = Instance.new("TextButton", G2L["77"]);
G2L["7e"]["TextWrapped"] = true;
G2L["7e"]["BorderSizePixel"] = 0;
G2L["7e"]["TextSize"] = 14;
G2L["7e"]["TextScaled"] = true;
G2L["7e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7e"]["BackgroundTransparency"] = 1;
G2L["7e"]["Size"] = UDim2.new(0, 92, 0, 23);
G2L["7e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7e"]["Text"] = [[Itens]];
G2L["7e"]["Name"] = [[Itens]];
G2L["7e"]["Position"] = UDim2.new(0, 0, 0.25347, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.Itens.LocalScript
G2L["7f"] = Instance.new("LocalScript", G2L["7e"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.AutoBuy
G2L["80"] = Instance.new("TextButton", G2L["77"]);
G2L["80"]["TextWrapped"] = true;
G2L["80"]["BorderSizePixel"] = 0;
G2L["80"]["TextSize"] = 14;
G2L["80"]["TextScaled"] = true;
G2L["80"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["80"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["80"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["80"]["BackgroundTransparency"] = 1;
G2L["80"]["Size"] = UDim2.new(0, 92, 0, 23);
G2L["80"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["80"]["Text"] = [[Auto Buy]];
G2L["80"]["Name"] = [[AutoBuy]];
G2L["80"]["Position"] = UDim2.new(0, 0, 0.41817, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.AutoBuy.LocalScript
G2L["81"] = Instance.new("LocalScript", G2L["80"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.Tools
G2L["82"] = Instance.new("TextButton", G2L["77"]);
G2L["82"]["TextWrapped"] = true;
G2L["82"]["BorderSizePixel"] = 0;
G2L["82"]["TextSize"] = 14;
G2L["82"]["TextScaled"] = true;
G2L["82"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["82"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["82"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["82"]["BackgroundTransparency"] = 1;
G2L["82"]["Size"] = UDim2.new(0, 92, 0, 23);
G2L["82"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["82"]["Text"] = [[Tools]];
G2L["82"]["Name"] = [[Tools]];
G2L["82"]["Position"] = UDim2.new(0, 0, 0.3423, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.Tools.LocalScript
G2L["83"] = Instance.new("LocalScript", G2L["82"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.Misc
G2L["84"] = Instance.new("TextButton", G2L["77"]);
G2L["84"]["TextWrapped"] = true;
G2L["84"]["BorderSizePixel"] = 0;
G2L["84"]["TextSize"] = 14;
G2L["84"]["TextScaled"] = true;
G2L["84"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["84"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["84"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["84"]["BackgroundTransparency"] = 1;
G2L["84"]["Size"] = UDim2.new(0, 92, 0, 23);
G2L["84"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["84"]["Text"] = [[Misc]];
G2L["84"]["Name"] = [[Misc]];
G2L["84"]["Position"] = UDim2.new(0.02174, 0, 0.49731, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.Misc.LocalScript
G2L["85"] = Instance.new("LocalScript", G2L["84"]);



-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Trash
G2L["86"] = Instance.new("Folder", G2L["2"]);
G2L["86"]["Name"] = [[Trash]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Trash.Frame
G2L["87"] = Instance.new("Frame", G2L["86"]);
G2L["87"]["BorderSizePixel"] = 0;
G2L["87"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["87"]["Size"] = UDim2.new(0, 92, 0, 2);
G2L["87"]["Position"] = UDim2.new(0, 0, 0.6246, 0);
G2L["87"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Trash.Frame
G2L["88"] = Instance.new("Frame", G2L["86"]);
G2L["88"]["BorderSizePixel"] = 0;
G2L["88"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["88"]["Size"] = UDim2.new(0, 92, 0, 2);
G2L["88"]["Position"] = UDim2.new(0, 0, 0.55016, 0);
G2L["88"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Trash.Frame
G2L["89"] = Instance.new("Frame", G2L["86"]);
G2L["89"]["BorderSizePixel"] = 0;
G2L["89"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["89"]["Size"] = UDim2.new(0, 92, 0, 2);
G2L["89"]["Position"] = UDim2.new(0, 0, 0.40453, 0);
G2L["89"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Trash.Frame
G2L["8a"] = Instance.new("Frame", G2L["86"]);
G2L["8a"]["BorderSizePixel"] = 0;
G2L["8a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8a"]["Size"] = UDim2.new(0, 92, 0, 2);
G2L["8a"]["Position"] = UDim2.new(0, 0, 0.47896, 0);
G2L["8a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Trash.Frame
G2L["8b"] = Instance.new("Frame", G2L["86"]);
G2L["8b"]["BorderSizePixel"] = 0;
G2L["8b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8b"]["Size"] = UDim2.new(0, 92, 0, 2);
G2L["8b"]["Position"] = UDim2.new(0, 0, 0.33333, 0);
G2L["8b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Trash.Frame
G2L["8c"] = Instance.new("Frame", G2L["86"]);
G2L["8c"]["BorderSizePixel"] = 0;
G2L["8c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8c"]["Size"] = UDim2.new(0, 92, 0, 2);
G2L["8c"]["Position"] = UDim2.new(0, 0, 0.17799, 0);
G2L["8c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Trash.Frame
G2L["8d"] = Instance.new("Frame", G2L["86"]);
G2L["8d"]["BorderSizePixel"] = 0;
G2L["8d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8d"]["Size"] = UDim2.new(0, 92, 0, 2);
G2L["8d"]["Position"] = UDim2.new(0, 0, 0.2589, 0);
G2L["8d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Trash.Frame
G2L["8e"] = Instance.new("Frame", G2L["86"]);
G2L["8e"]["BorderSizePixel"] = 0;
G2L["8e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8e"]["Size"] = UDim2.new(0, -2, 0, 279);
G2L["8e"]["Position"] = UDim2.new(0.17091, 0, 0.09385, 0);
G2L["8e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Trash.Frame
G2L["8f"] = Instance.new("Frame", G2L["86"]);
G2L["8f"]["BorderSizePixel"] = 0;
G2L["8f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8f"]["Size"] = UDim2.new(0, 550, 0, 1);
G2L["8f"]["Position"] = UDim2.new(0, 0, 0.09385, 0);
G2L["8f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Close
G2L["90"] = Instance.new("TextButton", G2L["2"]);
G2L["90"]["TextWrapped"] = true;
G2L["90"]["BorderSizePixel"] = 0;
G2L["90"]["TextSize"] = 14;
G2L["90"]["TextScaled"] = true;
G2L["90"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["90"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["90"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["90"]["BackgroundTransparency"] = 1;
G2L["90"]["Size"] = UDim2.new(0, 42, 0, 26);
G2L["90"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["90"]["Text"] = [[X]];
G2L["90"]["Name"] = [[Close]];
G2L["90"]["Position"] = UDim2.new(0.92364, 0, 0, 0);


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Close.LocalScript
G2L["91"] = Instance.new("LocalScript", G2L["90"]);



-- StarterGui.BABFT.SagittariusHubBABFT.Dragify
G2L["92"] = Instance.new("LocalScript", G2L["1"]);
G2L["92"]["Name"] = [[Dragify]];


-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Home.List.IY.LocalScript
local function C_e()
local script = G2L["e"];
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
	end)
end;
task.spawn(C_e);
-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Farm.List.AutoReedem.TextButton.LocalScript
local function C_18()
local script = G2L["18"];
	-- LocalScript dentro do botão
	local button = script.Parent
	
	local ativo = false
	local loopAtivo = nil
	
	local function loopClaim()
		while ativo do
			pcall(function()
				workspace:WaitForChild("ClaimRiverResultsGold"):FireServer()
			end)
			task.wait(0.5)
		end
	end
	
	button.MouseButton1Click:Connect(function()
		ativo = not ativo
	
		if ativo then
			button.BackgroundColor3 = Color3.new(0, 1, 0)
			loopAtivo = coroutine.wrap(loopClaim)()
		else
			button.BackgroundColor3 = Color3.new(1, 0, 0)
			loopAtivo = nil
		end
	end)
	
	button.BackgroundColor3 = Color3.new(1, 0, 0)
end;
task.spawn(C_18);
-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Farm.List.AutoFarm.TextButton.LocalScript
local function C_1f()
local script = G2L["1f"];
	-- LocalScript dentro do botão (VERSÃO CORRIGIDA)
	local button = script.Parent
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	local player = Players.LocalPlayer
	
	-- CONFIGURAÇÕES
	local velocidadeFly = 500
	local alturaVoo = 57
	local autoFarmAtivo = false
	local noclipConnection = nil
	local bv = nil
	local bg = nil
	
	-- ROTA
	local rota = {
		Vector3.new(-63, alturaVoo, 800),
		Vector3.new(-63, alturaVoo, 1600),
		Vector3.new(-63, alturaVoo, 2400),
		Vector3.new(-63, alturaVoo, 3200),
		Vector3.new(-63, alturaVoo, 4000),
		Vector3.new(-63, alturaVoo, 4800),
		Vector3.new(-63, alturaVoo, 5600),
		Vector3.new(-63, alturaVoo, 6400),
		Vector3.new(-63, alturaVoo, 7200),
		Vector3.new(-63, alturaVoo, 8500),
		Vector3.new(-63, -358, 9512)
	}
	
	-- FUNÇÃO PARA LIMPAR TUDO COM SEGURANÇA
	local function limparTudo()
		if noclipConnection then
			noclipConnection:Disconnect()
			noclipConnection = nil
		end
	
		pcall(function()
			if bv then
				bv:Destroy()
				bv = nil
			end
		end)
	
		pcall(function()
			if bg then
				bg:Destroy()
				bg = nil
			end
		end)
	
		-- Resetar colisões do personagem
		local char = player.Character
		if char then
			for _, part in pairs(char:GetDescendants()) do
				if part:IsA("BasePart") then
					pcall(function()
						part.CanCollide = true
					end)
				end
			end
	
			-- Restaurar estado do humanoid
			local humanoid = char:FindFirstChildOfClass("Humanoid")
			if humanoid then
				pcall(function()
					humanoid:ChangeState(Enum.HumanoidStateType.Running) -- Volta ao estado normal
				end)
			end
		end
	end
	
	-- FUNÇÃO PARA OBTER O ROOT COM SEGURANÇA
	local function getRoot()
		local char = player.Character
		if not char then return nil end
		return char:FindFirstChild("HumanoidRootPart")
	end
	
	-- FUNÇÃO DO NOCLIP CORRIGIDA
	local function setupNoclip()
		if noclipConnection then
			noclipConnection:Disconnect()
		end
	
		noclipConnection = RunService.Stepped:Connect(function()
			if not autoFarmAtivo then return end
	
			local char = player.Character
			if not char then return end
	
			local humanoid = char:FindFirstChildOfClass("Humanoid")
			local root = char:FindFirstChild("HumanoidRootPart")
	
			-- Colocar humanoid em estado Physics (ignora colisões)
			if humanoid then
				pcall(function()
					humanoid:ChangeState(Enum.HumanoidStateType.Physics) -- 11 = Physics
				end)
			end
	
			-- Desativar colisão das partes
			if root then
				pcall(function()
					root.CanCollide = false
				end)
			end
	
			for _, part in pairs(char:GetChildren()) do
				if part:IsA("BasePart") and part.Name ~= "HumanoidRootPart" then
					pcall(function()
						part.CanCollide = false
					end)
				end
			end
		end)
	end
	
	-- FUNÇÃO PARA EXECUTAR O AUTO FARM
	local function executarAutoFarm()
		while autoFarmAtivo do
			-- Aguardar personagem
			local char = player.Character
			if not char then
				player.CharacterAdded:Wait()
				char = player.Character
			end
	
			-- Pegar root
			local root = getRoot()
			if not root then
				repeat
					task.wait()
					root = getRoot()
				until root or not autoFarmAtivo
			end
	
			if not autoFarmAtivo then break end
	
			-- Criar forças de voo
			pcall(function()
				bv = Instance.new("BodyVelocity")
				bv.MaxForce = Vector3.new(1e9, 1e9, 1e9)
				bv.Parent = root
			end)
	
			pcall(function()
				bg = Instance.new("BodyGyro")
				bg.MaxTorque = Vector3.new(1e9, 1e9, 1e9)
				bg.P = 5000
				bg.CFrame = root.CFrame
				bg.Parent = root
			end)
	
			-- Setup noclip
			setupNoclip()
	
			-- PERCURSO
			for i, ponto in pairs(rota) do
				if not autoFarmAtivo then break end
	
				root = getRoot()
				if not root then break end
	
				local whileCount = 0
				while autoFarmAtivo and root and (root.Position - ponto).Magnitude > 20 do
					whileCount = whileCount + 1
					if whileCount > 1000 then break end
	
					root = getRoot()
					if not root then break end
	
					local direcao = (ponto - root.Position).Unit
	
					pcall(function()
						if bv and bv.Parent then
							bv.Velocity = direcao * velocidadeFly
						end
					end)
	
					pcall(function()
						if bg and bg.Parent then
							bg.CFrame = CFrame.lookAt(root.Position, ponto)
						end
					end)
	
					task.wait()
				end
	
				if not autoFarmAtivo then break end
	
				pcall(function()
					if bv and bv.Parent then
						bv.Velocity = Vector3.new(0, 0, 0)
					end
				end)
				task.wait(0.1)
			end
	
			limparTudo()
	
			if autoFarmAtivo then
				task.wait(1)
			end
		end
	end
	
	-- FUNÇÃO PARA ATIVAR/DESATIVAR
	local function toggleAutoFarm()
		autoFarmAtivo = not autoFarmAtivo
	
		if autoFarmAtivo then
			button.BackgroundColor3 = Color3.new(0, 1, 0) -- Verde
			
			limparTudo()
			task.wait(0.1)
			coroutine.wrap(executarAutoFarm)()
		else
			button.BackgroundColor3 = Color3.new(1, 0, 0) -- Vermelho
			
			limparTudo()
		end
	end
	
	-- CONECTAR O BOTÃO
	button.MouseButton1Click:Connect(toggleAutoFarm)
	
	-- COR INICIAL
	button.BackgroundColor3 = Color3.new(1, 0, 0)
	
	
	
	-- FUNÇÃO DE NOCLIP (Pode colocar no final do script)
	local function iniciarNoclipConstante()
		if noclipConnection then
			noclipConnection:Disconnect()
		end
	
		noclipConnection = RunService.Stepped:Connect(function()
			local char = player.Character
			if char and autoFarmAtivo then
				for _, part in ipairs(char:GetDescendants()) do
					if part:IsA("BasePart") then
						part.CanCollide = false
					end
				end
	
				local humanoid = char:FindFirstChildOfClass("Humanoid")
				if humanoid then
					-- O estado Physics desativa a física interna que empurra o boneco para fora das paredes
					humanoid:ChangeState(Enum.HumanoidStateType.Physics)
				end
			end
		end)
	end
end;
task.spawn(C_1f);
-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Tools.List.TPTool.LocalScript
local function C_44()
local script = G2L["44"];
	-- LocalScript dentro do botão
	local button = script.Parent
	local player = game:GetService("Players").LocalPlayer
	local mouse = player:GetMouse()
	
	button.MouseButton1Click:Connect(function()
		-- Criação da Tool
		local tpTool = Instance.new("Tool")
		tpTool.Name = "TPTOOL"
		tpTool.RequiresHandle = false
		tpTool.Parent = player.Backpack
	
		-- Evento de clique da Tool
		tpTool.Activated:Connect(function()
			local character = player.Character
			if character then
				local root = character:FindFirstChild("HumanoidRootPart")
				if root then
					-- Teleporta para a posição do mouse (3 studs acima para não entrar no chão)
					local targetPos = mouse.Hit.p + Vector3.new(0, 3, 0)
					root.CFrame = CFrame.new(targetPos)
				end
			end
		end)
	end)
end;
task.spawn(C_44);
-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Tools.List.Telekineses.LocalScript
local function C_48()
local script = G2L["48"];
	-- LocalScript dentro do botão
	local button = script.Parent
	local player = game:GetService("Players").LocalPlayer
	local uis = game:GetService("UserInputService")
	local runService = game:GetService("RunService")
	local mouse = player:GetMouse()
	
	button.MouseButton1Click:Connect(function()
		local tkTool = Instance.new("Tool")
		tkTool.Name = "MobileTelekinesis"
		tkTool.RequiresHandle = false
		tkTool.Parent = player.Backpack
	
		local target = nil
		local bp = nil
		local connection = nil
	
		tkTool.Equipped:Connect(function()
			local inputConn = uis.InputBegan:Connect(function(input, gpe)
				if gpe then return end
				if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
					if mouse.Target then
						target = mouse.Target
						target.Anchored = false
	
						bp = Instance.new("BodyPosition")
						bp.Name = "TK_Force"
						bp.MaxForce = Vector3.new(1e6, 1e6, 1e6)
						bp.D = 1000
						bp.P = 10000
						bp.Parent = target
	
						connection = runService.RenderStepped:Connect(function()
							if bp and target then
								bp.Position = mouse.Hit.p
							end
						end)
					end
				end
			end)
	
			local releaseConn
			releaseConn = uis.InputEnded:Connect(function(input)
				if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
					if connection then connection:Disconnect() end
					if bp then bp:Destroy() end
					target = nil
					inputConn:Disconnect()
					releaseConn:Disconnect()
				end
			end)
		end)
	end)
end;
task.spawn(C_48);
-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton.LocalScript
local function C_52()
local script = G2L["52"];
	-- LocalScript dentro do botão
	local button = script.Parent
	local player = game:GetService("Players").LocalPlayer
	
	button.MouseButton1Click:Connect(function()
		local character = player.Character
		if character then
			local root = character:FindFirstChild("HumanoidRootPart")
			if root then
				root.CFrame = CFrame.new(190.1, -7.8, 1159.8)
			end
		end
	end)
end;
task.spawn(C_52);
-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton.LocalScript
local function C_56()
local script = G2L["56"];
	-- Versão para rodar direto no Executor (Sem precisar de botão)
	local player = game:GetService("Players").LocalPlayer
	
	local function ativarCodigo()
		local args = {"Chillthrill709 was here"}
	
		-- Tenta encontrar a função no servidor
		local codeRemote = workspace:FindFirstChild("CheckCodeFunction") or workspace:WaitForChild("CheckCodeFunction", 3)
	
		if codeRemote then
			local sucesso, erro = pcall(function()
				codeRemote:InvokeServer(unpack(args))
			end)
	
			if sucesso then
				
			else
				
			end
		else
			
		end
	end
	
	ativarCodigo()
end;
task.spawn(C_56);
-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Itens.ScrollingFrame.TextButton.LocalScript
local function C_5d()
local script = G2L["5d"];
	-- LocalScript dentro do botão (SÓ FUNÇÃO, SEM COR)
	local button = script.Parent
	local player = game:GetService("Players").LocalPlayer
	
	button.MouseButton1Click:Connect(function()
		-- Verificar se a fase existe
		local lever = workspace:FindFirstChild("BoatStages")
			and workspace.BoatStages:FindFirstChild("OtherStages")
			and workspace.BoatStages.OtherStages:FindFirstChild("GearStage")
			and workspace.BoatStages.OtherStages.GearStage:FindFirstChild("TerrainWall1")
			and workspace.BoatStages.OtherStages.GearStage.TerrainWall1:FindFirstChild("Clock")
			and workspace.BoatStages.OtherStages.GearStage.TerrainWall1.Clock:FindFirstChild("Lever")
	
		if not lever then return end
	
		-- Garantir personagem
		local character = player.Character or player.CharacterAdded:Wait()
		local root = character:WaitForChild("HumanoidRootPart")
	
		-- Teleportar
		root.CFrame = lever.CFrame + Vector3.new(0, 3, 0)
	end)
end;
task.spawn(C_5d);
-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.Remove Water.LocalScript
local function C_66()
local script = G2L["66"];
	-- LocalScript dentro do botão
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		-- Procura em todos os descendentes do Workspace
		for _, object in ipairs(workspace:GetDescendants()) do
			if object.Name == "Water" then
				object:Destroy()
			end
		end
	end)
end;
task.spawn(C_66);
-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.NoFog.LocalScript
local function C_69()
local script = G2L["69"];
	-- LocalScript com toggle No-Fog
	local button = script.Parent
	local lighting = game:GetService("Lighting")
	
	-- Salvar valores originais
	local originalFogEnd = lighting.FogEnd
	local originalFogStart = lighting.FogStart
	local originalFogColor = lighting.FogColor
	
	local noFogOn = false
	
	button.MouseButton1Click:Connect(function()
		noFogOn = not noFogOn
	
		if noFogOn then
			-- Ativar No-Fog
			lighting.FogEnd = 1000000
			lighting.FogStart = 0
		else
			-- Voltar ao normal
			lighting.FogEnd = originalFogEnd
			lighting.FogStart = originalFogStart
			lighting.FogColor = originalFogColor
		end
	end)
end;
task.spawn(C_69);
-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.Fullbright.LocalScript
local function C_6d()
local script = G2L["6d"];
	-- LocalScript com toggle fullbright
	local button = script.Parent
	local lighting = game:GetService("Lighting")
	
	-- Salvar valores originais
	local originalAmbient = lighting.Ambient
	local originalBrightness = lighting.Brightness
	local originalColorShiftTop = lighting.ColorShift_Top
	local originalColorShiftBottom = lighting.ColorShift_Bottom
	local originalOutdoorAmbient = lighting.OutdoorAmbient
	local originalGlobalShadows = lighting.GlobalShadows
	
	local fullbrightOn = false
	
	button.MouseButton1Click:Connect(function()
		fullbrightOn = not fullbrightOn
	
		if fullbrightOn then
			-- Ativar fullbright
			lighting.Ambient = Color3.new(1, 1, 1)
			lighting.Brightness = 2
			lighting.ColorShift_Top = Color3.new(1, 1, 1)
			lighting.ColorShift_Bottom = Color3.new(1, 1, 1)
			lighting.OutdoorAmbient = Color3.new(1, 1, 1)
			lighting.GlobalShadows = false
		else
			-- Voltar ao normal
			lighting.Ambient = originalAmbient
			lighting.Brightness = originalBrightness
			lighting.ColorShift_Top = originalColorShiftTop
			lighting.ColorShift_Bottom = originalColorShiftBottom
			lighting.OutdoorAmbient = originalOutdoorAmbient
			lighting.GlobalShadows = originalGlobalShadows
		end
	end)
end;
task.spawn(C_6d);
-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Pages.Misc.List.TextButton.LocalScript
local function C_74()
local script = G2L["74"];
	-- LocalScript dentro do botão (CLIENT-SIDE)
	local button = script.Parent
	local player = game:GetService("Players").LocalPlayer
	
	-- Função para mudar para plástico
	local function changeToPlastic(part)
		if part:IsA("BasePart") then
			part.Material = Enum.Material.Plastic
		end
	end
	
	-- Função principal
	local function changeAllBlocks()
		-- Mudar blocos no workspace
		for _, object in pairs(workspace:GetDescendants()) do
			changeToPlastic(object)
		end
	
		-- Mudar blocos no personagem do jogador
		if player.Character then
			for _, object in pairs(player.Character:GetDescendants()) do
				changeToPlastic(object)
			end
		end
	
		
	end
	
	-- Quando clicar no botão
	button.MouseButton1Click:Connect(changeAllBlocks)
end;
task.spawn(C_74);
-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.Home.LocalScript
local function C_79()
local script = G2L["79"];
	-- LocalScript dentro do botão Home
	local button = script.Parent
	local screenGui = button.Parent.Parent
	local pagesFrame = screenGui:FindFirstChild("Pages")
	
	button.MouseButton1Click:Connect(function()
		if pagesFrame then
			for _, page in pairs(pagesFrame:GetChildren()) do
				if page:IsA("Frame") or page:IsA("ScrollingFrame") then
					page.Visible = false
				end
			end
	
			local homePage = pagesFrame:FindFirstChild("Home")
			if homePage then
				homePage.Visible = true
			end
		end
	end)
end;
task.spawn(C_79);
-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.Farm.LocalScript
local function C_7b()
local script = G2L["7b"];
	-- LocalScript dentro do botão Farm
	local button = script.Parent
	local screenGui = button.Parent.Parent -- ScreenGui
	local pagesFrame = screenGui:FindFirstChild("Pages")
	
	button.MouseButton1Click:Connect(function()
		if pagesFrame then
			-- Esconder todas as páginas
			for _, page in pairs(pagesFrame:GetChildren()) do
				if page:IsA("Frame") or page:IsA("ScrollingFrame") then
					page.Visible = false
				end
			end
	
			-- Mostrar página Farm
			local farmPage = pagesFrame:FindFirstChild("Farm")
			if farmPage then
				farmPage.Visible = true
			end
		end
	end)
end;
task.spawn(C_7b);
-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.Scripts.LocalScript
local function C_7d()
local script = G2L["7d"];
	-- LocalScript dentro do botão Scripts
	local button = script.Parent
	local screenGui = button.Parent.Parent
	local pagesFrame = screenGui:FindFirstChild("Pages")
	
	button.MouseButton1Click:Connect(function()
		if pagesFrame then
			for _, page in pairs(pagesFrame:GetChildren()) do
				if page:IsA("Frame") or page:IsA("ScrollingFrame") then
					page.Visible = false
				end
			end
	
			local scriptsPage = pagesFrame:FindFirstChild("Scripts")
			if scriptsPage then
				scriptsPage.Visible = true
			end
		end
	end)
end;
task.spawn(C_7d);
-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.Itens.LocalScript
local function C_7f()
local script = G2L["7f"];
	-- LocalScript dentro do botão Itens
	local button = script.Parent
	local screenGui = button.Parent.Parent
	local pagesFrame = screenGui:FindFirstChild("Pages")
	
	button.MouseButton1Click:Connect(function()
		if pagesFrame then
			for _, page in pairs(pagesFrame:GetChildren()) do
				if page:IsA("Frame") or page:IsA("ScrollingFrame") then
					page.Visible = false
				end
			end
	
			local itensPage = pagesFrame:FindFirstChild("Itens")
			if itensPage then
				itensPage.Visible = true
			end
		end
	end)
end;
task.spawn(C_7f);
-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.AutoBuy.LocalScript
local function C_81()
local script = G2L["81"];
	-- LocalScript dentro do botão AutoBuy
	local button = script.Parent
	local screenGui = button.Parent.Parent
	local pagesFrame = screenGui:FindFirstChild("Pages")
	
	button.MouseButton1Click:Connect(function()
		if pagesFrame then
			for _, page in pairs(pagesFrame:GetChildren()) do
				if page:IsA("Frame") or page:IsA("ScrollingFrame") then
					page.Visible = false
				end
			end
	
			local autoBuyPage = pagesFrame:FindFirstChild("AutoBuy")
			if autoBuyPage then
				autoBuyPage.Visible = true
			end
		end
	end)
end;
task.spawn(C_81);
-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.Tools.LocalScript
local function C_83()
local script = G2L["83"];
	-- LocalScript dentro do botão Tools
	local button = script.Parent
	local screenGui = button.Parent.Parent
	local pagesFrame = screenGui:FindFirstChild("Pages")
	
	button.MouseButton1Click:Connect(function()
		if pagesFrame then
			for _, page in pairs(pagesFrame:GetChildren()) do
				if page:IsA("Frame") or page:IsA("ScrollingFrame") then
					page.Visible = false
				end
			end
	
			local toolsPage = pagesFrame:FindFirstChild("Tools")
			if toolsPage then
				toolsPage.Visible = true
			end
		end
	end)
end;
task.spawn(C_83);
-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Buttons.Misc.LocalScript
local function C_85()
local script = G2L["85"];
	-- LocalScript dentro do botão Misc
	local button = script.Parent
	local screenGui = button.Parent.Parent
	local pagesFrame = screenGui:FindFirstChild("Pages")
	
	button.MouseButton1Click:Connect(function()
		if pagesFrame then
			for _, page in pairs(pagesFrame:GetChildren()) do
				if page:IsA("Frame") or page:IsA("ScrollingFrame") then
					page.Visible = false
				end
			end
	
			local miscPage = pagesFrame:FindFirstChild("Misc")
			if miscPage then
				miscPage.Visible = true
			end
		end
	end)
end;
task.spawn(C_85);
-- StarterGui.BABFT.SagittariusHubBABFT.BackGround.Close.LocalScript
local function C_91()
local script = G2L["91"];
	-- LocalScript para fechar a ScreenGui
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		-- Procura o ancestral que seja a ScreenGui
		local screenGui = button:FindFirstAncestorOfClass("ScreenGui")
	
		if screenGui then
			-- Se você quiser que ela suma para sempre até você executar o script de novo:
			screenGui:Destroy()
	
			-- OU se você quiser apenas esconder para poder ligar depois:
			-- screenGui.Enabled = false
		end
	end)
end;
task.spawn(C_91);
-- StarterGui.BABFT.SagittariusHubBABFT.Dragify
local function C_92()
local script = G2L["92"];
	local UIS = game:GetService("UserInputService")
	local TweenService = game:GetService("TweenService")
	
	local function makeDraggable(frame)
		local dragging = false
		local dragInput
		local dragStart
		local startPos
	
		local function update(input)
			local delta = input.Position - dragStart
			local targetPos = UDim2.new(
				startPos.X.Scale, 
				startPos.X.Offset + delta.X, 
				startPos.Y.Scale, 
				startPos.Y.Offset + delta.Y
			)
	
			TweenService:Create(frame, TweenInfo.new(0.15), {Position = targetPos}):Play()
		end
	
		frame.InputBegan:Connect(function(input)
			if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then
				dragging = true
				dragStart = input.Position
				startPos = frame.Position
	
				input.Changed:Connect(function()
					if input.UserInputState == Enum.UserInputState.End then
						dragging = false
					end
				end)
			end
		end)
	
		frame.InputChanged:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
				dragInput = input
			end
		end)
	
		UIS.InputChanged:Connect(function(input)
			if input == dragInput and dragging then
				update(input)
			end
		end)
	end
	
	-- Busca o ImageLabel chamado "BackGround" que está no mesmo nível do script
	local background = script.Parent:FindFirstChild("BackGround")
	
	if background then
		makeDraggable(background)
	end
end;
task.spawn(C_92);

return G2L["1"], require;
