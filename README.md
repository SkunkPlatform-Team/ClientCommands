# Client Commands

Client Commands is a Client Side for Roblox Script.
Based from the Basic and 7 Utilities Commands.

![Image](images/clientcommands.png)

**Current Prefix**: '.help'

## How to evaluate with my Client Side Executor?

To Evaluate with your Client Side Executor, Follow the steps:
1. Ensure you have executor client side for localscript.
2. Inject your Roblox Game.
3. Use the Example Usage:
```lua
print()
local success, result = pcall(function() -- This is the PCall to prevent Fallback.
    loadstring(game:HttpGet("https://raw.githubusercontent.com/SkunkPlatform-Team/ClientCommands/refs/heads/main/Main.txt"))() -- Evaluate with loadstring.
end)

if not success then
    warn("Error loading script: " .. result) -- This will show a Fallback Error.
end
```
4. Inject the Roblox Game to read example.
5. Execute your Client Side Executor.

---

That all for this Example Usage!
