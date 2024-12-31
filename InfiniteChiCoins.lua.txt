-- Infinite Chi and Coins Script for Ninja Legends (Personal Use Only)
-- WARNING: Use responsibly and only in your game!

local player = game.Players.LocalPlayer
local stats = player:FindFirstChild("leaderstats")  -- Adjust if your game uses a different stats folder

if stats then
    -- Setting infinite Chi and Coins
    stats.Chi.Value = math.huge  -- Infinite Chi
    stats.Coins.Value = math.huge  -- Infinite Coins
    
    print("Your Chi and Coins are now infinite!")
else
    print("Stats not found! Ensure the leaderstats folder exists.")
end
