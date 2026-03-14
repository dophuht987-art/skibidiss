local Key_He_Thong = "Ghostz_Cute_1"
local File_Luu = "Ghostz_Key_Data.json"

local function DaNhapKeyChua()
    if isfile(File_Luu) then
        local status, data = pcall(function() 
            return game:GetService("HttpService"):JSONDecode(readfile(File_Luu)) 
        end)
        if status and os.time() - data.Time < 86400 then 
            return true 
        end
    end
    return false
end

local function ChayScriptChinh()
    local success, err = pcall(function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/dophuht987-art/skibidiss/refs/heads/main/script.lua", true))()
    end)
end

local function HienMenuKey()
    local CoreGui = game:GetService("CoreGui")
    if CoreGui:FindFirstChild("Ghostz_KeyUI") then CoreGui["Ghostz_KeyUI"]:Destroy() end
    
    local SG = Instance.new("ScreenGui", CoreGui)
    SG.Name = "Ghostz_KeyUI"
    
    local Main = Instance.new("Frame", SG)
    Main.Size = UDim2.new(0, 320, 0, 180)
    Main.Position = UDim2.new(0.5, -160, 0.4, -90)
    Main.BackgroundColor3 = Color3.fromRGB(15, 15, 25)
    local Corner = Instance.new("UICorner", Main)
    Corner.CornerRadius = UDim.new(0, 15)
    
    local Stroke = Instance.new("UIStroke", Main)
    Stroke.Thickness = 2
    Stroke.Color = Color3.fromRGB(0, 150, 255)
    
    local Title = Instance.new("TextLabel", Main)
    Title.Size = UDim2.new(1, 0, 0, 50)
    Title.Text = "GHOSTZ HUB - KEY SYSTEM"
    Title.TextColor3 = Color3.fromRGB(0, 200, 255)
    Title.Font = Enum.Font.GothamBold
    Title.TextSize = 16
    Title.BackgroundTransparency = 1
    
    local Input = Instance.new("TextBox", Main)
    Input.Size = UDim2.new(0, 260, 0, 45)
    Input.Position = UDim2.new(0.5, -130, 0.45, -10)
    Input.PlaceholderText = "Enter Key..."
    Input.Text = ""
    Input.BackgroundColor3 = Color3.fromRGB(30, 30, 45)
    Input.TextColor3 = Color3.fromRGB(255, 255, 255)
    Instance.new("UICorner", Input).CornerRadius = UDim.new(0, 10)
    
    local Submit = Instance.new("TextButton", Main)
    Submit.Size = UDim2.new(0, 140, 0, 40)
    Submit.Position = UDim2.new(0.5, -70, 0.8, -5)
    Submit.Text = "SUBMIT"
    Submit.BackgroundColor3 = Color3.fromRGB(0, 100, 255)
    Submit.TextColor3 = Color3.fromRGB(255, 255, 255)
    Submit.Font = Enum.Font.GothamBold
    Instance.new("UICorner", Submit).CornerRadius = UDim.new(0, 10)

    Submit.MouseButton1Click:Connect(function()
        if Input.Text == Key_He_Thong then
            writefile(File_Luu, game:GetService("HttpService"):JSONEncode({Time = os.time()}))
            Submit.Text = "LOADING..."
            task.wait(1)
            SG:Destroy()
            ChayScriptChinh()
        else
            Input.Text = ""
            Input.PlaceholderText = "Invalid Key!"
        end
    end)
end

if DaNhapKeyChua() then
    ChayScriptChinh()
else
    HienMenuKey()
end
