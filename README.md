local userkey = "https://pastebin.com/raw/Xte0zdwN"
local blacklist = "https://pastebin.com/raw/ApxGanef"
local key = game:HttpGet(userkey, true)
local banned game:HttpGet(blacklist, true)

plr = game.Players.LocalPlayer

if string.find(key,_G.Key) then

print("Script loading")
print("Done")
else
plr:kick("WRONG KEY, Contact owner for Reset HWID")
end
