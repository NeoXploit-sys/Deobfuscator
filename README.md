--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 258 | Scripts: 30 | Modules: 1 | Tags: 0
local G2L = {};

-- Workspace.Gamepad Hub
G2L["1"] = Instance.new("ScreenGui", gethui());
G2L["1"]["Name"] = [[Gamepad Hub]];
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;


-- Workspace.Gamepad Hub.Hub
G2L["2"] = Instance.new("ScreenGui", G2L["1"]);
G2L["2"]["Name"] = [[Hub]];
G2L["2"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;


-- Workspace.Gamepad Hub.Hub.Frame
G2L["3"] = Instance.new("Frame", G2L["2"]);
G2L["3"]["BorderSizePixel"] = 0;
G2L["3"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3"]["Size"] = UDim2.new(0, 535, 0, 419);
G2L["3"]["Position"] = UDim2.new(0.17785, 0, 0.09722, 0);
G2L["3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Drag
G2L["4"] = Instance.new("LocalScript", G2L["3"]);
G2L["4"]["Name"] = [[Drag]];


-- Workspace.Gamepad Hub.Hub.Frame.UICorner
G2L["5"] = Instance.new("UICorner", G2L["3"]);



-- Workspace.Gamepad Hub.Hub.Frame.Frame
G2L["6"] = Instance.new("Frame", G2L["3"]);
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(62, 62, 62);
G2L["6"]["Size"] = UDim2.new(0, 535, 0, 2);
G2L["6"]["Position"] = UDim2.new(0, 0, 0.06444, 0);
G2L["6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Title
G2L["7"] = Instance.new("TextLabel", G2L["3"]);
G2L["7"]["TextWrapped"] = true;
G2L["7"]["BorderSizePixel"] = 0;
G2L["7"]["TextSize"] = 14;
G2L["7"]["TextScaled"] = true;
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["7"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7"]["BackgroundTransparency"] = 1;
G2L["7"]["Size"] = UDim2.new(0, 535, 0, 27);
G2L["7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["Text"] = [[Gamepad Hub V.1]];
G2L["7"]["Name"] = [[Title]];


-- Workspace.Gamepad Hub.Hub.Frame.Frame
G2L["8"] = Instance.new("Frame", G2L["3"]);
G2L["8"]["BorderSizePixel"] = 0;
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(62, 62, 62);
G2L["8"]["Size"] = UDim2.new(0, 2, 0, 392);
G2L["8"]["Position"] = UDim2.new(0.17009, 0, 0.06444, 0);
G2L["8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Buttons
G2L["9"] = Instance.new("Frame", G2L["3"]);
G2L["9"]["BorderSizePixel"] = 0;
G2L["9"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9"]["Size"] = UDim2.new(0, 100, 0, 100);
G2L["9"]["Position"] = UDim2.new(0.77196, 0, 0.75656, 0);
G2L["9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9"]["Name"] = [[Buttons]];
G2L["9"]["BackgroundTransparency"] = 1;


-- Workspace.Gamepad Hub.Hub.Frame.Buttons.LocalScript
G2L["a"] = Instance.new("LocalScript", G2L["9"]);



-- Workspace.Gamepad Hub.Hub.Frame.Buttons.Buttons
G2L["b"] = Instance.new("TextButton", G2L["9"]);
G2L["b"]["TextWrapped"] = true;
G2L["b"]["BorderSizePixel"] = 0;
G2L["b"]["TextSize"] = 14;
G2L["b"]["TextScaled"] = true;
G2L["b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["b"]["BackgroundTransparency"] = 1;
G2L["b"]["Size"] = UDim2.new(0, 74, 0, 50);
G2L["b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["Text"] = [[Buttons]];
G2L["b"]["Name"] = [[Buttons]];
G2L["b"]["Position"] = UDim2.new(-4.06692, 0, -2.26282, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Buttons.Combos
G2L["c"] = Instance.new("TextButton", G2L["9"]);
G2L["c"]["TextWrapped"] = true;
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["TextSize"] = 14;
G2L["c"]["TextScaled"] = true;
G2L["c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["c"]["BackgroundTransparency"] = 1;
G2L["c"]["Size"] = UDim2.new(0, 74, 0, 50);
G2L["c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["Text"] = [[Combos]];
G2L["c"]["Name"] = [[Combos]];
G2L["c"]["Position"] = UDim2.new(-4.06692, 0, -1.10597, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Buttons.Confing
G2L["d"] = Instance.new("TextButton", G2L["9"]);
G2L["d"]["TextWrapped"] = true;
G2L["d"]["BorderSizePixel"] = 0;
G2L["d"]["TextSize"] = 14;
G2L["d"]["TextScaled"] = true;
G2L["d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["d"]["BackgroundTransparency"] = 1;
G2L["d"]["Size"] = UDim2.new(0, 74, 0, 50);
G2L["d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d"]["Text"] = [[Confing]];
G2L["d"]["Name"] = [[Confing]];
G2L["d"]["Position"] = UDim2.new(-4.06692, 0, -0.1073, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Buttons.DashBoard
G2L["e"] = Instance.new("TextButton", G2L["9"]);
G2L["e"]["TextWrapped"] = true;
G2L["e"]["BorderSizePixel"] = 0;
G2L["e"]["TextSize"] = 14;
G2L["e"]["TextScaled"] = true;
G2L["e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["e"]["BackgroundTransparency"] = 1;
G2L["e"]["Size"] = UDim2.new(0, 74, 0, 50);
G2L["e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e"]["Text"] = [[Dashboard]];
G2L["e"]["Name"] = [[DashBoard]];
G2L["e"]["Position"] = UDim2.new(-4.06692, 0, -2.73215, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Buttons.Info
G2L["f"] = Instance.new("TextButton", G2L["9"]);
G2L["f"]["TextWrapped"] = true;
G2L["f"]["BorderSizePixel"] = 0;
G2L["f"]["TextSize"] = 14;
G2L["f"]["TextScaled"] = true;
G2L["f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["f"]["BackgroundTransparency"] = 1;
G2L["f"]["Size"] = UDim2.new(0, 74, 0, 50);
G2L["f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f"]["Text"] = [[Info]];
G2L["f"]["Name"] = [[Info]];
G2L["f"]["Position"] = UDim2.new(-4.06692, 0, 0.39203, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Buttons.Thumbsticks
G2L["10"] = Instance.new("TextButton", G2L["9"]);
G2L["10"]["TextWrapped"] = true;
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["TextSize"] = 14;
G2L["10"]["TextScaled"] = true;
G2L["10"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["10"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["10"]["BackgroundTransparency"] = 1;
G2L["10"]["Size"] = UDim2.new(0, 74, 0, 50);
G2L["10"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["Text"] = [[Thumbsticks]];
G2L["10"]["Name"] = [[Thumbsticks]];
G2L["10"]["Position"] = UDim2.new(-4.06692, 0, -1.66962, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Buttons.Vibration
G2L["11"] = Instance.new("TextButton", G2L["9"]);
G2L["11"]["TextWrapped"] = true;
G2L["11"]["BorderSizePixel"] = 0;
G2L["11"]["TextSize"] = 14;
G2L["11"]["TextScaled"] = true;
G2L["11"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["11"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["11"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["11"]["BackgroundTransparency"] = 1;
G2L["11"]["Size"] = UDim2.new(0, 74, 0, 50);
G2L["11"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["Text"] = [[Vibration]];
G2L["11"]["Name"] = [[Vibration]];
G2L["11"]["Position"] = UDim2.new(-4.06692, 0, -0.60663, 0);


-- Workspace.Gamepad Hub.Hub.Frame.User
G2L["12"] = Instance.new("ImageLabel", G2L["3"]);
G2L["12"]["BorderSizePixel"] = 0;
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["12"]["Image"] = [[rbxasset://textures/ui/GuiImagePlaceholder.png]];
G2L["12"]["Size"] = UDim2.new(0, 100, 0, 100);
G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["BackgroundTransparency"] = 1;
G2L["12"]["Name"] = [[User]];
G2L["12"]["Position"] = UDim2.new(0.19813, 0, 0.09785, 0);


-- Workspace.Gamepad Hub.Hub.Frame.User.LocalScript
G2L["13"] = Instance.new("LocalScript", G2L["12"]);



-- Workspace.Gamepad Hub.Hub.Frame.Username
G2L["14"] = Instance.new("TextLabel", G2L["3"]);
G2L["14"]["TextWrapped"] = true;
G2L["14"]["BorderSizePixel"] = 0;
G2L["14"]["TextSize"] = 14;
G2L["14"]["TextScaled"] = true;
G2L["14"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["14"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["14"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["14"]["BackgroundTransparency"] = 1;
G2L["14"]["Size"] = UDim2.new(0, 114, 0, 27);
G2L["14"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["14"]["Text"] = [[Loading....]];
G2L["14"]["Name"] = [[Username]];
G2L["14"]["Position"] = UDim2.new(0.18505, 0, 0.33652, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Username.LocalScript
G2L["15"] = Instance.new("LocalScript", G2L["14"]);



-- Workspace.Gamepad Hub.Hub.Frame.Username.Welcome
G2L["16"] = Instance.new("TextLabel", G2L["14"]);
G2L["16"]["TextWrapped"] = true;
G2L["16"]["BorderSizePixel"] = 0;
G2L["16"]["TextSize"] = 14;
G2L["16"]["TextScaled"] = true;
G2L["16"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["16"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["16"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["16"]["BackgroundTransparency"] = 1;
G2L["16"]["Size"] = UDim2.new(0, 187, 0, 107);
G2L["16"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["Text"] = [[Loading....]];
G2L["16"]["Name"] = [[Welcome]];
G2L["16"]["Position"] = UDim2.new(1.34463, 0, -3.59516, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Username.Welcome.script
G2L["17"] = Instance.new("LocalScript", G2L["16"]);
G2L["17"]["Name"] = [[script]];


-- Workspace.Gamepad Hub.Hub.Frame.Username.Gamepad Connected
G2L["18"] = Instance.new("TextLabel", G2L["14"]);
G2L["18"]["TextWrapped"] = true;
G2L["18"]["BorderSizePixel"] = 0;
G2L["18"]["TextSize"] = 14;
G2L["18"]["TextScaled"] = true;
G2L["18"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["18"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["18"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["18"]["BackgroundTransparency"] = 1;
G2L["18"]["Size"] = UDim2.new(0, 114, 0, 27);
G2L["18"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["18"]["Text"] = [[Loading....]];
G2L["18"]["Name"] = [[Gamepad Connected]];
G2L["18"]["Position"] = UDim2.new(-0.00794, 0, 8.3968, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Username.Gamepad Connected.script
G2L["19"] = Instance.new("LocalScript", G2L["18"]);
G2L["19"]["Name"] = [[script]];


-- Workspace.Gamepad Hub.Hub.Frame.realtime
G2L["1a"] = Instance.new("TextLabel", G2L["3"]);
G2L["1a"]["TextWrapped"] = true;
G2L["1a"]["BorderSizePixel"] = 0;
G2L["1a"]["TextSize"] = 14;
G2L["1a"]["TextScaled"] = true;
G2L["1a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["1a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1a"]["BackgroundTransparency"] = 1;
G2L["1a"]["Size"] = UDim2.new(0, 114, 0, 27);
G2L["1a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1a"]["Text"] = [[Loading....]];
G2L["1a"]["Name"] = [[realtime]];
G2L["1a"]["Position"] = UDim2.new(0.18505, 0, 0.42959, 0);


-- Workspace.Gamepad Hub.Hub.Frame.realtime.script
G2L["1b"] = Instance.new("LocalScript", G2L["1a"]);
G2L["1b"]["Name"] = [[script]];


-- Workspace.Gamepad Hub.Hub.Frame.svtime
G2L["1c"] = Instance.new("TextLabel", G2L["3"]);
G2L["1c"]["TextWrapped"] = true;
G2L["1c"]["BorderSizePixel"] = 0;
G2L["1c"]["TextSize"] = 14;
G2L["1c"]["TextScaled"] = true;
G2L["1c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["1c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1c"]["BackgroundTransparency"] = 1;
G2L["1c"]["Size"] = UDim2.new(0, 114, 0, 27);
G2L["1c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1c"]["Text"] = [[Loading....]];
G2L["1c"]["Name"] = [[svtime]];
G2L["1c"]["Position"] = UDim2.new(0.18505, 0, 0.52029, 0);


-- Workspace.Gamepad Hub.Hub.Frame.svtime.script
G2L["1d"] = Instance.new("LocalScript", G2L["1c"]);
G2L["1d"]["Name"] = [[script]];


-- Workspace.Gamepad Hub.Hub.Frame.jobid
G2L["1e"] = Instance.new("TextLabel", G2L["3"]);
G2L["1e"]["TextWrapped"] = true;
G2L["1e"]["BorderSizePixel"] = 0;
G2L["1e"]["TextSize"] = 14;
G2L["1e"]["TextScaled"] = true;
G2L["1e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["1e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1e"]["BackgroundTransparency"] = 1;
G2L["1e"]["Size"] = UDim2.new(0, 114, 0, 27);
G2L["1e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["Text"] = [[Loading....]];
G2L["1e"]["Name"] = [[jobid]];
G2L["1e"]["Position"] = UDim2.new(0.18505, 0, 0.61337, 0);


-- Workspace.Gamepad Hub.Hub.Frame.jobid.script
G2L["1f"] = Instance.new("LocalScript", G2L["1e"]);
G2L["1f"]["Name"] = [[script]];


-- Workspace.Gamepad Hub.Hub.Frame.progress
G2L["20"] = Instance.new("TextLabel", G2L["3"]);
G2L["20"]["TextWrapped"] = true;
G2L["20"]["BorderSizePixel"] = 0;
G2L["20"]["TextSize"] = 14;
G2L["20"]["TextScaled"] = true;
G2L["20"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["20"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["20"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["20"]["BackgroundTransparency"] = 1;
G2L["20"]["Size"] = UDim2.new(0, 114, 0, 27);
G2L["20"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["20"]["Text"] = [[Loading....]];
G2L["20"]["Name"] = [[progress]];
G2L["20"]["Position"] = UDim2.new(0.18505, 0, 0.69212, 0);


-- Workspace.Gamepad Hub.Hub.Frame.progress.LocalScript
G2L["21"] = Instance.new("LocalScript", G2L["20"]);



-- Workspace.Gamepad Hub.Hub.Frame.age
G2L["22"] = Instance.new("TextLabel", G2L["3"]);
G2L["22"]["TextWrapped"] = true;
G2L["22"]["BorderSizePixel"] = 0;
G2L["22"]["TextSize"] = 14;
G2L["22"]["TextScaled"] = true;
G2L["22"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["22"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["22"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["22"]["BackgroundTransparency"] = 1;
G2L["22"]["Size"] = UDim2.new(0, 114, 0, 27);
G2L["22"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["22"]["Text"] = [[Loading....]];
G2L["22"]["Name"] = [[age]];
G2L["22"]["Position"] = UDim2.new(0.18505, 0, 0.78759, 0);


-- Workspace.Gamepad Hub.Hub.Frame.age.LocalScript
G2L["23"] = Instance.new("LocalScript", G2L["22"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages
G2L["24"] = Instance.new("Frame", G2L["3"]);
G2L["24"]["BorderSizePixel"] = 0;
G2L["24"]["BackgroundColor3"] = Color3.fromRGB(5, 5, 5);
G2L["24"]["Size"] = UDim2.new(0, 100, 0, 100);
G2L["24"]["Position"] = UDim2.new(0.78692, 0, 0.75656, 0);
G2L["24"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["24"]["Name"] = [[Pages]];
G2L["24"]["BackgroundTransparency"] = 1;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons
G2L["25"] = Instance.new("Frame", G2L["24"]);
G2L["25"]["Visible"] = false;
G2L["25"]["BorderSizePixel"] = 0;
G2L["25"]["BackgroundColor3"] = Color3.fromRGB(11, 15, 22);
G2L["25"]["Size"] = UDim2.new(4.42, 0, 3.88, 0);
G2L["25"]["Position"] = UDim2.new(-3.28, 0, -2.88, 0);
G2L["25"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["25"]["Name"] = [[Buttons]];


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.LocalScript
G2L["26"] = Instance.new("LocalScript", G2L["25"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.ModuleScript
G2L["27"] = Instance.new("ModuleScript", G2L["25"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox
G2L["28"] = Instance.new("Frame", G2L["25"]);
G2L["28"]["BorderSizePixel"] = 0;
G2L["28"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["28"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["28"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["28"]["Name"] = [[Xbox]];
G2L["28"]["BackgroundTransparency"] = 1;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame
G2L["29"] = Instance.new("Frame", G2L["28"]);
G2L["29"]["BorderSizePixel"] = 0;
G2L["29"]["BackgroundColor3"] = Color3.fromRGB(44, 44, 44);
G2L["29"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["29"]["Size"] = UDim2.new(0.63073, 0, 0.54378, 0);
G2L["29"]["Position"] = UDim2.new(0.49432, 0, 0.55746, 0);
G2L["29"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["29"]["Name"] = [[MainFrame]];


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.UICorner
G2L["2a"] = Instance.new("UICorner", G2L["29"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.UIStroke
G2L["2b"] = Instance.new("UIStroke", G2L["29"]);
G2L["2b"]["Thickness"] = 6.4;
G2L["2b"]["Color"] = Color3.fromRGB(60, 60, 60);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons
G2L["2c"] = Instance.new("Frame", G2L["29"]);
G2L["2c"]["BorderSizePixel"] = 0;
G2L["2c"]["BackgroundColor3"] = Color3.fromRGB(84, 84, 84);
G2L["2c"]["Size"] = UDim2.new(0.21818, 0, 0.41509, 0);
G2L["2c"]["Position"] = UDim2.new(0.73223, 0, 0.1001, 0);
G2L["2c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2c"]["Name"] = [[Buttons]];


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.UICorner
G2L["2d"] = Instance.new("UICorner", G2L["2c"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.UIStroke
G2L["2e"] = Instance.new("UIStroke", G2L["2c"]);
G2L["2e"]["Thickness"] = 6.4;
G2L["2e"]["Color"] = Color3.fromRGB(60, 60, 60);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.X
G2L["2f"] = Instance.new("TextLabel", G2L["2c"]);
G2L["2f"]["TextWrapped"] = true;
G2L["2f"]["BorderSizePixel"] = 0;
G2L["2f"]["TextSize"] = 14;
G2L["2f"]["TextScaled"] = true;
G2L["2f"]["BackgroundColor3"] = Color3.fromRGB(60, 60, 60);
G2L["2f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2f"]["TextColor3"] = Color3.fromRGB(45, 3, 255);
G2L["2f"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["2f"]["Size"] = UDim2.new(0.2803, 0, 0.28788, 0);
G2L["2f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2f"]["Text"] = [[X]];
G2L["2f"]["Name"] = [[X]];
G2L["2f"]["Position"] = UDim2.new(0.202, 0, 0.483, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.X.UICorner
G2L["30"] = Instance.new("UICorner", G2L["2f"]);
G2L["30"]["CornerRadius"] = UDim.new(100, 100);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.X.UIStroke
G2L["31"] = Instance.new("UIStroke", G2L["2f"]);
G2L["31"]["Thickness"] = 2.9;
G2L["31"]["Color"] = Color3.fromRGB(112, 112, 112);
G2L["31"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.X.UIPadding
G2L["32"] = Instance.new("UIPadding", G2L["2f"]);
G2L["32"]["PaddingTop"] = UDim.new(0.00526, 0);
G2L["32"]["PaddingRight"] = UDim.new(0.27937, 0);
G2L["32"]["PaddingLeft"] = UDim.new(0.27937, 0);
G2L["32"]["PaddingBottom"] = UDim.new(0.00526, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.X.UIAspectRatioConstraint
G2L["33"] = Instance.new("UIAspectRatioConstraint", G2L["2f"]);
G2L["33"]["AspectRatio"] = 0.95419;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.A
G2L["34"] = Instance.new("TextLabel", G2L["2c"]);
G2L["34"]["TextWrapped"] = true;
G2L["34"]["BorderSizePixel"] = 0;
G2L["34"]["TextSize"] = 14;
G2L["34"]["TextScaled"] = true;
G2L["34"]["BackgroundColor3"] = Color3.fromRGB(60, 60, 60);
G2L["34"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["34"]["TextColor3"] = Color3.fromRGB(230, 255, 0);
G2L["34"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["34"]["Size"] = UDim2.new(0.2803, 0, 0.28788, 0);
G2L["34"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["34"]["Text"] = [[A]];
G2L["34"]["Name"] = [[A]];
G2L["34"]["Position"] = UDim2.new(0.5, 0, 0.789, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.A.UICorner
G2L["35"] = Instance.new("UICorner", G2L["34"]);
G2L["35"]["CornerRadius"] = UDim.new(100, 100);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.A.UIStroke
G2L["36"] = Instance.new("UIStroke", G2L["34"]);
G2L["36"]["Thickness"] = 2.9;
G2L["36"]["Color"] = Color3.fromRGB(112, 112, 112);
G2L["36"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.A.UIPadding
G2L["37"] = Instance.new("UIPadding", G2L["34"]);
G2L["37"]["PaddingTop"] = UDim.new(0.00526, 0);
G2L["37"]["PaddingRight"] = UDim.new(0.26834, 0);
G2L["37"]["PaddingLeft"] = UDim.new(0.26834, 0);
G2L["37"]["PaddingBottom"] = UDim.new(0.00526, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.A.UIAspectRatioConstraint
G2L["38"] = Instance.new("UIAspectRatioConstraint", G2L["34"]);
G2L["38"]["AspectRatio"] = 0.95419;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.B
G2L["39"] = Instance.new("TextLabel", G2L["2c"]);
G2L["39"]["TextWrapped"] = true;
G2L["39"]["BorderSizePixel"] = 0;
G2L["39"]["TextSize"] = 14;
G2L["39"]["TextScaled"] = true;
G2L["39"]["BackgroundColor3"] = Color3.fromRGB(60, 60, 60);
G2L["39"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["39"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["39"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["39"]["Size"] = UDim2.new(0.2803, 0, 0.28788, 0);
G2L["39"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["39"]["Text"] = [[B]];
G2L["39"]["Name"] = [[B]];
G2L["39"]["Position"] = UDim2.new(0.807, 0, 0.485, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.B.UICorner
G2L["3a"] = Instance.new("UICorner", G2L["39"]);
G2L["3a"]["CornerRadius"] = UDim.new(100, 100);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.B.UIStroke
G2L["3b"] = Instance.new("UIStroke", G2L["39"]);
G2L["3b"]["Thickness"] = 2.9;
G2L["3b"]["Color"] = Color3.fromRGB(112, 112, 112);
G2L["3b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.B.UIPadding
G2L["3c"] = Instance.new("UIPadding", G2L["39"]);
G2L["3c"]["PaddingTop"] = UDim.new(0.00526, 0);
G2L["3c"]["PaddingRight"] = UDim.new(0.2573, 0);
G2L["3c"]["PaddingLeft"] = UDim.new(0.2573, 0);
G2L["3c"]["PaddingBottom"] = UDim.new(0.00526, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.B.UIAspectRatioConstraint
G2L["3d"] = Instance.new("UIAspectRatioConstraint", G2L["39"]);
G2L["3d"]["AspectRatio"] = 0.95419;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.Y
G2L["3e"] = Instance.new("TextLabel", G2L["2c"]);
G2L["3e"]["TextWrapped"] = true;
G2L["3e"]["BorderSizePixel"] = 0;
G2L["3e"]["TextSize"] = 14;
G2L["3e"]["TextScaled"] = true;
G2L["3e"]["BackgroundColor3"] = Color3.fromRGB(60, 60, 60);
G2L["3e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3e"]["TextColor3"] = Color3.fromRGB(27, 255, 0);
G2L["3e"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["3e"]["Size"] = UDim2.new(0.2803, 0, 0.28788, 0);
G2L["3e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3e"]["Text"] = [[Y]];
G2L["3e"]["Name"] = [[Y]];
G2L["3e"]["Position"] = UDim2.new(0.5, 0, 0.20059, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.Y.UICorner
G2L["3f"] = Instance.new("UICorner", G2L["3e"]);
G2L["3f"]["CornerRadius"] = UDim.new(100, 100);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.Y.UIStroke
G2L["40"] = Instance.new("UIStroke", G2L["3e"]);
G2L["40"]["Thickness"] = 2.9;
G2L["40"]["Color"] = Color3.fromRGB(112, 112, 112);
G2L["40"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.Y.UIPadding
G2L["41"] = Instance.new("UIPadding", G2L["3e"]);
G2L["41"]["PaddingTop"] = UDim.new(0.00526, 0);
G2L["41"]["PaddingRight"] = UDim.new(0.30143, 0);
G2L["41"]["PaddingLeft"] = UDim.new(0.30143, 0);
G2L["41"]["PaddingBottom"] = UDim.new(0.00526, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Buttons.Y.UIAspectRatioConstraint
G2L["42"] = Instance.new("UIAspectRatioConstraint", G2L["3e"]);
G2L["42"]["AspectRatio"] = 0.95419;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Dpad
G2L["43"] = Instance.new("Frame", G2L["29"]);
G2L["43"]["BorderSizePixel"] = 0;
G2L["43"]["BackgroundColor3"] = Color3.fromRGB(84, 84, 84);
G2L["43"]["Size"] = UDim2.new(0.19504, 0, 0.37107, 0);
G2L["43"]["Position"] = UDim2.new(0.2314, 0, 0.57809, 0);
G2L["43"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["43"]["Name"] = [[Dpad]];


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Dpad.UICorner
G2L["44"] = Instance.new("UICorner", G2L["43"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Dpad.UIStroke
G2L["45"] = Instance.new("UIStroke", G2L["43"]);
G2L["45"]["Thickness"] = 6.4;
G2L["45"]["Color"] = Color3.fromRGB(60, 60, 60);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Dpad.Down
G2L["46"] = Instance.new("TextLabel", G2L["43"]);
G2L["46"]["TextWrapped"] = true;
G2L["46"]["BorderSizePixel"] = 0;
G2L["46"]["TextSize"] = 14;
G2L["46"]["TextScaled"] = true;
G2L["46"]["BackgroundColor3"] = Color3.fromRGB(60, 60, 60);
G2L["46"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["46"]["TextColor3"] = Color3.fromRGB(27, 255, 0);
G2L["46"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["46"]["Size"] = UDim2.new(0.20455, 0, 0.29545, 0);
G2L["46"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["46"]["Text"] = [[]];
G2L["46"]["Name"] = [[Down]];
G2L["46"]["Position"] = UDim2.new(0.5, 0, 0.76696, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Dpad.Down.UICorner
G2L["47"] = Instance.new("UICorner", G2L["46"]);
G2L["47"]["CornerRadius"] = UDim.new(0.15, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Dpad.Down.UIStroke
G2L["48"] = Instance.new("UIStroke", G2L["46"]);
G2L["48"]["Thickness"] = 2.9;
G2L["48"]["Color"] = Color3.fromRGB(112, 112, 112);
G2L["48"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Dpad.Up
G2L["49"] = Instance.new("TextLabel", G2L["43"]);
G2L["49"]["TextWrapped"] = true;
G2L["49"]["BorderSizePixel"] = 0;
G2L["49"]["TextSize"] = 14;
G2L["49"]["TextScaled"] = true;
G2L["49"]["BackgroundColor3"] = Color3.fromRGB(60, 60, 60);
G2L["49"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["49"]["TextColor3"] = Color3.fromRGB(27, 255, 0);
G2L["49"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["49"]["Size"] = UDim2.new(0.20455, 0, 0.29545, 0);
G2L["49"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["49"]["Text"] = [[]];
G2L["49"]["Name"] = [[Up]];
G2L["49"]["Position"] = UDim2.new(0.5, 0, 0.22908, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Dpad.Up.UICorner
G2L["4a"] = Instance.new("UICorner", G2L["49"]);
G2L["4a"]["CornerRadius"] = UDim.new(0.15, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Dpad.Up.UIStroke
G2L["4b"] = Instance.new("UIStroke", G2L["49"]);
G2L["4b"]["Thickness"] = 2.9;
G2L["4b"]["Color"] = Color3.fromRGB(112, 112, 112);
G2L["4b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Dpad.Right
G2L["4c"] = Instance.new("TextLabel", G2L["43"]);
G2L["4c"]["TextWrapped"] = true;
G2L["4c"]["BorderSizePixel"] = 0;
G2L["4c"]["TextSize"] = 14;
G2L["4c"]["TextScaled"] = true;
G2L["4c"]["BackgroundColor3"] = Color3.fromRGB(60, 60, 60);
G2L["4c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4c"]["TextColor3"] = Color3.fromRGB(27, 255, 0);
G2L["4c"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["4c"]["Size"] = UDim2.new(0.29545, 0, 0.20455, 0);
G2L["4c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4c"]["Text"] = [[]];
G2L["4c"]["Name"] = [[Right]];
G2L["4c"]["Position"] = UDim2.new(0.795, 0, 0.5, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Dpad.Right.UICorner
G2L["4d"] = Instance.new("UICorner", G2L["4c"]);
G2L["4d"]["CornerRadius"] = UDim.new(0.15, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Dpad.Right.UIStroke
G2L["4e"] = Instance.new("UIStroke", G2L["4c"]);
G2L["4e"]["Thickness"] = 2.9;
G2L["4e"]["Color"] = Color3.fromRGB(112, 112, 112);
G2L["4e"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Dpad.Left
G2L["4f"] = Instance.new("TextLabel", G2L["43"]);
G2L["4f"]["TextWrapped"] = true;
G2L["4f"]["BorderSizePixel"] = 0;
G2L["4f"]["TextSize"] = 14;
G2L["4f"]["TextScaled"] = true;
G2L["4f"]["BackgroundColor3"] = Color3.fromRGB(60, 60, 60);
G2L["4f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4f"]["TextColor3"] = Color3.fromRGB(27, 255, 0);
G2L["4f"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["4f"]["Size"] = UDim2.new(0.29545, 0, 0.20455, 0);
G2L["4f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4f"]["Text"] = [[]];
G2L["4f"]["Name"] = [[Left]];
G2L["4f"]["Position"] = UDim2.new(0.2, 0, 0.5, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Dpad.Left.UICorner
G2L["50"] = Instance.new("UICorner", G2L["4f"]);
G2L["50"]["CornerRadius"] = UDim.new(0.15, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Dpad.Left.UIStroke
G2L["51"] = Instance.new("UIStroke", G2L["4f"]);
G2L["51"]["Thickness"] = 2.9;
G2L["51"]["Color"] = Color3.fromRGB(112, 112, 112);
G2L["51"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LeftAnalog
G2L["52"] = Instance.new("Frame", G2L["29"]);
G2L["52"]["BorderSizePixel"] = 0;
G2L["52"]["BackgroundColor3"] = Color3.fromRGB(84, 84, 84);
G2L["52"]["Size"] = UDim2.new(0.21818, 0, 0.41509, 0);
G2L["52"]["Position"] = UDim2.new(0.04298, 0, 0.1001, 0);
G2L["52"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["52"]["Name"] = [[LeftAnalog]];


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LeftAnalog.UICorner
G2L["53"] = Instance.new("UICorner", G2L["52"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LeftAnalog.UIStroke
G2L["54"] = Instance.new("UIStroke", G2L["52"]);
G2L["54"]["Thickness"] = 6.4;
G2L["54"]["Color"] = Color3.fromRGB(60, 60, 60);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LeftAnalog.TextLabel
G2L["55"] = Instance.new("TextLabel", G2L["52"]);
G2L["55"]["TextWrapped"] = true;
G2L["55"]["BorderSizePixel"] = 0;
G2L["55"]["TextSize"] = 14;
G2L["55"]["TextScaled"] = true;
G2L["55"]["BackgroundColor3"] = Color3.fromRGB(60, 60, 60);
G2L["55"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["55"]["TextColor3"] = Color3.fromRGB(138, 139, 137);
G2L["55"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["55"]["Size"] = UDim2.new(0.49242, 0, 0.49242, 0);
G2L["55"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["55"]["Text"] = [[L]];
G2L["55"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LeftAnalog.TextLabel.UICorner
G2L["56"] = Instance.new("UICorner", G2L["55"]);
G2L["56"]["CornerRadius"] = UDim.new(0.15, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LeftAnalog.TextLabel.UIStroke
G2L["57"] = Instance.new("UIStroke", G2L["55"]);
G2L["57"]["Thickness"] = 2.9;
G2L["57"]["Color"] = Color3.fromRGB(112, 112, 112);
G2L["57"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RightAnalog
G2L["58"] = Instance.new("Frame", G2L["29"]);
G2L["58"]["BorderSizePixel"] = 0;
G2L["58"]["BackgroundColor3"] = Color3.fromRGB(84, 84, 84);
G2L["58"]["Size"] = UDim2.new(0.19504, 0, 0.37107, 0);
G2L["58"]["Position"] = UDim2.new(0.57521, 0, 0.57809, 0);
G2L["58"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["58"]["Name"] = [[RightAnalog]];


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RightAnalog.UICorner
G2L["59"] = Instance.new("UICorner", G2L["58"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RightAnalog.UIStroke
G2L["5a"] = Instance.new("UIStroke", G2L["58"]);
G2L["5a"]["Thickness"] = 6.4;
G2L["5a"]["Color"] = Color3.fromRGB(60, 60, 60);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RightAnalog.TextLabel
G2L["5b"] = Instance.new("TextLabel", G2L["58"]);
G2L["5b"]["TextWrapped"] = true;
G2L["5b"]["BorderSizePixel"] = 0;
G2L["5b"]["TextSize"] = 14;
G2L["5b"]["TextScaled"] = true;
G2L["5b"]["BackgroundColor3"] = Color3.fromRGB(60, 60, 60);
G2L["5b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5b"]["TextColor3"] = Color3.fromRGB(138, 139, 137);
G2L["5b"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["5b"]["Size"] = UDim2.new(0.55085, 0, 0.55085, 0);
G2L["5b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5b"]["Text"] = [[R]];
G2L["5b"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RightAnalog.TextLabel.UICorner
G2L["5c"] = Instance.new("UICorner", G2L["5b"]);
G2L["5c"]["CornerRadius"] = UDim.new(0.15, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RightAnalog.TextLabel.UIStroke
G2L["5d"] = Instance.new("UIStroke", G2L["5b"]);
G2L["5d"]["Thickness"] = 2.9;
G2L["5d"]["Color"] = Color3.fromRGB(112, 112, 112);
G2L["5d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Select
G2L["5e"] = Instance.new("TextLabel", G2L["29"]);
G2L["5e"]["TextWrapped"] = true;
G2L["5e"]["BorderSizePixel"] = 0;
G2L["5e"]["TextSize"] = 14;
G2L["5e"]["TextScaled"] = true;
G2L["5e"]["BackgroundColor3"] = Color3.fromRGB(60, 60, 60);
G2L["5e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5e"]["TextColor3"] = Color3.fromRGB(138, 139, 137);
G2L["5e"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["5e"]["Size"] = UDim2.new(0.13809, 0, 0.08573, 0);
G2L["5e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5e"]["Text"] = [[Select]];
G2L["5e"]["Name"] = [[Select]];
G2L["5e"]["Position"] = UDim2.new(0.37673, 0, 0.24831, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Select.UICorner
G2L["5f"] = Instance.new("UICorner", G2L["5e"]);
G2L["5f"]["CornerRadius"] = UDim.new(0.15, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Select.UIStroke
G2L["60"] = Instance.new("UIStroke", G2L["5e"]);
G2L["60"]["Thickness"] = 2.9;
G2L["60"]["Color"] = Color3.fromRGB(112, 112, 112);
G2L["60"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Start
G2L["61"] = Instance.new("TextLabel", G2L["29"]);
G2L["61"]["TextWrapped"] = true;
G2L["61"]["BorderSizePixel"] = 0;
G2L["61"]["TextSize"] = 14;
G2L["61"]["TextScaled"] = true;
G2L["61"]["BackgroundColor3"] = Color3.fromRGB(60, 60, 60);
G2L["61"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["61"]["TextColor3"] = Color3.fromRGB(138, 139, 137);
G2L["61"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["61"]["Size"] = UDim2.new(0.13809, 0, 0.08573, 0);
G2L["61"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["61"]["Text"] = [[Start]];
G2L["61"]["Name"] = [[Start]];
G2L["61"]["Position"] = UDim2.new(0.6164, 0, 0.24831, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Start.UICorner
G2L["62"] = Instance.new("UICorner", G2L["61"]);
G2L["62"]["CornerRadius"] = UDim.new(0.15, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.Start.UIStroke
G2L["63"] = Instance.new("UIStroke", G2L["61"]);
G2L["63"]["Thickness"] = 2.9;
G2L["63"]["Color"] = Color3.fromRGB(112, 112, 112);
G2L["63"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.UIAspectRatioConstraint
G2L["64"] = Instance.new("UIAspectRatioConstraint", G2L["29"]);
G2L["64"]["AspectRatio"] = 1.86443;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LButtons
G2L["65"] = Instance.new("Frame", G2L["29"]);
G2L["65"]["BorderSizePixel"] = 0;
G2L["65"]["BackgroundColor3"] = Color3.fromRGB(44, 44, 44);
G2L["65"]["AnchorPoint"] = Vector2.new(0, 0.5);
G2L["65"]["Size"] = UDim2.new(0.25748, 0, 0.29407, 0);
G2L["65"]["Position"] = UDim2.new(0, 0, -0.171, 0);
G2L["65"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["65"]["Name"] = [[LButtons]];


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LButtons.UICorner
G2L["66"] = Instance.new("UICorner", G2L["65"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LButtons.UIStroke
G2L["67"] = Instance.new("UIStroke", G2L["65"]);
G2L["67"]["Thickness"] = 6.4;
G2L["67"]["Color"] = Color3.fromRGB(60, 60, 60);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LButtons.LT
G2L["68"] = Instance.new("TextLabel", G2L["65"]);
G2L["68"]["TextWrapped"] = true;
G2L["68"]["BorderSizePixel"] = 0;
G2L["68"]["TextSize"] = 14;
G2L["68"]["TextScaled"] = true;
G2L["68"]["BackgroundColor3"] = Color3.fromRGB(116, 116, 116);
G2L["68"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["68"]["TextColor3"] = Color3.fromRGB(138, 139, 137);
G2L["68"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["68"]["Size"] = UDim2.new(0.85379, 0, 0.44166, 0);
G2L["68"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["68"]["Text"] = [[LT]];
G2L["68"]["Name"] = [[LT]];
G2L["68"]["Position"] = UDim2.new(0.49822, 0, 0.3299, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LButtons.LT.UICorner
G2L["69"] = Instance.new("UICorner", G2L["68"]);
G2L["69"]["CornerRadius"] = UDim.new(0.15, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LButtons.LT.UIStroke
G2L["6a"] = Instance.new("UIStroke", G2L["68"]);
G2L["6a"]["Thickness"] = 2.9;
G2L["6a"]["Color"] = Color3.fromRGB(112, 112, 112);
G2L["6a"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LButtons.LB
G2L["6b"] = Instance.new("TextLabel", G2L["65"]);
G2L["6b"]["TextWrapped"] = true;
G2L["6b"]["BorderSizePixel"] = 0;
G2L["6b"]["TextSize"] = 14;
G2L["6b"]["TextScaled"] = true;
G2L["6b"]["BackgroundColor3"] = Color3.fromRGB(60, 60, 60);
G2L["6b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6b"]["TextColor3"] = Color3.fromRGB(138, 139, 137);
G2L["6b"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["6b"]["Size"] = UDim2.new(0.85379, 0, 0.20455, 0);
G2L["6b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6b"]["Text"] = [[LB]];
G2L["6b"]["Name"] = [[LB]];
G2L["6b"]["Position"] = UDim2.new(0.49822, 0, 0.79897, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LButtons.LB.UICorner
G2L["6c"] = Instance.new("UICorner", G2L["6b"]);
G2L["6c"]["CornerRadius"] = UDim.new(0.15, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LButtons.LB.UIStroke
G2L["6d"] = Instance.new("UIStroke", G2L["6b"]);
G2L["6d"]["Thickness"] = 2.9;
G2L["6d"]["Color"] = Color3.fromRGB(112, 112, 112);
G2L["6d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LButtons.UIAspectRatioConstraint
G2L["6e"] = Instance.new("UIAspectRatioConstraint", G2L["65"]);
G2L["6e"]["AspectRatio"] = 1.47471;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LButtons.Trigger
G2L["6f"] = Instance.new("TextLabel", G2L["65"]);
G2L["6f"]["TextWrapped"] = true;
G2L["6f"]["BorderSizePixel"] = 0;
G2L["6f"]["TextSize"] = 14;
G2L["6f"]["TextScaled"] = true;
G2L["6f"]["BackgroundColor3"] = Color3.fromRGB(60, 60, 60);
G2L["6f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6f"]["TextColor3"] = Color3.fromRGB(138, 139, 137);
G2L["6f"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["6f"]["Size"] = UDim2.new(0.85379, 0, 0.44166, 0);
G2L["6f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6f"]["Text"] = [[LT]];
G2L["6f"]["Name"] = [[Trigger]];
G2L["6f"]["Position"] = UDim2.new(0.49822, 0, 0.3299, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LButtons.Trigger.UICorner
G2L["70"] = Instance.new("UICorner", G2L["6f"]);
G2L["70"]["CornerRadius"] = UDim.new(0.15, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LButtons.Trigger.UIStroke
G2L["71"] = Instance.new("UIStroke", G2L["6f"]);
G2L["71"]["Thickness"] = 2.9;
G2L["71"]["Color"] = Color3.fromRGB(112, 112, 112);
G2L["71"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RButtons
G2L["72"] = Instance.new("Frame", G2L["29"]);
G2L["72"]["BorderSizePixel"] = 0;
G2L["72"]["BackgroundColor3"] = Color3.fromRGB(44, 44, 44);
G2L["72"]["AnchorPoint"] = Vector2.new(1, 0.5);
G2L["72"]["Size"] = UDim2.new(0.25783, 0, 0.29407, 0);
G2L["72"]["Position"] = UDim2.new(1, 0, -0.171, 0);
G2L["72"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["72"]["Name"] = [[RButtons]];


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RButtons.UICorner
G2L["73"] = Instance.new("UICorner", G2L["72"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RButtons.UIStroke
G2L["74"] = Instance.new("UIStroke", G2L["72"]);
G2L["74"]["Thickness"] = 6.4;
G2L["74"]["Color"] = Color3.fromRGB(60, 60, 60);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RButtons.RT
G2L["75"] = Instance.new("TextLabel", G2L["72"]);
G2L["75"]["TextWrapped"] = true;
G2L["75"]["BorderSizePixel"] = 0;
G2L["75"]["TextSize"] = 14;
G2L["75"]["TextScaled"] = true;
G2L["75"]["BackgroundColor3"] = Color3.fromRGB(116, 116, 116);
G2L["75"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["75"]["TextColor3"] = Color3.fromRGB(138, 139, 137);
G2L["75"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["75"]["Size"] = UDim2.new(0.85379, 0, 0.44166, 0);
G2L["75"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["75"]["Text"] = [[RT]];
G2L["75"]["Name"] = [[RT]];
G2L["75"]["Position"] = UDim2.new(0.49822, 0, 0.3299, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RButtons.RT.UICorner
G2L["76"] = Instance.new("UICorner", G2L["75"]);
G2L["76"]["CornerRadius"] = UDim.new(0.15, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RButtons.RT.UIStroke
G2L["77"] = Instance.new("UIStroke", G2L["75"]);
G2L["77"]["Thickness"] = 2.9;
G2L["77"]["Color"] = Color3.fromRGB(112, 112, 112);
G2L["77"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RButtons.RB
G2L["78"] = Instance.new("TextLabel", G2L["72"]);
G2L["78"]["TextWrapped"] = true;
G2L["78"]["BorderSizePixel"] = 0;
G2L["78"]["TextSize"] = 14;
G2L["78"]["TextScaled"] = true;
G2L["78"]["BackgroundColor3"] = Color3.fromRGB(60, 60, 60);
G2L["78"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["78"]["TextColor3"] = Color3.fromRGB(138, 139, 137);
G2L["78"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["78"]["Size"] = UDim2.new(0.85379, 0, 0.20455, 0);
G2L["78"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["78"]["Text"] = [[RB]];
G2L["78"]["Name"] = [[RB]];
G2L["78"]["Position"] = UDim2.new(0.49822, 0, 0.79897, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RButtons.RB.UICorner
G2L["79"] = Instance.new("UICorner", G2L["78"]);
G2L["79"]["CornerRadius"] = UDim.new(0.15, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RButtons.RB.UIStroke
G2L["7a"] = Instance.new("UIStroke", G2L["78"]);
G2L["7a"]["Thickness"] = 2.9;
G2L["7a"]["Color"] = Color3.fromRGB(112, 112, 112);
G2L["7a"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RButtons.UIAspectRatioConstraint
G2L["7b"] = Instance.new("UIAspectRatioConstraint", G2L["72"]);
G2L["7b"]["AspectRatio"] = 1.47673;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RButtons.Trigger
G2L["7c"] = Instance.new("TextLabel", G2L["72"]);
G2L["7c"]["TextWrapped"] = true;
G2L["7c"]["BorderSizePixel"] = 0;
G2L["7c"]["TextSize"] = 14;
G2L["7c"]["TextScaled"] = true;
G2L["7c"]["BackgroundColor3"] = Color3.fromRGB(60, 60, 60);
G2L["7c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7c"]["TextColor3"] = Color3.fromRGB(138, 139, 137);
G2L["7c"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["7c"]["Size"] = UDim2.new(0.85379, 0, 0.44166, 0);
G2L["7c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7c"]["Text"] = [[RT]];
G2L["7c"]["Name"] = [[Trigger]];
G2L["7c"]["Position"] = UDim2.new(0.49822, 0, 0.3299, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RButtons.Trigger.UICorner
G2L["7d"] = Instance.new("UICorner", G2L["7c"]);
G2L["7d"]["CornerRadius"] = UDim.new(0.15, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RButtons.Trigger.UIStroke
G2L["7e"] = Instance.new("UIStroke", G2L["7c"]);
G2L["7e"]["Thickness"] = 2.9;
G2L["7e"]["Color"] = Color3.fromRGB(112, 112, 112);
G2L["7e"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.LPos
G2L["7f"] = Instance.new("TextLabel", G2L["29"]);
G2L["7f"]["TextWrapped"] = true;
G2L["7f"]["BorderSizePixel"] = 0;
G2L["7f"]["TextSize"] = 14;
G2L["7f"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["7f"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["7f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7f"]["TextColor3"] = Color3.fromRGB(172, 172, 172);
G2L["7f"]["BackgroundTransparency"] = 1;
G2L["7f"]["Size"] = UDim2.new(0.17347, 0, 0.14031, 0);
G2L["7f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7f"]["Text"] = [[X: 0
Y: 0]];
G2L["7f"]["Name"] = [[LPos]];
G2L["7f"]["Position"] = UDim2.new(0.04142, 0, 0.54615, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.MainFrame.RPos
G2L["80"] = Instance.new("TextLabel", G2L["29"]);
G2L["80"]["TextWrapped"] = true;
G2L["80"]["BorderSizePixel"] = 0;
G2L["80"]["TextSize"] = 14;
G2L["80"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["80"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["80"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["80"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["80"]["TextColor3"] = Color3.fromRGB(172, 172, 172);
G2L["80"]["BackgroundTransparency"] = 1;
G2L["80"]["Size"] = UDim2.new(0.17347, 0, 0.14031, 0);
G2L["80"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["80"]["Text"] = [[X: 0
Y: 0]];
G2L["80"]["Name"] = [[RPos]];
G2L["80"]["Position"] = UDim2.new(0.79535, 0, 0.80716, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.TextLabel
G2L["81"] = Instance.new("TextLabel", G2L["28"]);
G2L["81"]["TextWrapped"] = true;
G2L["81"]["BorderSizePixel"] = 0;
G2L["81"]["TextSize"] = 14;
G2L["81"]["TextScaled"] = true;
G2L["81"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["81"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["81"]["TextColor3"] = Color3.fromRGB(172, 172, 172);
G2L["81"]["BackgroundTransparency"] = 1;
G2L["81"]["Size"] = UDim2.new(0.20851, 0, 0.05472, 0);
G2L["81"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["81"]["Text"] = [[No Gamepad (try press anything)]];
G2L["81"]["Position"] = UDim2.new(0.39056, 0, 0.14364, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.Vibration
G2L["82"] = Instance.new("Folder", G2L["28"]);
G2L["82"]["Name"] = [[Vibration]];


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.Vibration.LeftVib
G2L["83"] = Instance.new("TextButton", G2L["82"]);
G2L["83"]["TextWrapped"] = true;
G2L["83"]["BorderSizePixel"] = 0;
G2L["83"]["TextSize"] = 32;
G2L["83"]["TextColor3"] = Color3.fromRGB(138, 139, 137);
G2L["83"]["BackgroundColor3"] = Color3.fromRGB(44, 44, 44);
G2L["83"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["83"]["Size"] = UDim2.new(0.1887, 0, 0.07182, 0);
G2L["83"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["83"]["Text"] = [[Left]];
G2L["83"]["Name"] = [[LeftVib]];
G2L["83"]["Visible"] = false;
G2L["83"]["Position"] = UDim2.new(0.18453, 0, 0.89261, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.Vibration.LeftVib.UICorner
G2L["84"] = Instance.new("UICorner", G2L["83"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.Vibration.LeftVib.UIStroke
G2L["85"] = Instance.new("UIStroke", G2L["83"]);
G2L["85"]["Thickness"] = 2.9;
G2L["85"]["Color"] = Color3.fromRGB(60, 60, 60);
G2L["85"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.Vibration.RightVib
G2L["86"] = Instance.new("TextButton", G2L["82"]);
G2L["86"]["TextWrapped"] = true;
G2L["86"]["BorderSizePixel"] = 0;
G2L["86"]["TextSize"] = 32;
G2L["86"]["TextColor3"] = Color3.fromRGB(138, 139, 137);
G2L["86"]["BackgroundColor3"] = Color3.fromRGB(44, 44, 44);
G2L["86"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["86"]["Size"] = UDim2.new(0.1887, 0, 0.07182, 0);
G2L["86"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["86"]["Text"] = [[Right]];
G2L["86"]["Name"] = [[RightVib]];
G2L["86"]["Visible"] = false;
G2L["86"]["Position"] = UDim2.new(0.61405, 0, 0.89261, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.Vibration.RightVib.UICorner
G2L["87"] = Instance.new("UICorner", G2L["86"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.Vibration.RightVib.UIStroke
G2L["88"] = Instance.new("UIStroke", G2L["86"]);
G2L["88"]["Thickness"] = 2.9;
G2L["88"]["Color"] = Color3.fromRGB(60, 60, 60);
G2L["88"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.Vibration.AllVib
G2L["89"] = Instance.new("TextButton", G2L["82"]);
G2L["89"]["TextWrapped"] = true;
G2L["89"]["BorderSizePixel"] = 0;
G2L["89"]["TextSize"] = 32;
G2L["89"]["TextColor3"] = Color3.fromRGB(138, 139, 137);
G2L["89"]["BackgroundColor3"] = Color3.fromRGB(44, 44, 44);
G2L["89"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["89"]["Size"] = UDim2.new(0.1887, 0, 0.07182, 0);
G2L["89"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["89"]["Text"] = [[All]];
G2L["89"]["Name"] = [[AllVib]];
G2L["89"]["Visible"] = false;
G2L["89"]["Position"] = UDim2.new(0.39929, 0, 0.89261, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.Vibration.AllVib.UICorner
G2L["8a"] = Instance.new("UICorner", G2L["89"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.Vibration.AllVib.UIStroke
G2L["8b"] = Instance.new("UIStroke", G2L["89"]);
G2L["8b"]["Thickness"] = 2.9;
G2L["8b"]["Color"] = Color3.fromRGB(60, 60, 60);
G2L["8b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Xbox.Vibration.Vib
G2L["8c"] = Instance.new("TextLabel", G2L["82"]);
G2L["8c"]["TextWrapped"] = true;
G2L["8c"]["BorderSizePixel"] = 0;
G2L["8c"]["TextSize"] = 14;
G2L["8c"]["TextScaled"] = true;
G2L["8c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["8c"]["TextColor3"] = Color3.fromRGB(172, 172, 172);
G2L["8c"]["BackgroundTransparency"] = 1;
G2L["8c"]["Size"] = UDim2.new(0.20851, 0, 0.0342, 0);
G2L["8c"]["Visible"] = false;
G2L["8c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8c"]["Text"] = [[Vibration]];
G2L["8c"]["Name"] = [[Vib]];
G2L["8c"]["Position"] = UDim2.new(0.38847, 0, 0.84644, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.Credit
G2L["8d"] = Instance.new("TextLabel", G2L["25"]);
G2L["8d"]["TextWrapped"] = true;
G2L["8d"]["BorderSizePixel"] = 0;
G2L["8d"]["TextSize"] = 14;
G2L["8d"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["8d"]["TextScaled"] = true;
G2L["8d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["8d"]["TextColor3"] = Color3.fromRGB(172, 172, 172);
G2L["8d"]["BackgroundTransparency"] = 1;
G2L["8d"]["Size"] = UDim2.new(0.20851, 0, 0.0342, 0);
G2L["8d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8d"]["Text"] = [[Made By Chillz_AZY (YT)]];
G2L["8d"]["Name"] = [[Credit]];
G2L["8d"]["Position"] = UDim2.new(0.00273, 0, 0.96443, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Thumbsticks
G2L["8e"] = Instance.new("Frame", G2L["24"]);
G2L["8e"]["Visible"] = false;
G2L["8e"]["BorderSizePixel"] = 0;
G2L["8e"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8e"]["Size"] = UDim2.new(0, 436, 0, 390);
G2L["8e"]["Position"] = UDim2.new(-3.22905, 0, -2.88, 0);
G2L["8e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8e"]["Name"] = [[Thumbsticks]];


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Thumbsticks.TextButton
G2L["8f"] = Instance.new("TextButton", G2L["8e"]);
G2L["8f"]["TextWrapped"] = true;
G2L["8f"]["BorderSizePixel"] = 0;
G2L["8f"]["TextSize"] = 14;
G2L["8f"]["TextScaled"] = true;
G2L["8f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8f"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
G2L["8f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["8f"]["Size"] = UDim2.new(0, 93, 0, 29);
G2L["8f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8f"]["Text"] = [[Off]];
G2L["8f"]["Position"] = UDim2.new(0.3922, 0, 0.1359, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Thumbsticks.TextButton.LocalScript
G2L["90"] = Instance.new("LocalScript", G2L["8f"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Thumbsticks.TextButton.UICorner
G2L["91"] = Instance.new("UICorner", G2L["8f"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Thumbsticks.TextLabel
G2L["92"] = Instance.new("TextLabel", G2L["8e"]);
G2L["92"]["TextWrapped"] = true;
G2L["92"]["BorderSizePixel"] = 0;
G2L["92"]["TextSize"] = 14;
G2L["92"]["TextScaled"] = true;
G2L["92"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["92"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["92"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["92"]["BackgroundTransparency"] = 1;
G2L["92"]["Size"] = UDim2.new(0, 118, 0, 56);
G2L["92"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["92"]["Text"] = [[Reduce  Drift:]];
G2L["92"]["Position"] = UDim2.new(0.06651, 0, 0.10256, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Thumbsticks.TextLabel
G2L["93"] = Instance.new("TextLabel", G2L["8e"]);
G2L["93"]["TextWrapped"] = true;
G2L["93"]["BorderSizePixel"] = 0;
G2L["93"]["TextSize"] = 14;
G2L["93"]["TextScaled"] = true;
G2L["93"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["93"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["93"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["93"]["BackgroundTransparency"] = 1;
G2L["93"]["Size"] = UDim2.new(0, 244, 0, 95);
G2L["93"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["93"]["Text"] = [[Position Sticks:]];
G2L["93"]["Position"] = UDim2.new(0.15367, 0, 0.35641, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Thumbsticks.TextLabel
G2L["94"] = Instance.new("TextLabel", G2L["8e"]);
G2L["94"]["TextWrapped"] = true;
G2L["94"]["BorderSizePixel"] = 0;
G2L["94"]["TextSize"] = 14;
G2L["94"]["TextScaled"] = true;
G2L["94"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["94"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["94"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["94"]["BackgroundTransparency"] = 1;
G2L["94"]["Size"] = UDim2.new(0, 109, 0, 55);
G2L["94"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["94"]["Text"] = [[Stick1:]];
G2L["94"]["Position"] = UDim2.new(0.04587, 0, 0.59744, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Thumbsticks.TextLabel
G2L["95"] = Instance.new("TextLabel", G2L["8e"]);
G2L["95"]["TextWrapped"] = true;
G2L["95"]["BorderSizePixel"] = 0;
G2L["95"]["TextSize"] = 14;
G2L["95"]["TextScaled"] = true;
G2L["95"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["95"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["95"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["95"]["BackgroundTransparency"] = 1;
G2L["95"]["Size"] = UDim2.new(0, 109, 0, 55);
G2L["95"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["95"]["Text"] = [[Stick2:]];
G2L["95"]["Position"] = UDim2.new(0.6055, 0, 0.6, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Thumbsticks.TextLabel
G2L["96"] = Instance.new("TextLabel", G2L["8e"]);
G2L["96"]["TextWrapped"] = true;
G2L["96"]["BorderSizePixel"] = 0;
G2L["96"]["TextSize"] = 14;
G2L["96"]["TextScaled"] = true;
G2L["96"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["96"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["96"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["96"]["BackgroundTransparency"] = 1;
G2L["96"]["Size"] = UDim2.new(0, 109, 0, 55);
G2L["96"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["96"]["Text"] = [[Stick1:]];
G2L["96"]["Position"] = UDim2.new(0.04587, 0, 0.77179, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Thumbsticks.TextLabel.LocalScript
G2L["97"] = Instance.new("LocalScript", G2L["96"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Thumbsticks.TextLabel
G2L["98"] = Instance.new("TextLabel", G2L["8e"]);
G2L["98"]["TextWrapped"] = true;
G2L["98"]["BorderSizePixel"] = 0;
G2L["98"]["TextSize"] = 14;
G2L["98"]["TextScaled"] = true;
G2L["98"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["98"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["98"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["98"]["BackgroundTransparency"] = 1;
G2L["98"]["Size"] = UDim2.new(0, 109, 0, 55);
G2L["98"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["98"]["Text"] = [[Stick2:]];
G2L["98"]["Position"] = UDim2.new(0.6055, 0, 0.79487, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Thumbsticks.TextLabel.LocalScript
G2L["99"] = Instance.new("LocalScript", G2L["98"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos
G2L["9a"] = Instance.new("Frame", G2L["24"]);
G2L["9a"]["Visible"] = false;
G2L["9a"]["BorderSizePixel"] = 0;
G2L["9a"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9a"]["Size"] = UDim2.new(0, 442, 0, 388);
G2L["9a"]["Position"] = UDim2.new(-3.28, 0, -2.88, 0);
G2L["9a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9a"]["Name"] = [[Combos]];


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.Combo
G2L["9b"] = Instance.new("LocalScript", G2L["9a"]);
G2L["9b"]["Name"] = [[Combo]];


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel
G2L["9c"] = Instance.new("TextLabel", G2L["9a"]);
G2L["9c"]["TextWrapped"] = true;
G2L["9c"]["BorderSizePixel"] = 0;
G2L["9c"]["TextSize"] = 14;
G2L["9c"]["TextScaled"] = true;
G2L["9c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["9c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9c"]["BackgroundTransparency"] = 1;
G2L["9c"]["Size"] = UDim2.new(0, 168, 0, 37);
G2L["9c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9c"]["Text"] = [[Combos:]];
G2L["9c"]["Position"] = UDim2.new(0.23077, 0, 0.03608, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel
G2L["9d"] = Instance.new("TextLabel", G2L["9a"]);
G2L["9d"]["TextWrapped"] = true;
G2L["9d"]["BorderSizePixel"] = 0;
G2L["9d"]["TextSize"] = 14;
G2L["9d"]["TextScaled"] = true;
G2L["9d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["9d"]["TextColor3"] = Color3.fromRGB(38, 18, 255);
G2L["9d"]["BackgroundTransparency"] = 1;
G2L["9d"]["Size"] = UDim2.new(0, 168, 0, 37);
G2L["9d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9d"]["Text"] = [[X]];
G2L["9d"]["Position"] = UDim2.new(-0.04977, 0, 0.31186, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["9e"] = Instance.new("TextLabel", G2L["9d"]);
G2L["9e"]["TextWrapped"] = true;
G2L["9e"]["BorderSizePixel"] = 0;
G2L["9e"]["TextSize"] = 14;
G2L["9e"]["TextScaled"] = true;
G2L["9e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["9e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9e"]["BackgroundTransparency"] = 1;
G2L["9e"]["Size"] = UDim2.new(0, 168, 0, 37);
G2L["9e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9e"]["Text"] = [[+]];
G2L["9e"]["Position"] = UDim2.new(0.15856, 0, -0.01247, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["9f"] = Instance.new("TextLabel", G2L["9d"]);
G2L["9f"]["TextWrapped"] = true;
G2L["9f"]["BorderSizePixel"] = 0;
G2L["9f"]["TextSize"] = 14;
G2L["9f"]["TextScaled"] = true;
G2L["9f"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["9f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["9f"]["TextColor3"] = Color3.fromRGB(243, 255, 0);
G2L["9f"]["BackgroundTransparency"] = 1;
G2L["9f"]["Size"] = UDim2.new(0, 168, 0, 37);
G2L["9f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9f"]["Text"] = [[Y]];
G2L["9f"]["Position"] = UDim2.new(0.27761, 0, -0.01247, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["a0"] = Instance.new("TextLabel", G2L["9d"]);
G2L["a0"]["TextWrapped"] = true;
G2L["a0"]["BorderSizePixel"] = 0;
G2L["a0"]["TextSize"] = 14;
G2L["a0"]["TextScaled"] = true;
G2L["a0"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["a0"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["a0"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a0"]["BackgroundTransparency"] = 1;
G2L["a0"]["Size"] = UDim2.new(0, 168, 0, 37);
G2L["a0"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a0"]["Text"] = [[+]];
G2L["a0"]["Position"] = UDim2.new(0.42046, 0, -0.01247, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["a1"] = Instance.new("TextLabel", G2L["9d"]);
G2L["a1"]["TextWrapped"] = true;
G2L["a1"]["BorderSizePixel"] = 0;
G2L["a1"]["TextSize"] = 14;
G2L["a1"]["TextScaled"] = true;
G2L["a1"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["a1"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["a1"]["TextColor3"] = Color3.fromRGB(0, 255, 0);
G2L["a1"]["BackgroundTransparency"] = 1;
G2L["a1"]["Size"] = UDim2.new(0, 168, 0, 37);
G2L["a1"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a1"]["Text"] = [[A]];
G2L["a1"]["Position"] = UDim2.new(0.58118, 0, -0.01247, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["a2"] = Instance.new("TextLabel", G2L["9d"]);
G2L["a2"]["TextWrapped"] = true;
G2L["a2"]["BorderSizePixel"] = 0;
G2L["a2"]["TextSize"] = 14;
G2L["a2"]["TextScaled"] = true;
G2L["a2"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["a2"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["a2"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a2"]["BackgroundTransparency"] = 1;
G2L["a2"]["Size"] = UDim2.new(0, 168, 0, 37);
G2L["a2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a2"]["Text"] = [[+]];
G2L["a2"]["Position"] = UDim2.new(0.73594, 0, 0.01456, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["a3"] = Instance.new("TextLabel", G2L["9d"]);
G2L["a3"]["TextWrapped"] = true;
G2L["a3"]["BorderSizePixel"] = 0;
G2L["a3"]["TextSize"] = 14;
G2L["a3"]["TextScaled"] = true;
G2L["a3"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["a3"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["a3"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a3"]["BackgroundTransparency"] = 1;
G2L["a3"]["Size"] = UDim2.new(0, 168, 0, 36);
G2L["a3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a3"]["Text"] = [[RT]];
G2L["a3"]["Position"] = UDim2.new(0.94427, 0, 0.02516, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["a4"] = Instance.new("TextLabel", G2L["9d"]);
G2L["a4"]["TextWrapped"] = true;
G2L["a4"]["BorderSizePixel"] = 0;
G2L["a4"]["TextSize"] = 14;
G2L["a4"]["TextScaled"] = true;
G2L["a4"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["a4"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["a4"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a4"]["BackgroundTransparency"] = 1;
G2L["a4"]["Size"] = UDim2.new(0, 168, 0, 36);
G2L["a4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a4"]["Text"] = [[=]];
G2L["a4"]["Position"] = UDim2.new(1.15856, 0, 0.02516, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["a5"] = Instance.new("TextLabel", G2L["9d"]);
G2L["a5"]["TextWrapped"] = true;
G2L["a5"]["BorderSizePixel"] = 0;
G2L["a5"]["TextSize"] = 14;
G2L["a5"]["TextScaled"] = true;
G2L["a5"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["a5"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["a5"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a5"]["BackgroundTransparency"] = 1;
G2L["a5"]["Size"] = UDim2.new(0, 168, 0, 36);
G2L["a5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a5"]["Text"] = [[Fly]];
G2L["a5"]["Position"] = UDim2.new(1.42046, 0, 0.02516, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel
G2L["a6"] = Instance.new("TextLabel", G2L["9a"]);
G2L["a6"]["TextWrapped"] = true;
G2L["a6"]["BorderSizePixel"] = 0;
G2L["a6"]["TextSize"] = 14;
G2L["a6"]["TextScaled"] = true;
G2L["a6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a6"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["a6"]["TextColor3"] = Color3.fromRGB(38, 18, 255);
G2L["a6"]["BackgroundTransparency"] = 1;
G2L["a6"]["Size"] = UDim2.new(0, 168, 0, 37);
G2L["a6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a6"]["Text"] = [[X]];
G2L["a6"]["Position"] = UDim2.new(-0.04977, 0, 0.31186, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["a7"] = Instance.new("TextLabel", G2L["a6"]);
G2L["a7"]["TextWrapped"] = true;
G2L["a7"]["BorderSizePixel"] = 0;
G2L["a7"]["TextSize"] = 14;
G2L["a7"]["TextScaled"] = true;
G2L["a7"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["a7"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["a7"]["TextColor3"] = Color3.fromRGB(243, 255, 0);
G2L["a7"]["BackgroundTransparency"] = 1;
G2L["a7"]["Size"] = UDim2.new(0, 168, 0, 37);
G2L["a7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a7"]["Text"] = [[Y]];
G2L["a7"]["Position"] = UDim2.new(0.27761, 0, -0.01247, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["a8"] = Instance.new("TextLabel", G2L["a6"]);
G2L["a8"]["TextWrapped"] = true;
G2L["a8"]["BorderSizePixel"] = 0;
G2L["a8"]["TextSize"] = 14;
G2L["a8"]["TextScaled"] = true;
G2L["a8"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["a8"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["a8"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a8"]["BackgroundTransparency"] = 1;
G2L["a8"]["Size"] = UDim2.new(0, 168, 0, 37);
G2L["a8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a8"]["Text"] = [[+]];
G2L["a8"]["Position"] = UDim2.new(0.42046, 0, -0.01247, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["a9"] = Instance.new("TextLabel", G2L["a6"]);
G2L["a9"]["TextWrapped"] = true;
G2L["a9"]["BorderSizePixel"] = 0;
G2L["a9"]["TextSize"] = 14;
G2L["a9"]["TextScaled"] = true;
G2L["a9"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["a9"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["a9"]["TextColor3"] = Color3.fromRGB(0, 255, 0);
G2L["a9"]["BackgroundTransparency"] = 1;
G2L["a9"]["Size"] = UDim2.new(0, 168, 0, 37);
G2L["a9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a9"]["Text"] = [[A]];
G2L["a9"]["Position"] = UDim2.new(0.58118, 0, -0.01247, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["aa"] = Instance.new("TextLabel", G2L["a6"]);
G2L["aa"]["TextWrapped"] = true;
G2L["aa"]["BorderSizePixel"] = 0;
G2L["aa"]["TextSize"] = 14;
G2L["aa"]["TextScaled"] = true;
G2L["aa"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["aa"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["aa"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["aa"]["BackgroundTransparency"] = 1;
G2L["aa"]["Size"] = UDim2.new(0, 168, 0, 37);
G2L["aa"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["aa"]["Text"] = [[+]];
G2L["aa"]["Position"] = UDim2.new(0.73594, 0, 0.01456, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["ab"] = Instance.new("TextLabel", G2L["a6"]);
G2L["ab"]["TextWrapped"] = true;
G2L["ab"]["BorderSizePixel"] = 0;
G2L["ab"]["TextSize"] = 14;
G2L["ab"]["TextScaled"] = true;
G2L["ab"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["ab"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["ab"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ab"]["BackgroundTransparency"] = 1;
G2L["ab"]["Size"] = UDim2.new(0, 168, 0, 36);
G2L["ab"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ab"]["Text"] = [[RT]];
G2L["ab"]["Position"] = UDim2.new(0.94427, 0, 0.02516, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["ac"] = Instance.new("TextLabel", G2L["a6"]);
G2L["ac"]["TextWrapped"] = true;
G2L["ac"]["BorderSizePixel"] = 0;
G2L["ac"]["TextSize"] = 14;
G2L["ac"]["TextScaled"] = true;
G2L["ac"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["ac"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["ac"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ac"]["BackgroundTransparency"] = 1;
G2L["ac"]["Size"] = UDim2.new(0, 168, 0, 36);
G2L["ac"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ac"]["Text"] = [[=]];
G2L["ac"]["Position"] = UDim2.new(1.15856, 0, 0.02516, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["ad"] = Instance.new("TextLabel", G2L["a6"]);
G2L["ad"]["TextWrapped"] = true;
G2L["ad"]["BorderSizePixel"] = 0;
G2L["ad"]["TextSize"] = 14;
G2L["ad"]["TextScaled"] = true;
G2L["ad"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["ad"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["ad"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ad"]["BackgroundTransparency"] = 1;
G2L["ad"]["Size"] = UDim2.new(0, 168, 0, 36);
G2L["ad"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ad"]["Text"] = [[Fly]];
G2L["ad"]["Position"] = UDim2.new(1.42046, 0, 0.02516, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["ae"] = Instance.new("TextLabel", G2L["a6"]);
G2L["ae"]["TextWrapped"] = true;
G2L["ae"]["BorderSizePixel"] = 0;
G2L["ae"]["TextSize"] = 14;
G2L["ae"]["TextScaled"] = true;
G2L["ae"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["ae"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["ae"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ae"]["BackgroundTransparency"] = 1;
G2L["ae"]["Size"] = UDim2.new(0, 168, 0, 36);
G2L["ae"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ae"]["Text"] = [[Soon! :)]];
G2L["ae"]["Position"] = UDim2.new(0.73594, 0, 4.59272, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["af"] = Instance.new("TextLabel", G2L["a6"]);
G2L["af"]["TextWrapped"] = true;
G2L["af"]["BorderSizePixel"] = 0;
G2L["af"]["TextSize"] = 14;
G2L["af"]["TextScaled"] = true;
G2L["af"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["af"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["af"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["af"]["BackgroundTransparency"] = 1;
G2L["af"]["Size"] = UDim2.new(0, 168, 0, 36);
G2L["af"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["af"]["Text"] = [[Or]];
G2L["af"]["Position"] = UDim2.new(0.66451, 0, 0.86299, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["b0"] = Instance.new("TextLabel", G2L["a6"]);
G2L["b0"]["TextWrapped"] = true;
G2L["b0"]["BorderSizePixel"] = 0;
G2L["b0"]["TextSize"] = 14;
G2L["b0"]["TextScaled"] = true;
G2L["b0"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["b0"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["b0"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["b0"]["BackgroundTransparency"] = 1;
G2L["b0"]["Size"] = UDim2.new(0, 168, 0, 36);
G2L["b0"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b0"]["Text"] = [[B]];
G2L["b0"]["Position"] = UDim2.new(0.20618, 0, 5.94408, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["b1"] = Instance.new("TextLabel", G2L["a6"]);
G2L["b1"]["TextWrapped"] = true;
G2L["b1"]["BorderSizePixel"] = 0;
G2L["b1"]["TextSize"] = 14;
G2L["b1"]["TextScaled"] = true;
G2L["b1"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["b1"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["b1"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["b1"]["BackgroundTransparency"] = 1;
G2L["b1"]["Size"] = UDim2.new(0, 168, 0, 36);
G2L["b1"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b1"]["Text"] = [[○]];
G2L["b1"]["Position"] = UDim2.new(0.58713, 0, 5.94408, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["b2"] = Instance.new("TextLabel", G2L["a6"]);
G2L["b2"]["TextWrapped"] = true;
G2L["b2"]["BorderSizePixel"] = 0;
G2L["b2"]["TextSize"] = 14;
G2L["b2"]["TextScaled"] = true;
G2L["b2"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["b2"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["b2"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b2"]["BackgroundTransparency"] = 1;
G2L["b2"]["Size"] = UDim2.new(0, 168, 0, 36);
G2L["b2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b2"]["Text"] = [[or]];
G2L["b2"]["Position"] = UDim2.new(0.36094, 0, 5.86299, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["b3"] = Instance.new("TextLabel", G2L["a6"]);
G2L["b3"]["TextWrapped"] = true;
G2L["b3"]["BorderSizePixel"] = 0;
G2L["b3"]["TextSize"] = 14;
G2L["b3"]["TextScaled"] = true;
G2L["b3"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["b3"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["b3"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b3"]["BackgroundTransparency"] = 1;
G2L["b3"]["Size"] = UDim2.new(0, 168, 0, 36);
G2L["b3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b3"]["Text"] = [[to stop flying]];
G2L["b3"]["Position"] = UDim2.new(1.28356, 0, 5.94408, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel
G2L["b4"] = Instance.new("TextLabel", G2L["9a"]);
G2L["b4"]["TextWrapped"] = true;
G2L["b4"]["BorderSizePixel"] = 0;
G2L["b4"]["TextSize"] = 14;
G2L["b4"]["TextScaled"] = true;
G2L["b4"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b4"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["b4"]["TextColor3"] = Color3.fromRGB(255, 0, 255);
G2L["b4"]["BackgroundTransparency"] = 1;
G2L["b4"]["Size"] = UDim2.new(0, 168, 0, 37);
G2L["b4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b4"]["Text"] = [[□]];
G2L["b4"]["Position"] = UDim2.new(-0.04751, 0, 0.49227, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["b5"] = Instance.new("TextLabel", G2L["b4"]);
G2L["b5"]["TextWrapped"] = true;
G2L["b5"]["BorderSizePixel"] = 0;
G2L["b5"]["TextSize"] = 14;
G2L["b5"]["TextScaled"] = true;
G2L["b5"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["b5"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["b5"]["TextColor3"] = Color3.fromRGB(0, 255, 0);
G2L["b5"]["BackgroundTransparency"] = 1;
G2L["b5"]["Size"] = UDim2.new(0, 168, 0, 37);
G2L["b5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b5"]["Text"] = [[△]];
G2L["b5"]["Position"] = UDim2.new(0.27761, 0, -0.01247, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["b6"] = Instance.new("TextLabel", G2L["b4"]);
G2L["b6"]["TextWrapped"] = true;
G2L["b6"]["BorderSizePixel"] = 0;
G2L["b6"]["TextSize"] = 14;
G2L["b6"]["TextScaled"] = true;
G2L["b6"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["b6"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["b6"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b6"]["BackgroundTransparency"] = 1;
G2L["b6"]["Size"] = UDim2.new(0, 168, 0, 37);
G2L["b6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b6"]["Text"] = [[+]];
G2L["b6"]["Position"] = UDim2.new(0.42046, 0, -0.01247, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["b7"] = Instance.new("TextLabel", G2L["b4"]);
G2L["b7"]["TextWrapped"] = true;
G2L["b7"]["BorderSizePixel"] = 0;
G2L["b7"]["TextSize"] = 14;
G2L["b7"]["TextScaled"] = true;
G2L["b7"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["b7"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["b7"]["TextColor3"] = Color3.fromRGB(0, 111, 255);
G2L["b7"]["BackgroundTransparency"] = 1;
G2L["b7"]["Size"] = UDim2.new(0, 168, 0, 37);
G2L["b7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b7"]["Text"] = [[x]];
G2L["b7"]["Position"] = UDim2.new(0.58118, 0, -0.01247, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["b8"] = Instance.new("TextLabel", G2L["b4"]);
G2L["b8"]["TextWrapped"] = true;
G2L["b8"]["BorderSizePixel"] = 0;
G2L["b8"]["TextSize"] = 14;
G2L["b8"]["TextScaled"] = true;
G2L["b8"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["b8"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["b8"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b8"]["BackgroundTransparency"] = 1;
G2L["b8"]["Size"] = UDim2.new(0, 168, 0, 37);
G2L["b8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b8"]["Text"] = [[+]];
G2L["b8"]["Position"] = UDim2.new(0.73594, 0, 0.01456, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["b9"] = Instance.new("TextLabel", G2L["b4"]);
G2L["b9"]["TextWrapped"] = true;
G2L["b9"]["BorderSizePixel"] = 0;
G2L["b9"]["TextSize"] = 14;
G2L["b9"]["TextScaled"] = true;
G2L["b9"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["b9"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["b9"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b9"]["BackgroundTransparency"] = 1;
G2L["b9"]["Size"] = UDim2.new(0, 168, 0, 36);
G2L["b9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b9"]["Text"] = [[R2]];
G2L["b9"]["Position"] = UDim2.new(0.94427, 0, 0.02516, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["ba"] = Instance.new("TextLabel", G2L["b4"]);
G2L["ba"]["TextWrapped"] = true;
G2L["ba"]["BorderSizePixel"] = 0;
G2L["ba"]["TextSize"] = 14;
G2L["ba"]["TextScaled"] = true;
G2L["ba"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["ba"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["ba"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ba"]["BackgroundTransparency"] = 1;
G2L["ba"]["Size"] = UDim2.new(0, 168, 0, 36);
G2L["ba"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ba"]["Text"] = [[=]];
G2L["ba"]["Position"] = UDim2.new(1.15856, 0, 0.02516, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["bb"] = Instance.new("TextLabel", G2L["b4"]);
G2L["bb"]["TextWrapped"] = true;
G2L["bb"]["BorderSizePixel"] = 0;
G2L["bb"]["TextSize"] = 14;
G2L["bb"]["TextScaled"] = true;
G2L["bb"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["bb"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["bb"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["bb"]["BackgroundTransparency"] = 1;
G2L["bb"]["Size"] = UDim2.new(0, 168, 0, 36);
G2L["bb"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["bb"]["Text"] = [[Fly]];
G2L["bb"]["Position"] = UDim2.new(1.42046, 0, 0.02516, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.TextLabel.TextLabel
G2L["bc"] = Instance.new("TextLabel", G2L["b4"]);
G2L["bc"]["TextWrapped"] = true;
G2L["bc"]["BorderSizePixel"] = 0;
G2L["bc"]["TextSize"] = 14;
G2L["bc"]["TextScaled"] = true;
G2L["bc"]["BackgroundColor3"] = Color3.fromRGB(213, 255, 0);
G2L["bc"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["bc"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["bc"]["BackgroundTransparency"] = 1;
G2L["bc"]["Size"] = UDim2.new(0, 168, 0, 37);
G2L["bc"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["bc"]["Text"] = [[+]];
G2L["bc"]["Position"] = UDim2.new(0.15261, 0, 0.01456, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration
G2L["bd"] = Instance.new("Frame", G2L["24"]);
G2L["bd"]["Visible"] = false;
G2L["bd"]["BorderSizePixel"] = 0;
G2L["bd"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["bd"]["Size"] = UDim2.new(0, 442, 0, 388);
G2L["bd"]["Position"] = UDim2.new(-3.28, 0, -2.88, 0);
G2L["bd"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["bd"]["Name"] = [[Vibration]];


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextLabel
G2L["be"] = Instance.new("TextLabel", G2L["bd"]);
G2L["be"]["TextWrapped"] = true;
G2L["be"]["BorderSizePixel"] = 0;
G2L["be"]["TextSize"] = 14;
G2L["be"]["TextScaled"] = true;
G2L["be"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["be"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["be"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["be"]["BackgroundTransparency"] = 1;
G2L["be"]["Size"] = UDim2.new(0, 139, 0, 33);
G2L["be"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["be"]["Text"] = [[RT/R2:]];
G2L["be"]["Position"] = UDim2.new(0, 0, 0.03608, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextLabel
G2L["bf"] = Instance.new("TextLabel", G2L["bd"]);
G2L["bf"]["TextWrapped"] = true;
G2L["bf"]["BorderSizePixel"] = 0;
G2L["bf"]["TextSize"] = 14;
G2L["bf"]["TextScaled"] = true;
G2L["bf"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["bf"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["bf"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["bf"]["BackgroundTransparency"] = 1;
G2L["bf"]["Size"] = UDim2.new(0, 139, 0, 33);
G2L["bf"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["bf"]["Text"] = [[LT/L2:]];
G2L["bf"]["Position"] = UDim2.new(-0.00452, 0, 0.13144, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextLabel
G2L["c0"] = Instance.new("TextLabel", G2L["bd"]);
G2L["c0"]["TextWrapped"] = true;
G2L["c0"]["BorderSizePixel"] = 0;
G2L["c0"]["TextSize"] = 14;
G2L["c0"]["TextScaled"] = true;
G2L["c0"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c0"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["c0"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c0"]["BackgroundTransparency"] = 1;
G2L["c0"]["Size"] = UDim2.new(0, 139, 0, 33);
G2L["c0"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c0"]["Text"] = [[X/□:]];
G2L["c0"]["Position"] = UDim2.new(-0.00452, 0, 0.2268, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextLabel
G2L["c1"] = Instance.new("TextLabel", G2L["bd"]);
G2L["c1"]["TextWrapped"] = true;
G2L["c1"]["BorderSizePixel"] = 0;
G2L["c1"]["TextSize"] = 14;
G2L["c1"]["TextScaled"] = true;
G2L["c1"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c1"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["c1"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c1"]["BackgroundTransparency"] = 1;
G2L["c1"]["Size"] = UDim2.new(0, 139, 0, 33);
G2L["c1"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c1"]["Text"] = [[Y/△:]];
G2L["c1"]["Position"] = UDim2.new(0, 0, 0.31186, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextLabel
G2L["c2"] = Instance.new("TextLabel", G2L["bd"]);
G2L["c2"]["TextWrapped"] = true;
G2L["c2"]["BorderSizePixel"] = 0;
G2L["c2"]["TextSize"] = 14;
G2L["c2"]["TextScaled"] = true;
G2L["c2"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c2"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["c2"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c2"]["BackgroundTransparency"] = 1;
G2L["c2"]["Size"] = UDim2.new(0, 139, 0, 33);
G2L["c2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c2"]["Text"] = [[A/x:]];
G2L["c2"]["Position"] = UDim2.new(-0.00452, 0, 0.39691, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextLabel
G2L["c3"] = Instance.new("TextLabel", G2L["bd"]);
G2L["c3"]["TextWrapped"] = true;
G2L["c3"]["BorderSizePixel"] = 0;
G2L["c3"]["TextSize"] = 14;
G2L["c3"]["TextScaled"] = true;
G2L["c3"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c3"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["c3"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c3"]["BackgroundTransparency"] = 1;
G2L["c3"]["Size"] = UDim2.new(0, 139, 0, 33);
G2L["c3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c3"]["Text"] = [[B/◯:]];
G2L["c3"]["Position"] = UDim2.new(-0.01584, 0, 0.48711, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextLabel
G2L["c4"] = Instance.new("TextLabel", G2L["bd"]);
G2L["c4"]["TextWrapped"] = true;
G2L["c4"]["BorderSizePixel"] = 0;
G2L["c4"]["TextSize"] = 14;
G2L["c4"]["TextScaled"] = true;
G2L["c4"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c4"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["c4"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c4"]["BackgroundTransparency"] = 1;
G2L["c4"]["Size"] = UDim2.new(0, 139, 0, 33);
G2L["c4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c4"]["Text"] = [[RB/R1:]];
G2L["c4"]["Position"] = UDim2.new(-0.00452, 0, 0.5799, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextLabel
G2L["c5"] = Instance.new("TextLabel", G2L["bd"]);
G2L["c5"]["TextWrapped"] = true;
G2L["c5"]["BorderSizePixel"] = 0;
G2L["c5"]["TextSize"] = 14;
G2L["c5"]["TextScaled"] = true;
G2L["c5"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c5"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["c5"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c5"]["BackgroundTransparency"] = 1;
G2L["c5"]["Size"] = UDim2.new(0, 139, 0, 33);
G2L["c5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c5"]["Text"] = [[LB/L1:]];
G2L["c5"]["Position"] = UDim2.new(-0.01584, 0, 0.66495, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextLabel
G2L["c6"] = Instance.new("TextLabel", G2L["bd"]);
G2L["c6"]["TextWrapped"] = true;
G2L["c6"]["BorderSizePixel"] = 0;
G2L["c6"]["TextSize"] = 14;
G2L["c6"]["TextScaled"] = true;
G2L["c6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c6"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["c6"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c6"]["BackgroundTransparency"] = 1;
G2L["c6"]["Size"] = UDim2.new(0, 139, 0, 33);
G2L["c6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c6"]["Text"] = [[RS/R3:]];
G2L["c6"]["Position"] = UDim2.new(-0.00452, 0, 0.81959, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextLabel
G2L["c7"] = Instance.new("TextLabel", G2L["bd"]);
G2L["c7"]["TextWrapped"] = true;
G2L["c7"]["BorderSizePixel"] = 0;
G2L["c7"]["TextSize"] = 14;
G2L["c7"]["TextScaled"] = true;
G2L["c7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c7"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["c7"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c7"]["BackgroundTransparency"] = 1;
G2L["c7"]["Size"] = UDim2.new(0, 139, 0, 33);
G2L["c7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c7"]["Text"] = [[Select/Share:]];
G2L["c7"]["Position"] = UDim2.new(0, 0, 0.73454, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextLabel
G2L["c8"] = Instance.new("TextLabel", G2L["bd"]);
G2L["c8"]["TextWrapped"] = true;
G2L["c8"]["BorderSizePixel"] = 0;
G2L["c8"]["TextSize"] = 14;
G2L["c8"]["TextScaled"] = true;
G2L["c8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c8"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["c8"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c8"]["BackgroundTransparency"] = 1;
G2L["c8"]["Size"] = UDim2.new(0, 139, 0, 33);
G2L["c8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c8"]["Text"] = [[LS/L3:]];
G2L["c8"]["Position"] = UDim2.new(-0.00452, 0, 0.90464, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton
G2L["c9"] = Instance.new("TextButton", G2L["bd"]);
G2L["c9"]["TextWrapped"] = true;
G2L["c9"]["BorderSizePixel"] = 0;
G2L["c9"]["TextSize"] = 14;
G2L["c9"]["TextScaled"] = true;
G2L["c9"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c9"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
G2L["c9"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["c9"]["Size"] = UDim2.new(0, 115, 0, 24);
G2L["c9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c9"]["Text"] = [[Off]];
G2L["c9"]["Position"] = UDim2.new(0.30995, 0, 0.05928, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
G2L["ca"] = Instance.new("LocalScript", G2L["c9"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.UICorner
G2L["cb"] = Instance.new("UICorner", G2L["c9"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton
G2L["cc"] = Instance.new("TextButton", G2L["bd"]);
G2L["cc"]["TextWrapped"] = true;
G2L["cc"]["BorderSizePixel"] = 0;
G2L["cc"]["TextSize"] = 14;
G2L["cc"]["TextScaled"] = true;
G2L["cc"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["cc"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
G2L["cc"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["cc"]["Size"] = UDim2.new(0, 115, 0, 24);
G2L["cc"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["cc"]["Text"] = [[Off]];
G2L["cc"]["Position"] = UDim2.new(0.30995, 0, 0.15464, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
G2L["cd"] = Instance.new("LocalScript", G2L["cc"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.UICorner
G2L["ce"] = Instance.new("UICorner", G2L["cc"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton
G2L["cf"] = Instance.new("TextButton", G2L["bd"]);
G2L["cf"]["TextWrapped"] = true;
G2L["cf"]["BorderSizePixel"] = 0;
G2L["cf"]["TextSize"] = 14;
G2L["cf"]["TextScaled"] = true;
G2L["cf"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["cf"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
G2L["cf"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["cf"]["Size"] = UDim2.new(0, 115, 0, 24);
G2L["cf"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["cf"]["Text"] = [[Off]];
G2L["cf"]["Position"] = UDim2.new(0.30995, 0, 0.41753, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
G2L["d0"] = Instance.new("LocalScript", G2L["cf"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.UICorner
G2L["d1"] = Instance.new("UICorner", G2L["cf"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton
G2L["d2"] = Instance.new("TextButton", G2L["bd"]);
G2L["d2"]["TextWrapped"] = true;
G2L["d2"]["BorderSizePixel"] = 0;
G2L["d2"]["TextSize"] = 14;
G2L["d2"]["TextScaled"] = true;
G2L["d2"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d2"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
G2L["d2"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["d2"]["Size"] = UDim2.new(0, 115, 0, 24);
G2L["d2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d2"]["Text"] = [[Off]];
G2L["d2"]["Position"] = UDim2.new(0.30995, 0, 0.33505, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
G2L["d3"] = Instance.new("LocalScript", G2L["d2"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.UICorner
G2L["d4"] = Instance.new("UICorner", G2L["d2"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton
G2L["d5"] = Instance.new("TextButton", G2L["bd"]);
G2L["d5"]["TextWrapped"] = true;
G2L["d5"]["BorderSizePixel"] = 0;
G2L["d5"]["TextSize"] = 14;
G2L["d5"]["TextScaled"] = true;
G2L["d5"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d5"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
G2L["d5"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["d5"]["Size"] = UDim2.new(0, 115, 0, 24);
G2L["d5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d5"]["Text"] = [[Off]];
G2L["d5"]["Position"] = UDim2.new(0.30995, 0, 0.25, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
G2L["d6"] = Instance.new("LocalScript", G2L["d5"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.UICorner
G2L["d7"] = Instance.new("UICorner", G2L["d5"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton
G2L["d8"] = Instance.new("TextButton", G2L["bd"]);
G2L["d8"]["TextWrapped"] = true;
G2L["d8"]["BorderSizePixel"] = 0;
G2L["d8"]["TextSize"] = 14;
G2L["d8"]["TextScaled"] = true;
G2L["d8"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d8"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
G2L["d8"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["d8"]["Size"] = UDim2.new(0, 115, 0, 24);
G2L["d8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d8"]["Text"] = [[Off]];
G2L["d8"]["Position"] = UDim2.new(0.31448, 0, 0.51031, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
G2L["d9"] = Instance.new("LocalScript", G2L["d8"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.UICorner
G2L["da"] = Instance.new("UICorner", G2L["d8"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton
G2L["db"] = Instance.new("TextButton", G2L["bd"]);
G2L["db"]["TextWrapped"] = true;
G2L["db"]["BorderSizePixel"] = 0;
G2L["db"]["TextSize"] = 14;
G2L["db"]["TextScaled"] = true;
G2L["db"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["db"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
G2L["db"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["db"]["Size"] = UDim2.new(0, 115, 0, 24);
G2L["db"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["db"]["Text"] = [[Off]];
G2L["db"]["Position"] = UDim2.new(0.31448, 0, 0.60309, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
G2L["dc"] = Instance.new("LocalScript", G2L["db"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.UICorner
G2L["dd"] = Instance.new("UICorner", G2L["db"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton
G2L["de"] = Instance.new("TextButton", G2L["bd"]);
G2L["de"]["TextWrapped"] = true;
G2L["de"]["BorderSizePixel"] = 0;
G2L["de"]["TextSize"] = 14;
G2L["de"]["TextScaled"] = true;
G2L["de"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["de"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
G2L["de"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["de"]["Size"] = UDim2.new(0, 115, 0, 24);
G2L["de"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["de"]["Text"] = [[Off]];
G2L["de"]["Position"] = UDim2.new(0.31448, 0, 0.68814, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
G2L["df"] = Instance.new("LocalScript", G2L["de"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.UICorner
G2L["e0"] = Instance.new("UICorner", G2L["de"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton
G2L["e1"] = Instance.new("TextButton", G2L["bd"]);
G2L["e1"]["TextWrapped"] = true;
G2L["e1"]["BorderSizePixel"] = 0;
G2L["e1"]["TextSize"] = 14;
G2L["e1"]["TextScaled"] = true;
G2L["e1"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e1"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
G2L["e1"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["e1"]["Size"] = UDim2.new(0, 115, 0, 24);
G2L["e1"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e1"]["Text"] = [[Off]];
G2L["e1"]["Position"] = UDim2.new(0.35973, 0, 0.75773, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
G2L["e2"] = Instance.new("LocalScript", G2L["e1"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.UICorner
G2L["e3"] = Instance.new("UICorner", G2L["e1"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton
G2L["e4"] = Instance.new("TextButton", G2L["bd"]);
G2L["e4"]["TextWrapped"] = true;
G2L["e4"]["BorderSizePixel"] = 0;
G2L["e4"]["TextSize"] = 14;
G2L["e4"]["TextScaled"] = true;
G2L["e4"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e4"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
G2L["e4"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["e4"]["Size"] = UDim2.new(0, 115, 0, 24);
G2L["e4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e4"]["Text"] = [[Off]];
G2L["e4"]["Position"] = UDim2.new(0.33258, 0, 0.84536, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
G2L["e5"] = Instance.new("LocalScript", G2L["e4"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.UICorner
G2L["e6"] = Instance.new("UICorner", G2L["e4"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton
G2L["e7"] = Instance.new("TextButton", G2L["bd"]);
G2L["e7"]["TextWrapped"] = true;
G2L["e7"]["BorderSizePixel"] = 0;
G2L["e7"]["TextSize"] = 14;
G2L["e7"]["TextScaled"] = true;
G2L["e7"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e7"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
G2L["e7"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["e7"]["Size"] = UDim2.new(0, 115, 0, 24);
G2L["e7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e7"]["Text"] = [[Off]];
G2L["e7"]["Position"] = UDim2.new(0.35973, 0, 0.92784, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
G2L["e8"] = Instance.new("LocalScript", G2L["e7"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.UICorner
G2L["e9"] = Instance.new("UICorner", G2L["e7"]);



-- Workspace.Gamepad Hub.Hub.Frame.Pages.Confing
G2L["ea"] = Instance.new("Frame", G2L["24"]);
G2L["ea"]["Visible"] = false;
G2L["ea"]["BorderSizePixel"] = 0;
G2L["ea"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ea"]["Size"] = UDim2.new(0, 442, 0, 390);
G2L["ea"]["Position"] = UDim2.new(-3.28, 0, -2.88, 0);
G2L["ea"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ea"]["Name"] = [[Confing]];


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Confing.TextLabel
G2L["eb"] = Instance.new("TextLabel", G2L["ea"]);
G2L["eb"]["TextWrapped"] = true;
G2L["eb"]["BorderSizePixel"] = 0;
G2L["eb"]["TextSize"] = 14;
G2L["eb"]["TextScaled"] = true;
G2L["eb"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["eb"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["eb"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["eb"]["BackgroundTransparency"] = 1;
G2L["eb"]["Size"] = UDim2.new(0, 200, 0, 95);
G2L["eb"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["eb"]["Text"] = [[Soon :)]];
G2L["eb"]["Position"] = UDim2.new(0.23982, 0, 0.3, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Info
G2L["ec"] = Instance.new("Frame", G2L["24"]);
G2L["ec"]["Visible"] = false;
G2L["ec"]["BorderSizePixel"] = 0;
G2L["ec"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ec"]["Size"] = UDim2.new(0, 442, 0, 388);
G2L["ec"]["Position"] = UDim2.new(-3.28, 0, -2.88, 0);
G2L["ec"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ec"]["Name"] = [[Info]];


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Info.TextLabel
G2L["ed"] = Instance.new("TextLabel", G2L["ec"]);
G2L["ed"]["TextWrapped"] = true;
G2L["ed"]["BorderSizePixel"] = 0;
G2L["ed"]["TextSize"] = 14;
G2L["ed"]["TextScaled"] = true;
G2L["ed"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ed"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["ed"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ed"]["BackgroundTransparency"] = 1;
G2L["ed"]["Size"] = UDim2.new(0, 211, 0, 65);
G2L["ed"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ed"]["Text"] = [[Made By Boymig44 :)]];
G2L["ed"]["Position"] = UDim2.new(0.19231, 0, 0.03093, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Info.TextLabel
G2L["ee"] = Instance.new("TextLabel", G2L["ec"]);
G2L["ee"]["TextWrapped"] = true;
G2L["ee"]["BorderSizePixel"] = 0;
G2L["ee"]["TextSize"] = 14;
G2L["ee"]["TextScaled"] = true;
G2L["ee"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ee"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["ee"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ee"]["BackgroundTransparency"] = 1;
G2L["ee"]["Size"] = UDim2.new(0, 143, 0, 37);
G2L["ee"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ee"]["Text"] = [[Pages:]];
G2L["ee"]["Position"] = UDim2.new(0.26923, 0, 0.23969, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Info.TextLabel
G2L["ef"] = Instance.new("TextLabel", G2L["ec"]);
G2L["ef"]["TextWrapped"] = true;
G2L["ef"]["BorderSizePixel"] = 0;
G2L["ef"]["TextSize"] = 14;
G2L["ef"]["TextScaled"] = true;
G2L["ef"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ef"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["ef"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ef"]["BackgroundTransparency"] = 1;
G2L["ef"]["Size"] = UDim2.new(0, 140, 0, 43);
G2L["ef"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ef"]["Text"] = [[Dashboard: See Your Information, Gamepads Connecteds Server Time.... Etc.]];
G2L["ef"]["Position"] = UDim2.new(0.06109, 0, 0.38918, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Info.TextLabel
G2L["f0"] = Instance.new("TextLabel", G2L["ec"]);
G2L["f0"]["TextWrapped"] = true;
G2L["f0"]["BorderSizePixel"] = 0;
G2L["f0"]["TextSize"] = 14;
G2L["f0"]["TextScaled"] = true;
G2L["f0"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f0"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["f0"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f0"]["BackgroundTransparency"] = 1;
G2L["f0"]["Size"] = UDim2.new(0, 140, 0, 43);
G2L["f0"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f0"]["Text"] = [[Buttons: See Buttons Of Your Gamepad, PS/Xbox/Generic.... Etc.]];
G2L["f0"]["Position"] = UDim2.new(0.06109, 0, 0.54639, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Info.TextLabel
G2L["f1"] = Instance.new("TextLabel", G2L["ec"]);
G2L["f1"]["TextWrapped"] = true;
G2L["f1"]["BorderSizePixel"] = 0;
G2L["f1"]["TextSize"] = 14;
G2L["f1"]["TextScaled"] = true;
G2L["f1"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f1"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["f1"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f1"]["BackgroundTransparency"] = 1;
G2L["f1"]["Size"] = UDim2.new(0, 140, 0, 43);
G2L["f1"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f1"]["Text"] = [[Thumbsticks: Reduce a Drift and Show Positions Of Stick1 and Stick2.]];
G2L["f1"]["Position"] = UDim2.new(0.45023, 0, 0.39175, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Info.TextLabel
G2L["f2"] = Instance.new("TextLabel", G2L["ec"]);
G2L["f2"]["TextWrapped"] = true;
G2L["f2"]["BorderSizePixel"] = 0;
G2L["f2"]["TextSize"] = 14;
G2L["f2"]["TextScaled"] = true;
G2L["f2"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f2"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["f2"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f2"]["BackgroundTransparency"] = 1;
G2L["f2"]["Size"] = UDim2.new(0, 140, 0, 43);
G2L["f2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f2"]["Text"] = [[Combos: The Combos of Buttons of your Gamepad. (Not Working)]];
G2L["f2"]["Position"] = UDim2.new(0.45023, 0, 0.5567, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Info.TextLabel
G2L["f3"] = Instance.new("TextLabel", G2L["ec"]);
G2L["f3"]["TextWrapped"] = true;
G2L["f3"]["BorderSizePixel"] = 0;
G2L["f3"]["TextSize"] = 14;
G2L["f3"]["TextScaled"] = true;
G2L["f3"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f3"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["f3"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f3"]["BackgroundTransparency"] = 1;
G2L["f3"]["Size"] = UDim2.new(0, 140, 0, 43);
G2L["f3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f3"]["Text"] = [[Vibration:  Test Vibration of Your Gamepad on each Button.]];
G2L["f3"]["Position"] = UDim2.new(0.06109, 0, 0.6933, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Info.TextLabel
G2L["f4"] = Instance.new("TextLabel", G2L["ec"]);
G2L["f4"]["TextWrapped"] = true;
G2L["f4"]["BorderSizePixel"] = 0;
G2L["f4"]["TextSize"] = 14;
G2L["f4"]["TextScaled"] = true;
G2L["f4"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f4"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["f4"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f4"]["BackgroundTransparency"] = 1;
G2L["f4"]["Size"] = UDim2.new(0, 140, 0, 43);
G2L["f4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f4"]["Text"] = [[Confing: Confings of the Gamepad Hub. (Soon)]];
G2L["f4"]["Position"] = UDim2.new(0.45023, 0, 0.6933, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Pages.Info.TextLabel
G2L["f5"] = Instance.new("TextLabel", G2L["ec"]);
G2L["f5"]["TextWrapped"] = true;
G2L["f5"]["BorderSizePixel"] = 0;
G2L["f5"]["TextSize"] = 14;
G2L["f5"]["TextScaled"] = true;
G2L["f5"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f5"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["f5"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f5"]["BackgroundTransparency"] = 1;
G2L["f5"]["Size"] = UDim2.new(0, 140, 0, 43);
G2L["f5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f5"]["Text"] = [[Info:  Info of the Gamepad Hub, Pages, Creators, Etc...]];
G2L["f5"]["Position"] = UDim2.new(0.06109, 0, 0.87113, 0);


-- Workspace.Gamepad Hub.Hub.Frame.TextButton
G2L["f6"] = Instance.new("TextButton", G2L["3"]);
G2L["f6"]["TextWrapped"] = true;
G2L["f6"]["BorderSizePixel"] = 0;
G2L["f6"]["TextSize"] = 14;
G2L["f6"]["TextScaled"] = true;
G2L["f6"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f6"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["f6"]["BackgroundTransparency"] = 1;
G2L["f6"]["Size"] = UDim2.new(0, 36, 0, 32);
G2L["f6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f6"]["Text"] = [[X]];
G2L["f6"]["Position"] = UDim2.new(0.93271, 0, -0.01193, 0);


-- Workspace.Gamepad Hub.Hub.Frame.TextButton.LocalScript
G2L["f7"] = Instance.new("LocalScript", G2L["f6"]);



-- Workspace.Gamepad Hub.Hub.Frame.Close
G2L["f8"] = Instance.new("Frame", G2L["3"]);
G2L["f8"]["Visible"] = false;
G2L["f8"]["BorderSizePixel"] = 0;
G2L["f8"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f8"]["Size"] = UDim2.new(0, 171, 0, 85);
G2L["f8"]["Position"] = UDim2.new(1.02617, 0, 0.06921, 0);
G2L["f8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f8"]["Name"] = [[Close]];


-- Workspace.Gamepad Hub.Hub.Frame.Close.UICorner
G2L["f9"] = Instance.new("UICorner", G2L["f8"]);



-- Workspace.Gamepad Hub.Hub.Frame.Close.Frame
G2L["fa"] = Instance.new("Frame", G2L["f8"]);
G2L["fa"]["BorderSizePixel"] = 0;
G2L["fa"]["BackgroundColor3"] = Color3.fromRGB(62, 62, 62);
G2L["fa"]["Size"] = UDim2.new(0, 171, 0, 1);
G2L["fa"]["Position"] = UDim2.new(0, 0, 0.22353, 0);
G2L["fa"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Close.TextLabel
G2L["fb"] = Instance.new("TextLabel", G2L["f8"]);
G2L["fb"]["TextWrapped"] = true;
G2L["fb"]["BorderSizePixel"] = 0;
G2L["fb"]["TextSize"] = 14;
G2L["fb"]["TextScaled"] = true;
G2L["fb"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["fb"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["fb"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["fb"]["BackgroundTransparency"] = 1;
G2L["fb"]["Size"] = UDim2.new(0, 171, 0, 20);
G2L["fb"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["fb"]["Text"] = [[Close]];


-- Workspace.Gamepad Hub.Hub.Frame.Close.TextButton
G2L["fc"] = Instance.new("TextButton", G2L["f8"]);
G2L["fc"]["TextWrapped"] = true;
G2L["fc"]["BorderSizePixel"] = 0;
G2L["fc"]["TextSize"] = 14;
G2L["fc"]["TextScaled"] = true;
G2L["fc"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["fc"]["BackgroundColor3"] = Color3.fromRGB(62, 62, 62);
G2L["fc"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["fc"]["Size"] = UDim2.new(0, 63, 0, 32);
G2L["fc"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["fc"]["Text"] = [[Yes]];
G2L["fc"]["Position"] = UDim2.new(0.08772, 0, 0.54118, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Close.TextButton.LocalScript
G2L["fd"] = Instance.new("LocalScript", G2L["fc"]);



-- Workspace.Gamepad Hub.Hub.Frame.Close.TextButton.UICorner
G2L["fe"] = Instance.new("UICorner", G2L["fc"]);



-- Workspace.Gamepad Hub.Hub.Frame.Close.TextButton
G2L["ff"] = Instance.new("TextButton", G2L["f8"]);
G2L["ff"]["TextWrapped"] = true;
G2L["ff"]["BorderSizePixel"] = 0;
G2L["ff"]["TextSize"] = 14;
G2L["ff"]["TextScaled"] = true;
G2L["ff"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ff"]["BackgroundColor3"] = Color3.fromRGB(62, 62, 62);
G2L["ff"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["ff"]["Size"] = UDim2.new(0, 63, 0, 32);
G2L["ff"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ff"]["Text"] = [[No]];
G2L["ff"]["Position"] = UDim2.new(0.53801, 0, 0.54118, 0);


-- Workspace.Gamepad Hub.Hub.Frame.Close.TextButton.LocalScript
G2L["100"] = Instance.new("LocalScript", G2L["ff"]);



-- Workspace.Gamepad Hub.Hub.Frame.Close.TextButton.UICorner
G2L["101"] = Instance.new("UICorner", G2L["ff"]);



-- Workspace.Gamepad Hub.Hub.Frame.Close.TextLabel
G2L["102"] = Instance.new("TextLabel", G2L["f8"]);
G2L["102"]["TextWrapped"] = true;
G2L["102"]["BorderSizePixel"] = 0;
G2L["102"]["TextSize"] = 14;
G2L["102"]["TextScaled"] = true;
G2L["102"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["102"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["102"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["102"]["BackgroundTransparency"] = 1;
G2L["102"]["Size"] = UDim2.new(0, 110, 0, 25);
G2L["102"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["102"]["Text"] = [[Do You Have Sure to Close This Script?]];
G2L["102"]["Position"] = UDim2.new(0.17544, 0, 0.23529, 0);


-- Require G2L wrapper
local G2L_REQUIRE = require;
local G2L_MODULES = {};
local function require(Module:ModuleScript)
    local ModuleState = G2L_MODULES[Module];
    if ModuleState then
        if not ModuleState.Required then
            ModuleState.Required = true;
            ModuleState.Value = ModuleState.Closure();
        end
        return ModuleState.Value;
    end;
    return G2L_REQUIRE(Module);
end

G2L_MODULES[G2L["27"]] = {
Closure = function()
    local script = G2L["27"];-- Decompiled with Konstant V2.1, a fast Luau decompiler made in Luau by plusgiant5 (https://discord.gg/brNTY8nX8t)
-- Decompiled on 2026-01-07 15:46:19
-- Luau version 6, Types version 3
-- Time taken: 0.006479 seconds

local UserInputService_upvr = game:GetService("UserInputService")
local module_upvr = {
	gamepadTypeFromNewestInput = "none";
	inputTypeThePlayerIsUsing = "KeyboardAndMouse";
	gamepadType = "none";
}
local tbl_upvr = {Enum.UserInputType.MouseButton1, Enum.UserInputType.MouseButton2, Enum.UserInputType.MouseButton3, Enum.UserInputType.MouseMovement, Enum.UserInputType.MouseWheel}
local tbl_upvr_4 = {Enum.KeyCode.ButtonA, Enum.KeyCode.ButtonB, Enum.KeyCode.ButtonX, Enum.KeyCode.ButtonY, Enum.KeyCode.ButtonL1, Enum.KeyCode.ButtonL2, Enum.KeyCode.ButtonL3, Enum.KeyCode.ButtonR1, Enum.KeyCode.ButtonR2, Enum.KeyCode.ButtonR3, Enum.KeyCode.ButtonStart, Enum.KeyCode.ButtonSelect, Enum.KeyCode.DPadUp, Enum.KeyCode.DPadDown, Enum.KeyCode.DPadLeft, Enum.KeyCode.DPadRight, Enum.KeyCode.Thumbstick1, Enum.KeyCode.Thumbstick2}
local tbl_upvr_3 = {"ButtonA", "ButtonB", "ButtonX", "ButtonY", "ButtonLB", "ButtonLT", "ButtonLS", "ButtonRB", "ButtonRT", "ButtonRS", "ButtonStart", "ButtonSelect"}
local tbl_upvr_2 = {"ButtonCross", "ButtonCircle", "ButtonSquare", "ButtonTriangle", "ButtonL1", "ButtonL2", "ButtonL3", "ButtonR1", "ButtonR2", "ButtonR3", "ButtonOptions", "ButtonTouchpad", "ButtonShare"}
local ITCRE_upvr = game.Lighting.ITCRE
UserInputService_upvr.InputBegan:Connect(function(arg1) -- Line 97
	--[[ Upvalues[7]:
		[1]: module_upvr (readonly)
		[2]: ITCRE_upvr (readonly)
		[3]: UserInputService_upvr (readonly)
		[4]: tbl_upvr (readonly)
		[5]: tbl_upvr_4 (readonly)
		[6]: tbl_upvr_3 (readonly)
		[7]: tbl_upvr_2 (readonly)
	]]
	if arg1.UserInputType == Enum.UserInputType.Keyboard and (module_upvr.inputTypeThePlayerIsUsing == "Gamepad" or module_upvr.inputTypeThePlayerIsUsing == "Touch") then
		print("New InputType detected: Keyboard and Mouse")
		module_upvr.inputTypeThePlayerIsUsing = "KeyboardAndMouse"
		ITCRE_upvr:FireServer(module_upvr.inputTypeThePlayerIsUsing)
		UserInputService_upvr.MouseIconEnabled = true
		script.Parent:WaitForChild("IngameUI").MobileButtons.Visible = false
	else
		for _, v in pairs(tbl_upvr) do
			if arg1.UserInputType == v and module_upvr.inputTypeThePlayerIsUsing ~= "KeyboardAndMouse" then
				print("New InputType detected: Keyboard and Mouse")
				module_upvr.inputTypeThePlayerIsUsing = "KeyboardAndMouse"
				ITCRE_upvr:FireServer(module_upvr.inputTypeThePlayerIsUsing)
				UserInputService_upvr.MouseIconEnabled = true
				script.Parent:WaitForChild("IngameUI").MobileButtons.Visible = false
				return
			end
		end
		for i_2, var31 in pairs(tbl_upvr_4) do
			if arg1.KeyCode == var31 then
				if module_upvr.inputTypeThePlayerIsUsing ~= "Gamepad" then
					print("New InputType detected: Gamepad")
					module_upvr.inputTypeThePlayerIsUsing = "Gamepad"
					ITCRE_upvr:FireServer(module_upvr.inputTypeThePlayerIsUsing)
					UserInputService_upvr.MouseIconEnabled = false
					script.Parent:WaitForChild("IngameUI").MobileButtons.Visible = false
				end
				local any_GetStringForKeyCode_result1 = UserInputService_upvr:GetStringForKeyCode(var31)
				for _, v_3 in pairs(tbl_upvr_3) do
					if v_3 == any_GetStringForKeyCode_result1 then
						module_upvr.gamepadTypeFromNewestInput = "Xbox"
					end
				end
				for i_4, v_4 in pairs(tbl_upvr_2) do
					if v_4 == any_GetStringForKeyCode_result1 then
						module_upvr.gamepadTypeFromNewestInput = "PlayStation"
					end
				end
				if module_upvr.gamepadTypeFromNewestInput ~= module_upvr.gamepadType then
					module_upvr.gamepadType = module_upvr.gamepadTypeFromNewestInput
					i_4 = module_upvr
					ITCRE_upvr:FireServer(i_4.inputTypeThePlayerIsUsing)
					print(module_upvr.gamepadType)
				end
			end
		end
		if arg1.UserInputType == Enum.UserInputType.Touch and module_upvr.inputTypeThePlayerIsUsing ~= "Touch" then
			module_upvr.gamepadTypeFromNewestInput = "none"
			print("New InputType detected: Touch")
			module_upvr.inputTypeThePlayerIsUsing = "Touch"
			i_2 = module_upvr
			ITCRE_upvr:FireServer(i_2.inputTypeThePlayerIsUsing)
			i_2 = "IngameUI"
			script.Parent:WaitForChild(i_2).MobileButtons.Visible = true
			i_2 = "TouchGui"
			local JumpButton_upvr = script.Parent:WaitForChild(i_2).TouchControlFrame:WaitForChild("JumpButton")
			i_2 = 0.715
			JumpButton_upvr.Position = UDim2.fromScale(0.845, i_2)
			var31 = game.Workspace
			i_2 = var31.RemoteEventsFolder
			function var31(arg1_2, arg2) -- Line 184
				--[[ Upvalues[1]:
					[1]: JumpButton_upvr (readonly)
				]]
				if arg1_2 == "JumpButton" then
					if arg2 == false then
						JumpButton_upvr.Visible = false
						return
					end
					if arg2 == true then
						JumpButton_upvr.Visible = true
					end
				end
			end
			i_2.UI.ToggleMobileButtons.OnClientEvent:Connect(var31)
			return
		end
	end
end)
return module_upvr

end;
};
-- Workspace.Gamepad Hub.Hub.Frame.Drag
local function C_4()
local script = G2L["4"];
	local UserInputService = game:GetService("UserInputService")
	
	local gui = script.Parent
	
	local dragging
	local dragInput
	local dragStart
	local startPos
	
	local function update(input)
		local delta = input.Position - dragStart
		gui.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	end
	
	gui.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = gui.Position
			
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	gui.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	UserInputService.InputChanged:Connect(function(input)
		if input == dragInput and dragging then
			update(input)
		end
	end)
end;
task.spawn(C_4);
-- Workspace.Gamepad Hub.Hub.Frame.Buttons.LocalScript
local function C_a()
local script = G2L["a"];
	-- ===============================
	-- GAMEPAD HUB - PAGE SYSTEM FINAL
	-- ===============================
	
	local player = game.Players.LocalPlayer
	local playerGui = player:WaitForChild("PlayerGui")
	
	local screenGui = playerGui:WaitForChild("Gamepad Hub")
	local hub = screenGui:WaitForChild("Hub")
	
	local mainFrame = hub:WaitForChild("Frame")
	local pagesContainer = mainFrame:WaitForChild("Pages")
	local buttonsContainer = mainFrame:WaitForChild("Buttons")
	
	-- REGRA: o container Pages NUNCA fica invisível
	pagesContainer.Visible = true
	
	-- 🔹 PÁGINAS REAIS (Dashboard NÃO está aqui)
	local PAGES = {
		Buttons = true,
		Confing = true,
		Thumbsticks = true,
		Combos = true,
		Vibration = true,
		Info = true,
	}
	
	-- ===============================
	-- FECHAR TODAS AS PÁGINAS
	-- ===============================
	local function DisableAllPages()
		for _, page in ipairs(pagesContainer:GetChildren()) do
			if page:IsA("Frame") and PAGES[page.Name] then
				page.Visible = false
			end
		end
	end
	
	-- limpa tudo ao iniciar
	DisableAllPages()
	
	-- ===============================
	-- CONECTAR BOTÕES
	-- ===============================
	for _, btn in ipairs(buttonsContainer:GetChildren()) do
		if btn:IsA("TextButton") or btn:IsA("ImageButton") then
	
			btn.MouseButton1Click:Connect(function()
				-- 🔴 DASHBOARD: só fecha tudo
				if btn.Name == "DashBoard" then
					DisableAllPages()
					return
				end
	
				-- botão que não corresponde a página
				if not PAGES[btn.Name] then
					return
				end
	
				-- comportamento normal
				DisableAllPages()
	
				local page = pagesContainer:FindFirstChild(btn.Name)
				if page then
					page.Visible = true
				else
					warn("Página não encontrada:", btn.Name)
				end
			end)
		end
	end
	
	print("✅ Sistema FINAL carregado (Dashboard = botão de reset)")
	
end;
task.spawn(C_a);
-- Workspace.Gamepad Hub.Hub.Frame.User.LocalScript
local function C_13()
local script = G2L["13"];
	 local imageLabel = script.Parent  -- Reference to the ImageLabel
	local player = game.Players.LocalPlayer  -- Reference to the local player
	
	-- Function to load profile picture
	local function updateProfilePicture()
		local profilePicUrl = "https://www.roblox.com/headshot-thumbnail/image?userId=" .. player.UserId .. "&width=420&height=420&format=png"
	
		-- Set the ImageLabel's Image property to the local player's profile picture
		imageLabel.Image = profilePicUrl
	end
	
	-- Wait for the local player to be available
	if player then
		-- Run the function to set the profile picture
		updateProfilePicture()
	end
	
end;
task.spawn(C_13);
-- Workspace.Gamepad Hub.Hub.Frame.Username.LocalScript
local function C_15()
local script = G2L["15"];
	local textLabel = script.Parent  -- Reference to the TextLabel
	
	-- Update the TextLabel text to the username
	textLabel.Text = game.Players.LocalPlayer.Name
	
end;
task.spawn(C_15);
-- Workspace.Gamepad Hub.Hub.Frame.Username.Welcome.script
local function C_17()
local script = G2L["17"];
	-- LocalScript dentro do TextLabel
	
	local textLabel = script.Parent
	local player = game.Players.LocalPlayer
	
	textLabel.Text = "Welcome Back, " .. player.Name .. "!"
	
end;
task.spawn(C_17);
-- Workspace.Gamepad Hub.Hub.Frame.Username.Gamepad Connected.script
local function C_19()
local script = G2L["19"];
	-- LocalScript dentro do TextLabel
	
	local textLabel = script.Parent
	local UserInputService = game:GetService("UserInputService")
	
	local function atualizarGamepads()
		local count = 0
		for _, device in pairs(UserInputService:GetConnectedGamepads()) do
			count = count + 1
		end
		textLabel.Text = "Gamepads Connecteds: " .. count
	end
	
	-- Atualiza quando o script roda
	atualizarGamepads()
	
	-- Atualiza quando um gamepad é conectado
	UserInputService.GamepadConnected:Connect(atualizarGamepads)
	
	-- Atualiza quando um gamepad é desconectado
	UserInputService.GamepadDisconnected:Connect(atualizarGamepads)
	
end;
task.spawn(C_19);
-- Workspace.Gamepad Hub.Hub.Frame.realtime.script
local function C_1b()
local script = G2L["1b"];
	local textLabel = script.Parent  -- Reference to the TextLabel
	
	-- Function to update the TextLabel with the current real time
	local function updateRealTime()
		while true do
			-- Get the current system time in a readable format (e.g., "HH:MM:SS")
			local realTime = os.date("%H:%M:%S")  -- Current time in HH:MM:SS format
	
			-- Update the TextLabel's text with the current real time
			textLabel.Text = "Time: " .. realTime
	
			-- Wait for 1 second before updating again
			wait(1)
		end
	end
	
	-- Start updating the real time
	updateRealTime()
	
end;
task.spawn(C_1b);
-- Workspace.Gamepad Hub.Hub.Frame.svtime.script
local function C_1d()
local script = G2L["1d"];
	local textLabel = script.Parent  -- Reference to the TextLabel
	
	-- Function to update the TextLabel with the server time
	local function updateServerTime()
		while true do
			-- Get the current server time in a readable format (e.g., "HH:MM:SS")
			local serverTime = os.date("%H:%M:%S")  -- Current server time in HH:MM:SS format
	
			-- Update the TextLabel's text with the server time
			textLabel.Text = "Server Time: " .. serverTime
	
			-- Wait for 1 second before updating again
			wait(1)
		end
	end
	
	-- Start updating the server time
	updateServerTime()
	
end;
task.spawn(C_1d);
-- Workspace.Gamepad Hub.Hub.Frame.jobid.script
local function C_1f()
local script = G2L["1f"];
	local textLabel = script.Parent  -- Reference to the TextLabel
	
	-- Function to update the TextLabel with the server's Job ID
	local function updateJobId()
		while true do
			-- Get the current Job ID
			local jobId = game.JobId
	
			-- Update the TextLabel's text with the Job ID
			textLabel.Text = "Job ID: " .. jobId
	
			-- Wait for 1 second before updating again (to keep it real-time)
			wait(1)
		end
	end
	
	-- Start updating the Job ID
	updateJobId()
	
end;
task.spawn(C_1f);
-- Workspace.Gamepad Hub.Hub.Frame.progress.LocalScript
local function C_21()
local script = G2L["21"];
	local textLabel = script.Parent -- Reference to the TextLabel
	local maxPercentage = 100       -- Maximum progress value
	
	-- Function to simulate loading
	local function updateProgress()
		for i = 0, maxPercentage do
			textLabel.Text = "Loading (" .. i .. "%)"
			wait(0.05 * (1 - (i / maxPercentage))) -- Increase speed as percentage goes up
		end
		textLabel.Text = "Success! You are now be able to use." -- Final message
	end
	
	-- Start updating progress
	updateProgress()
	
end;
task.spawn(C_21);
-- Workspace.Gamepad Hub.Hub.Frame.age.LocalScript
local function C_23()
local script = G2L["23"];
	local textLabel = script.Parent  -- Reference to the TextLabel
	
	-- Function to calculate the player's age in days
	local function calculateAgeInDays()
		local player = game.Players.LocalPlayer
		local birthday = player.AccountAge -- The player's account age in days
		return birthday
	end
	
	-- Update the TextLabel to show the player's age in days
	textLabel.Text = calculateAgeInDays() .. " Days"
	
end;
task.spawn(C_23);
-- Workspace.Gamepad Hub.Hub.Frame.Pages.Buttons.LocalScript
local function C_26()
local script = G2L["26"];
	-- Saved by UniversalSynSaveInstance (Join to Copy Games) https://discord.gg/wx4ThpAsmw
	
	-- Decompiled with Konstant V2.1, a fast Luau decompiler made in Luau by plusgiant5 (https://discord.gg/brNTY8nX8t)
	-- Decompiled on 2026-01-06 23:30:51
	-- Luau version 6, Types version 3
	-- Time taken: 0.020686 seconds
	
	local HapticService_upvr = game:GetService("HapticService")
	local UserInputService = game:GetService("UserInputService")
	local Xbox_upvr = script.Parent.Xbox
	local Buttons_upvr = Xbox_upvr.MainFrame.Buttons
	local Dpad_upvr = Xbox_upvr.MainFrame.Dpad
	local MainFrame_upvr = Xbox_upvr.MainFrame
	local Gamepad1_upvr = Enum.UserInputType.Gamepad1
	local function CheckVibrationSupport_upvr() -- Line 10, Named "CheckVibrationSupport"
		--[[ Upvalues[3]:
			[1]: HapticService_upvr (readonly)
			[2]: Gamepad1_upvr (readonly)
			[3]: Xbox_upvr (readonly)
		]]
		if HapticService_upvr:IsVibrationSupported(Gamepad1_upvr) and HapticService_upvr:IsMotorSupported(Gamepad1_upvr, Enum.VibrationMotor.Large) then
			for _, v in pairs(Xbox_upvr.Vibration:GetChildren()) do
				v.Visible = true
			end
			return true
		end
		return false
	end
	CheckVibrationSupport_upvr()
	UserInputService.GamepadConnected:Connect(function(arg1) -- Line 36
		--[[ Upvalues[2]:
			[1]: Xbox_upvr (readonly)
			[2]: CheckVibrationSupport_upvr (readonly)
		]]
		print("User has connected controller: "..tostring(arg1))
		Xbox_upvr.TextLabel.Text = "Gamepad Connected: "..tostring(arg1.Name)
		CheckVibrationSupport_upvr()
	end)
	UserInputService.GamepadDisconnected:Connect(function(arg1) -- Line 43
		--[[ Upvalues[2]:
			[1]: Xbox_upvr (readonly)
			[2]: CheckVibrationSupport_upvr (readonly)
		]]
		print("User has disconnected controller: "..tostring(arg1))
		Xbox_upvr.TextLabel.Text = "Gamepad Disconnected"
		CheckVibrationSupport_upvr()
	end)
	UserInputService.InputBegan:Connect(function(arg1, arg2) -- Line 52
		--[[ Upvalues[4]:
			[1]: Xbox_upvr (readonly)
			[2]: Buttons_upvr (readonly)
			[3]: Dpad_upvr (readonly)
			[4]: MainFrame_upvr (readonly)
		]]
		if arg1.UserInputType == Enum.UserInputType.Gamepad1 then
			Xbox_upvr.TextLabel.Text = "Gamepad Connected: Gamepad1"
			if arg1.KeyCode == Enum.KeyCode.ButtonY then
				Buttons_upvr.Y.BackgroundColor3 = Color3.fromRGB(99, 99, 99)
			end
			if arg1.KeyCode == Enum.KeyCode.ButtonX then
				Buttons_upvr.X.BackgroundColor3 = Color3.fromRGB(99, 99, 99)
			end
			if arg1.KeyCode == Enum.KeyCode.ButtonA then
				Buttons_upvr.A.BackgroundColor3 = Color3.fromRGB(99, 99, 99)
			end
			if arg1.KeyCode == Enum.KeyCode.ButtonB then
				Buttons_upvr.B.BackgroundColor3 = Color3.fromRGB(99, 99, 99)
			end
			if arg1.KeyCode == Enum.KeyCode.DPadUp then
				Dpad_upvr.Up.BackgroundColor3 = Color3.fromRGB(99, 99, 99)
			end
			if arg1.KeyCode == Enum.KeyCode.DPadDown then
				Dpad_upvr.Down.BackgroundColor3 = Color3.fromRGB(99, 99, 99)
			end
			if arg1.KeyCode == Enum.KeyCode.DPadLeft then
				Dpad_upvr.Left.BackgroundColor3 = Color3.fromRGB(99, 99, 99)
			end
			if arg1.KeyCode == Enum.KeyCode.DPadRight then
				Dpad_upvr.Right.BackgroundColor3 = Color3.fromRGB(99, 99, 99)
			end
			if arg1.KeyCode == Enum.KeyCode.ButtonL3 then
				MainFrame_upvr.LeftAnalog.TextLabel.BackgroundColor3 = Color3.fromRGB(99, 99, 99)
			end
			if arg1.KeyCode == Enum.KeyCode.ButtonR3 then
				MainFrame_upvr.RightAnalog.TextLabel.BackgroundColor3 = Color3.fromRGB(99, 99, 99)
			end
			if arg1.KeyCode == Enum.KeyCode.ButtonStart then
				MainFrame_upvr.Start.BackgroundColor3 = Color3.fromRGB(99, 99, 99)
			end
			if arg1.KeyCode == Enum.KeyCode.ButtonSelect then
				MainFrame_upvr.Select.BackgroundColor3 = Color3.fromRGB(99, 99, 99)
			end
			if arg1.KeyCode == Enum.KeyCode.ButtonL1 then
				MainFrame_upvr.LButtons.LB.BackgroundColor3 = Color3.fromRGB(99, 99, 99)
			end
			if arg1.KeyCode == Enum.KeyCode.ButtonR1 then
				MainFrame_upvr.RButtons.RB.BackgroundColor3 = Color3.fromRGB(99, 99, 99)
			end
		end
	end)
	UserInputService.InputEnded:Connect(function(arg1, arg2) -- Line 139
		--[[ Upvalues[3]:
			[1]: Buttons_upvr (readonly)
			[2]: Dpad_upvr (readonly)
			[3]: MainFrame_upvr (readonly)
		]]
		if arg1.UserInputType == Enum.UserInputType.Gamepad1 then
			if arg1.KeyCode == Enum.KeyCode.ButtonY then
				Buttons_upvr.Y.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
			end
			if arg1.KeyCode == Enum.KeyCode.ButtonX then
				Buttons_upvr.X.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
			end
			if arg1.KeyCode == Enum.KeyCode.ButtonA then
				Buttons_upvr.A.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
			end
			if arg1.KeyCode == Enum.KeyCode.ButtonB then
				Buttons_upvr.B.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
			end
			if arg1.KeyCode == Enum.KeyCode.DPadUp then
				Dpad_upvr.Up.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
			end
			if arg1.KeyCode == Enum.KeyCode.DPadDown then
				Dpad_upvr.Down.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
			end
			if arg1.KeyCode == Enum.KeyCode.DPadLeft then
				Dpad_upvr.Left.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
			end
			if arg1.KeyCode == Enum.KeyCode.DPadRight then
				Dpad_upvr.Right.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
			end
			if arg1.KeyCode == Enum.KeyCode.ButtonL3 then
				MainFrame_upvr.LeftAnalog.TextLabel.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
			end
			if arg1.KeyCode == Enum.KeyCode.ButtonR3 then
				MainFrame_upvr.RightAnalog.TextLabel.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
			end
			if arg1.KeyCode == Enum.KeyCode.ButtonStart then
				MainFrame_upvr.Start.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
			end
			if arg1.KeyCode == Enum.KeyCode.ButtonSelect then
				MainFrame_upvr.Select.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
			end
			if arg1.KeyCode == Enum.KeyCode.ButtonL1 then
				MainFrame_upvr.LButtons.LB.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
			end
			if arg1.KeyCode == Enum.KeyCode.ButtonR1 then
				MainFrame_upvr.RButtons.RB.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
			end
		end
	end)
	UserInputService.InputChanged:Connect(function(arg1) -- Line 229
		--[[ Upvalues[1]:
			[1]: MainFrame_upvr (readonly)
		]]
		if arg1.KeyCode == Enum.KeyCode.Thumbstick1 then
			MainFrame_upvr.LPos.Text = "X: "..arg1.Position.X.."\nY:"..arg1.Position.Y
			MainFrame_upvr.LeftAnalog.TextLabel.Position = UDim2.fromScale((arg1.Position.X + 1) / 2, (1 - arg1.Position.Y - 1 + 1) / 2)
		end
		if arg1.KeyCode == Enum.KeyCode.Thumbstick2 then
			MainFrame_upvr.RPos.Text = "X: "..arg1.Position.X.."\nY:"..arg1.Position.Y
			MainFrame_upvr.RightAnalog.TextLabel.Position = UDim2.fromScale((arg1.Position.X + 1) / 2, (1 - arg1.Position.Y - 1 + 1) / 2)
		end
		if arg1.KeyCode == Enum.KeyCode.ButtonR2 then
			MainFrame_upvr.RButtons.Trigger.Transparency = arg1.Position.Z
		end
		if arg1.KeyCode == Enum.KeyCode.ButtonL2 then
			MainFrame_upvr.LButtons.Trigger.Transparency = arg1.Position.Z
		end
	end)
	Xbox_upvr.Vibration.AllVib.MouseButton1Down:Connect(function() -- Line 260
		--[[ Upvalues[2]:
			[1]: HapticService_upvr (readonly)
			[2]: Gamepad1_upvr (readonly)
		]]
		HapticService_upvr:SetMotor(Gamepad1_upvr, Enum.VibrationMotor.Large, 1)
		HapticService_upvr:SetMotor(Gamepad1_upvr, Enum.VibrationMotor.Small, 1)
	end)
	Xbox_upvr.Vibration.LeftVib.MouseButton1Down:Connect(function() -- Line 264
		--[[ Upvalues[2]:
			[1]: HapticService_upvr (readonly)
			[2]: Gamepad1_upvr (readonly)
		]]
		HapticService_upvr:SetMotor(Gamepad1_upvr, Enum.VibrationMotor.Large, 1)
	end)
	Xbox_upvr.Vibration.RightVib.MouseButton1Down:Connect(function() -- Line 267
		--[[ Upvalues[2]:
			[1]: HapticService_upvr (readonly)
			[2]: Gamepad1_upvr (readonly)
		]]
		HapticService_upvr:SetMotor(Gamepad1_upvr, Enum.VibrationMotor.Small, 1)
	end)
	Xbox_upvr.Vibration.AllVib.MouseButton1Up:Connect(function() -- Line 271
		--[[ Upvalues[2]:
			[1]: HapticService_upvr (readonly)
			[2]: Gamepad1_upvr (readonly)
		]]
		HapticService_upvr:SetMotor(Gamepad1_upvr, Enum.VibrationMotor.Large, 0)
		HapticService_upvr:SetMotor(Gamepad1_upvr, Enum.VibrationMotor.Small, 0)
	end)
	Xbox_upvr.Vibration.LeftVib.MouseButton1Up:Connect(function() -- Line 275
		--[[ Upvalues[2]:
			[1]: HapticService_upvr (readonly)
			[2]: Gamepad1_upvr (readonly)
		]]
		HapticService_upvr:SetMotor(Gamepad1_upvr, Enum.VibrationMotor.Large, 0)
	end)
	Xbox_upvr.Vibration.RightVib.MouseButton1Up:Connect(function() -- Line 278
		--[[ Upvalues[2]:
			[1]: HapticService_upvr (readonly)
			[2]: Gamepad1_upvr (readonly)
		]]
		HapticService_upvr:SetMotor(Gamepad1_upvr, Enum.VibrationMotor.Small, 0)
	end)
end;
task.spawn(C_26);
-- Workspace.Gamepad Hub.Hub.Frame.Pages.Thumbsticks.TextButton.LocalScript
local function C_90()
local script = G2L["90"];
	-- LocalScript dentro do TextButton
	
	local button = script.Parent
	
	local Players = game:GetService("Players")
	local UserInputService = game:GetService("UserInputService")
	local RunService = game:GetService("RunService")
	
	local player = Players.LocalPlayer
	local camera = workspace.CurrentCamera
	
	-- CONFIG
	local DEADZONE = 0.15
	local CAMERA_SENS = 3
	
	-- ESTADO
	local enabled = false
	local moveInput = Vector2.zero
	local lookInput = Vector2.zero
	local yaw = 0
	local pitch = 0
	
	local humanoid
	local root
	
	-- ======================
	-- DEADZONE
	-- ======================
	local function applyDeadzone(v)
		if math.abs(v) < DEADZONE then
			return 0
		end
		return (v - math.sign(v) * DEADZONE) / (1 - DEADZONE)
	end
	
	-- ======================
	-- VISUAL DO BOTÃO
	-- ======================
	local function updateButton()
		if enabled then
			button.Text = "ON"
			button.BackgroundColor3 = Color3.fromRGB(60, 200, 60)
		else
			button.Text = "OFF"
			button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
		end
	end
	
	updateButton()
	
	button.Activated:Connect(function()
		enabled = not enabled
		updateButton()
	
		if not enabled then
			camera.CameraType = Enum.CameraType.Custom
		end
	end)
	
	-- ======================
	-- PERSONAGEM
	-- ======================
	local function setupCharacter(char)
		humanoid = char:WaitForChild("Humanoid")
		root = char:WaitForChild("HumanoidRootPart")
	end
	
	if player.Character then
		setupCharacter(player.Character)
	end
	
	player.CharacterAdded:Connect(setupCharacter)
	
	-- ======================
	-- INPUT GAMEPAD
	-- ======================
	UserInputService.InputChanged:Connect(function(input)
		if not enabled then return end
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		-- STICK 1 → ANDAR
		if input.KeyCode == Enum.KeyCode.Thumbstick1 then
			moveInput = Vector2.new(
				applyDeadzone(input.Position.X),
				applyDeadzone(input.Position.Y)
			)
		end
	
		-- STICK 2 → CÂMERA
		if input.KeyCode == Enum.KeyCode.Thumbstick2 then
			lookInput = Vector2.new(
				applyDeadzone(input.Position.X),
				applyDeadzone(input.Position.Y)
			)
		end
	end)
	
	-- ======================
	-- LOOP
	-- ======================
	RunService.RenderStepped:Connect(function()
		if not enabled then return end
		if not humanoid or not root then return end
	
		-- ANDAR (stick 1)
		local moveVector = Vector3.new(
			moveInput.X,
			0,
			-moveInput.Y
		)
		humanoid:Move(moveVector, true)
	
		-- CÂMERA (stick 2)
		yaw -= lookInput.X * CAMERA_SENS
		pitch -= lookInput.Y * CAMERA_SENS
		pitch = math.clamp(pitch, -80, 80)
	
		camera.CameraType = Enum.CameraType.Scriptable
		camera.CFrame =
			CFrame.new(root.Position)
			* CFrame.Angles(0, math.rad(yaw), 0)
			* CFrame.Angles(math.rad(pitch), 0, 0)
			* CFrame.new(0, 2, 8)
	end)
	
end;
task.spawn(C_90);
-- Workspace.Gamepad Hub.Hub.Frame.Pages.Thumbsticks.TextLabel.LocalScript
local function C_97()
local script = G2L["97"];
	-- LocalScript dentro do TextLabel
	
	local label = script.Parent
	local UserInputService = game:GetService("UserInputService")
	
	label.Text = "Stick1\nX: 0.00\nY: 0.00"
	
	UserInputService.InputChanged:Connect(function(input)
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
		if input.KeyCode ~= Enum.KeyCode.Thumbstick1 then return end
	
		local x = input.Position.X
		local y = input.Position.Y
	
		label.Text = string.format(
			"Stick1\nX: %.2f\nY: %.2f",
			x,
			y
		)
	end)
	
end;
task.spawn(C_97);
-- Workspace.Gamepad Hub.Hub.Frame.Pages.Thumbsticks.TextLabel.LocalScript
local function C_99()
local script = G2L["99"];
	-- LocalScript dentro do TextLabel
	
	local label = script.Parent
	local UserInputService = game:GetService("UserInputService")
	
	label.Text = "Stick2\nX: 0.00\nY: 0.00"
	
	UserInputService.InputChanged:Connect(function(input)
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
		if input.KeyCode ~= Enum.KeyCode.Thumbstick2 then return end
	
		local x = input.Position.X
		local y = input.Position.Y
	
		label.Text = string.format(
			"Stick2\nX: %.2f\nY: %.2f",
			x,
			y
		)
	end)
	
end;
task.spawn(C_99);
-- Workspace.Gamepad Hub.Hub.Frame.Pages.Combos.Combo
local function C_9b()
local script = G2L["9b"];
	-- LocalScript
	
	local Players = game:GetService("Players")
	local UserInputService = game:GetService("UserInputService")
	local RunService = game:GetService("RunService")
	
	local player = Players.LocalPlayer
	
	-- =====================
	-- COMBO (PS)
	-- 🔺 ⬜ ❌ RT
	-- =====================
	local combo = {
		Enum.KeyCode.ButtonY, -- Triângulo
		Enum.KeyCode.ButtonX, -- Quadrado
		Enum.KeyCode.ButtonA, -- X (Cross)
		Enum.KeyCode.ButtonR2 -- RT
	}
	
	local comboIndex = 1
	local lastInput = 0
	local comboTimeout = 1.5
	
	-- =====================
	-- FLY CONFIG
	-- =====================
	local flying = false
	local speed = 60
	
	local bv, bg
	
	-- =====================
	-- FLY FUNÇÕES
	-- =====================
	local function startFly()
		if flying then return end
		flying = true
	
		local char = player.Character or player.CharacterAdded:Wait()
		local root = char:WaitForChild("HumanoidRootPart")
		local humanoid = char:WaitForChild("Humanoid")
	
		humanoid.PlatformStand = true
	
		bv = Instance.new("BodyVelocity")
		bv.MaxForce = Vector3.new(1e6, 1e6, 1e6)
		bv.Velocity = Vector3.zero
		bv.Parent = root
	
		bg = Instance.new("BodyGyro")
		bg.MaxTorque = Vector3.new(1e6, 1e6, 1e6)
		bg.CFrame = root.CFrame
		bg.Parent = root
	end
	
	local function stopFly()
		flying = false
	
		local char = player.Character
		if not char then return end
	
		local humanoid = char:FindFirstChild("Humanoid")
		if humanoid then
			humanoid.PlatformStand = false
		end
	
		if bv then bv:Destroy() end
		if bg then bg:Destroy() end
	end
	
	-- =====================
	-- MOVIMENTO DO FLY
	-- =====================
	RunService.RenderStepped:Connect(function()
		if not flying then return end
	
		local char = player.Character
		if not char then return end
		local root = char:FindFirstChild("HumanoidRootPart")
		if not root then return end
	
		local cam = workspace.CurrentCamera
	
		bg.CFrame = cam.CFrame
		bv.Velocity = cam.CFrame.LookVector * speed
	end)
	
	-- =====================
	-- DETECTOR DE COMBO
	-- =====================
	UserInputService.InputBegan:Connect(function(input, gp)
		if gp then return end
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		local now = tick()
		if now - lastInput > comboTimeout then
			comboIndex = 1
		end
	
		if input.KeyCode == combo[comboIndex] then
			comboIndex += 1
			lastInput = now
	
			if comboIndex > #combo then
				print("🔥 FLY ATIVADO")
				startFly()
				comboIndex = 1
			end
		else
			comboIndex = 1
		end
	
		-- DESLIGAR COM BOLINHA
		if input.KeyCode == Enum.KeyCode.ButtonB then
			print("🛑 FLY DESLIGADO")
			stopFly()
		end
	end)
	
end;
task.spawn(C_9b);
-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
local function C_ca()
local script = G2L["ca"];
	-- LocalScript
	
	local UserInputService = game:GetService("UserInputService")
	local HapticService = game:GetService("HapticService")
	
	local button = script.Parent
	
	-- ===== ESTADO =====
	local enabled = false
	local holding = false
	
	-- ===== UI =====
	button.Text = "OFF"
	button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
	
	local function updateUI()
		if enabled then
			button.Text = "ON"
			button.BackgroundColor3 = Color3.fromRGB(60, 200, 60)
		else
			button.Text = "OFF"
			button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
		end
	end
	
	button.Activated:Connect(function()
		enabled = not enabled
		updateUI()
	end)
	
	-- ===== SUPORTE REAL =====
	local function canVibrate()
		return HapticService:IsVibrationSupported(
			Enum.UserInputType.Gamepad1,
			Enum.VibrationMotor.Large
		)
	end
	
	-- ===== LOOP DE VIBRAÇÃO =====
	task.spawn(function()
		while true do
			task.wait(0.05)
	
			if enabled and holding and canVibrate() then
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					1
				)
			else
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					0
				)
			end
		end
	end)
	
	-- ===== INPUT RT / R2 =====
	UserInputService.InputBegan:Connect(function(input, gp)
		if gp then return end
		if not enabled then return end
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		-- RT (Xbox) / R2 (PlayStation)
		if input.KeyCode == Enum.KeyCode.ButtonR2 then
			holding = true
		end
	end)
	
	UserInputService.InputEnded:Connect(function(input)
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		if input.KeyCode == Enum.KeyCode.ButtonR2 then
			holding = false
		end
	end)
	
end;
task.spawn(C_ca);
-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
local function C_cd()
local script = G2L["cd"];
	-- LocalScript
	
	local UserInputService = game:GetService("UserInputService")
	local HapticService = game:GetService("HapticService")
	
	local button = script.Parent
	
	-- ===== ESTADO =====
	local enabled = false
	local holding = false
	
	-- ===== UI =====
	button.Text = "OFF"
	button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
	
	local function updateUI()
		if enabled then
			button.Text = "ON"
			button.BackgroundColor3 = Color3.fromRGB(60, 200, 60)
		else
			button.Text = "OFF"
			button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
		end
	end
	
	button.Activated:Connect(function()
		enabled = not enabled
		updateUI()
	end)
	
	-- ===== SUPORTE =====
	local function canVibrate()
		return HapticService:IsVibrationSupported(
			Enum.UserInputType.Gamepad1,
			Enum.VibrationMotor.Large
		)
	end
	
	-- ===== LOOP DE VIBRAÇÃO =====
	task.spawn(function()
		while true do
			task.wait(0.05)
	
			if enabled and holding and canVibrate() then
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					1
				)
			else
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					0
				)
			end
		end
	end)
	
	-- ===== INPUT LT / L2 =====
	UserInputService.InputBegan:Connect(function(input, gp)
		if gp then return end
		if not enabled then return end
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		-- LT (Xbox) / L2 (PlayStation)
		if input.KeyCode == Enum.KeyCode.ButtonL2 then
			holding = true
		end
	end)
	
	UserInputService.InputEnded:Connect(function(input)
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		if input.KeyCode == Enum.KeyCode.ButtonL2 then
			holding = false
		end
	end)
	
end;
task.spawn(C_cd);
-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
local function C_d0()
local script = G2L["d0"];
	-- LocalScript
	
	local UserInputService = game:GetService("UserInputService")
	local HapticService = game:GetService("HapticService")
	
	local button = script.Parent
	
	-- ===== ESTADO =====
	local enabled = false
	local holding = false
	
	-- ===== UI =====
	button.Text = "OFF"
	button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
	
	local function updateUI()
		if enabled then
			button.Text = "ON"
			button.BackgroundColor3 = Color3.fromRGB(60, 200, 60)
		else
			button.Text = "OFF"
			button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
		end
	end
	
	button.Activated:Connect(function()
		enabled = not enabled
		updateUI()
	end)
	
	-- ===== SUPORTE =====
	local function canVibrate()
		return HapticService:IsVibrationSupported(
			Enum.UserInputType.Gamepad1,
			Enum.VibrationMotor.Large
		)
	end
	
	-- ===== LOOP DE VIBRAÇÃO =====
	task.spawn(function()
		while true do
			task.wait(0.05)
	
			if enabled and holding and canVibrate() then
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					1
				)
			else
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					0
				)
			end
		end
	end)
	
	-- ===== INPUT A / X =====
	UserInputService.InputBegan:Connect(function(input, gp)
		if gp then return end
		if not enabled then return end
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		-- A (Xbox) / X (PlayStation)
		if input.KeyCode == Enum.KeyCode.ButtonA then
			holding = true
		end
	end)
	
	UserInputService.InputEnded:Connect(function(input)
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		if input.KeyCode == Enum.KeyCode.ButtonA then
			holding = false
		end
	end)
	
end;
task.spawn(C_d0);
-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
local function C_d3()
local script = G2L["d3"];
	-- LocalScript
	
	local UserInputService = game:GetService("UserInputService")
	local HapticService = game:GetService("HapticService")
	
	local button = script.Parent
	
	-- ===== ESTADO =====
	local enabled = false
	local holding = false
	
	-- ===== UI =====
	button.Text = "OFF"
	button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
	
	local function updateUI()
		if enabled then
			button.Text = "ON"
			button.BackgroundColor3 = Color3.fromRGB(60, 200, 60)
		else
			button.Text = "OFF"
			button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
		end
	end
	
	button.Activated:Connect(function()
		enabled = not enabled
		updateUI()
	end)
	
	-- ===== SUPORTE =====
	local function canVibrate()
		return HapticService:IsVibrationSupported(
			Enum.UserInputType.Gamepad1,
			Enum.VibrationMotor.Large
		)
	end
	
	-- ===== LOOP DE VIBRAÇÃO =====
	task.spawn(function()
		while true do
			task.wait(0.05)
	
			if enabled and holding and canVibrate() then
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					1
				)
			else
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					0
				)
			end
		end
	end)
	
	-- ===== INPUT Y / TRIÂNGULO =====
	UserInputService.InputBegan:Connect(function(input, gp)
		if gp then return end
		if not enabled then return end
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		-- Y (Xbox) / Triângulo (PlayStation)
		if input.KeyCode == Enum.KeyCode.ButtonY then
			holding = true
		end
	end)
	
	UserInputService.InputEnded:Connect(function(input)
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		if input.KeyCode == Enum.KeyCode.ButtonY then
			holding = false
		end
	end)
	
end;
task.spawn(C_d3);
-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
local function C_d6()
local script = G2L["d6"];
	-- LocalScript
	
	local UserInputService = game:GetService("UserInputService")
	local HapticService = game:GetService("HapticService")
	
	local button = script.Parent
	
	-- ===== ESTADO =====
	local enabled = false
	local holding = false
	
	-- ===== UI =====
	button.Text = "OFF"
	button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
	
	local function updateUI()
		if enabled then
			button.Text = "ON"
			button.BackgroundColor3 = Color3.fromRGB(60, 200, 60)
		else
			button.Text = "OFF"
			button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
		end
	end
	
	button.Activated:Connect(function()
		enabled = not enabled
		updateUI()
	end)
	
	-- ===== CHECAGEM REAL =====
	local function canVibrate()
		return HapticService:IsVibrationSupported(
			Enum.UserInputType.Gamepad1,
			Enum.VibrationMotor.Large
		)
	end
	
	-- ===== LOOP DE VIBRAÇÃO (OBRIGATÓRIO) =====
	task.spawn(function()
		while true do
			task.wait(0.05)
	
			if enabled and holding and canVibrate() then
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					1
				)
			else
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					0
				)
			end
		end
	end)
	
	-- ===== INPUT =====
	UserInputService.InputBegan:Connect(function(input, gp)
		if gp then return end
		if not enabled then return end
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		if input.KeyCode == Enum.KeyCode.ButtonX then
			holding = true
		end
	end)
	
	UserInputService.InputEnded:Connect(function(input)
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		if input.KeyCode == Enum.KeyCode.ButtonX then
			holding = false
		end
	end)
	
end;
task.spawn(C_d6);
-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
local function C_d9()
local script = G2L["d9"];
	-- LocalScript
	
	local UserInputService = game:GetService("UserInputService")
	local HapticService = game:GetService("HapticService")
	
	local button = script.Parent
	
	-- ===== ESTADO =====
	local enabled = false
	local holding = false
	
	-- ===== UI =====
	button.Text = "OFF"
	button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
	
	local function updateUI()
		if enabled then
			button.Text = "ON"
			button.BackgroundColor3 = Color3.fromRGB(60, 200, 60)
		else
			button.Text = "OFF"
			button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
		end
	end
	
	button.Activated:Connect(function()
		enabled = not enabled
		updateUI()
	end)
	
	-- ===== SUPORTE =====
	local function canVibrate()
		return HapticService:IsVibrationSupported(
			Enum.UserInputType.Gamepad1,
			Enum.VibrationMotor.Large
		)
	end
	
	-- ===== LOOP DE VIBRAÇÃO =====
	task.spawn(function()
		while true do
			task.wait(0.05)
	
			if enabled and holding and canVibrate() then
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					1
				)
			else
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					0
				)
			end
		end
	end)
	
	-- ===== INPUT B / CIRCLE =====
	UserInputService.InputBegan:Connect(function(input, gp)
		if gp then return end
		if not enabled then return end
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		-- B (Xbox) / Circle (PlayStation)
		if input.KeyCode == Enum.KeyCode.ButtonB then
			holding = true
		end
	end)
	
	UserInputService.InputEnded:Connect(function(input)
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		if input.KeyCode == Enum.KeyCode.ButtonB then
			holding = false
		end
	end)
	
end;
task.spawn(C_d9);
-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
local function C_dc()
local script = G2L["dc"];
	-- LocalScript
	
	local UserInputService = game:GetService("UserInputService")
	local HapticService = game:GetService("HapticService")
	
	local button = script.Parent
	
	-- ===== ESTADO =====
	local enabled = false
	local holding = false
	
	-- ===== UI =====
	button.Text = "OFF"
	button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
	
	local function updateUI()
		if enabled then
			button.Text = "ON"
			button.BackgroundColor3 = Color3.fromRGB(60, 200, 60)
		else
			button.Text = "OFF"
			button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
		end
	end
	
	button.Activated:Connect(function()
		enabled = not enabled
		updateUI()
	end)
	
	-- ===== SUPORTE =====
	local function canVibrate()
		return HapticService:IsVibrationSupported(
			Enum.UserInputType.Gamepad1,
			Enum.VibrationMotor.Large
		)
	end
	
	-- ===== LOOP DE VIBRAÇÃO =====
	task.spawn(function()
		while true do
			task.wait(0.05)
	
			if enabled and holding and canVibrate() then
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					1
				)
			else
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					0
				)
			end
		end
	end)
	
	-- ===== INPUT RB / R1 =====
	UserInputService.InputBegan:Connect(function(input, gp)
		if gp then return end
		if not enabled then return end
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		-- RB (Xbox) / R1 (PlayStation)
		if input.KeyCode == Enum.KeyCode.ButtonR1 then
			holding = true
		end
	end)
	
	UserInputService.InputEnded:Connect(function(input)
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		if input.KeyCode == Enum.KeyCode.ButtonR1 then
			holding = false
		end
	end)
	
end;
task.spawn(C_dc);
-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
local function C_df()
local script = G2L["df"];
	-- LocalScript
	
	local UserInputService = game:GetService("UserInputService")
	local HapticService = game:GetService("HapticService")
	
	local button = script.Parent
	
	-- ===== ESTADO =====
	local enabled = false
	local holding = false
	
	-- ===== UI =====
	button.Text = "OFF"
	button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
	
	local function updateUI()
		if enabled then
			button.Text = "ON"
			button.BackgroundColor3 = Color3.fromRGB(60, 200, 60)
		else
			button.Text = "OFF"
			button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
		end
	end
	
	button.Activated:Connect(function()
		enabled = not enabled
		updateUI()
	end)
	
	-- ===== SUPORTE =====
	local function canVibrate()
		return HapticService:IsVibrationSupported(
			Enum.UserInputType.Gamepad1,
			Enum.VibrationMotor.Large
		)
	end
	
	-- ===== LOOP DE VIBRAÇÃO =====
	task.spawn(function()
		while true do
			task.wait(0.05)
	
			if enabled and holding and canVibrate() then
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					1
				)
			else
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					0
				)
			end
		end
	end)
	
	-- ===== INPUT LB / L1 =====
	UserInputService.InputBegan:Connect(function(input, gp)
		if gp then return end
		if not enabled then return end
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		-- LB (Xbox) / L1 (PlayStation)
		if input.KeyCode == Enum.KeyCode.ButtonL1 then
			holding = true
		end
	end)
	
	UserInputService.InputEnded:Connect(function(input)
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		if input.KeyCode == Enum.KeyCode.ButtonL1 then
			holding = false
		end
	end)
	
end;
task.spawn(C_df);
-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
local function C_e2()
local script = G2L["e2"];
	-- LocalScript
	
	local UserInputService = game:GetService("UserInputService")
	local HapticService = game:GetService("HapticService")
	
	local button = script.Parent
	
	-- ===== ESTADO =====
	local enabled = false
	local holding = false
	
	-- ===== UI =====
	button.Text = "OFF"
	button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
	
	local function updateUI()
		if enabled then
			button.Text = "ON"
			button.BackgroundColor3 = Color3.fromRGB(60, 200, 60)
		else
			button.Text = "OFF"
			button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
		end
	end
	
	button.Activated:Connect(function()
		enabled = not enabled
		updateUI()
	end)
	
	-- ===== SUPORTE =====
	local function canVibrate()
		return HapticService:IsVibrationSupported(
			Enum.UserInputType.Gamepad1,
			Enum.VibrationMotor.Large
		)
	end
	
	-- ===== LOOP DE VIBRAÇÃO =====
	task.spawn(function()
		while true do
			task.wait(0.05)
	
			if enabled and holding and canVibrate() then
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					1
				)
			else
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					0
				)
			end
		end
	end)
	
	-- ===== INPUT SELECT / SHARE =====
	UserInputService.InputBegan:Connect(function(input, gp)
		if gp then return end
		if not enabled then return end
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		-- Select (Xbox) / Share (PlayStation)
		if input.KeyCode == Enum.KeyCode.ButtonSelect then
			holding = true
		end
	end)
	
	UserInputService.InputEnded:Connect(function(input)
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		if input.KeyCode == Enum.KeyCode.ButtonSelect then
			holding = false
		end
	end)
	
end;
task.spawn(C_e2);
-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
local function C_e5()
local script = G2L["e5"];
	-- LocalScript
	
	local UserInputService = game:GetService("UserInputService")
	local HapticService = game:GetService("HapticService")
	
	local button = script.Parent
	
	-- ===== ESTADO =====
	local enabled = false
	local holding = false
	
	-- ===== UI =====
	button.Text = "OFF"
	button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
	
	local function updateUI()
		if enabled then
			button.Text = "ON"
			button.BackgroundColor3 = Color3.fromRGB(60, 200, 60)
		else
			button.Text = "OFF"
			button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
		end
	end
	
	button.Activated:Connect(function()
		enabled = not enabled
		updateUI()
	end)
	
	-- ===== SUPORTE =====
	local function canVibrate()
		return HapticService:IsVibrationSupported(
			Enum.UserInputType.Gamepad1,
			Enum.VibrationMotor.Large
		)
	end
	
	-- ===== LOOP DE VIBRAÇÃO =====
	task.spawn(function()
		while true do
			task.wait(0.05)
	
			if enabled and holding and canVibrate() then
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					1
				)
			else
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					0
				)
			end
		end
	end)
	
	-- ===== INPUT RS / R3 =====
	UserInputService.InputBegan:Connect(function(input, gp)
		if gp then return end
		if not enabled then return end
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		-- RS (Xbox) / R3 (PlayStation)
		if input.KeyCode == Enum.KeyCode.ButtonR3 then
			holding = true
		end
	end)
	
	UserInputService.InputEnded:Connect(function(input)
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		if input.KeyCode == Enum.KeyCode.ButtonR3 then
			holding = false
		end
	end)
	
end;
task.spawn(C_e5);
-- Workspace.Gamepad Hub.Hub.Frame.Pages.Vibration.TextButton.LocalScript
local function C_e8()
local script = G2L["e8"];
	-- LocalScript
	
	local UserInputService = game:GetService("UserInputService")
	local HapticService = game:GetService("HapticService")
	
	local button = script.Parent
	
	-- ===== ESTADO =====
	local enabled = false
	local holding = false
	
	-- ===== UI =====
	button.Text = "OFF"
	button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
	
	local function updateUI()
		if enabled then
			button.Text = "ON"
			button.BackgroundColor3 = Color3.fromRGB(60, 200, 60)
		else
			button.Text = "OFF"
			button.BackgroundColor3 = Color3.fromRGB(200, 60, 60)
		end
	end
	
	button.Activated:Connect(function()
		enabled = not enabled
		updateUI()
	end)
	
	-- ===== SUPORTE =====
	local function canVibrate()
		return HapticService:IsVibrationSupported(
			Enum.UserInputType.Gamepad1,
			Enum.VibrationMotor.Large
		)
	end
	
	-- ===== LOOP DE VIBRAÇÃO =====
	task.spawn(function()
		while true do
			task.wait(0.05)
	
			if enabled and holding and canVibrate() then
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					1
				)
			else
				HapticService:SetMotor(
					Enum.UserInputType.Gamepad1,
					Enum.VibrationMotor.Large,
					0
				)
			end
		end
	end)
	
	-- ===== INPUT LS / L3 =====
	UserInputService.InputBegan:Connect(function(input, gp)
		if gp then return end
		if not enabled then return end
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		-- LS (Xbox) / L3 (PlayStation)
		if input.KeyCode == Enum.KeyCode.ButtonL3 then
			holding = true
		end
	end)
	
	UserInputService.InputEnded:Connect(function(input)
		if input.UserInputType ~= Enum.UserInputType.Gamepad1 then return end
	
		if input.KeyCode == Enum.KeyCode.ButtonL3 then
			holding = false
		end
	end)
	
end;
task.spawn(C_e8);
-- Workspace.Gamepad Hub.Hub.Frame.TextButton.LocalScript
local function C_f7()
local script = G2L["f7"];
	local button = script.Parent
	
	-- Sobe até achar a ScreenGui Gamepad Hub
	local gamepadHub = button:FindFirstAncestor("Gamepad Hub")
	if not gamepadHub then
		warn("Gamepad Hub não encontrado")
		return
	end
	
	-- Pega o Hub
	local hub = gamepadHub:FindFirstChild("Hub", true)
	if not hub then
		warn("Hub não encontrado")
		return
	end
	
	-- Pega o Close (Frame)
	local closeFrame = hub:FindFirstChild("Close", true)
	if not closeFrame then
		warn("Close não encontrado")
		return
	end
	
	button.MouseButton1Click:Connect(function()
		closeFrame.Visible = true
	end)
	
end;
task.spawn(C_f7);
-- Workspace.Gamepad Hub.Hub.Frame.Close.TextButton.LocalScript
local function C_fd()
local script = G2L["fd"];
	-- LocalScript dentro do botão
	
	local button = script.Parent
	
	local player = game.Players.LocalPlayer
	local playerGui = player:WaitForChild("PlayerGui")
	
	button.Activated:Connect(function()
		local screenGui = playerGui:FindFirstChild("Gamepad Hub")
		if screenGui then
			screenGui:Destroy()
		end
	end)
	
end;
task.spawn(C_fd);
-- Workspace.Gamepad Hub.Hub.Frame.Close.TextButton.LocalScript
local function C_100()
local script = G2L["100"];
	local button = script.Parent
	
	-- sobe a hierarquia até achar o Gamepad Hub
	local gamepadHub = button:FindFirstAncestor("Gamepad Hub")
	if not gamepadHub then return end
	
	local hub = gamepadHub:FindFirstChild("Hub", true)
	if not hub then return end
	
	local closeFrame = hub:FindFirstChild("Close", true)
	if not closeFrame then return end
	
	button.MouseButton1Click:Connect(function()
		closeFrame.Visible = false
	end)
	
end;
task.spawn(C_100);

return G2L["1"], require;
