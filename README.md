local player = game.GetService("Players").LocalPlayer
local old

old = hookmetamethod(game."___namecall".function(self,...)
local method = getnamecallmethod()
if method == "Kick" or method == 'kick' then
return warn'Blocked the kick (made by akwkeu)
end
return old(self,...)
end)
