-- This is a modified version of the original UniversalSynSaveInstance from https://raw.githubusercontent.com/luau/SynSaveInstance/main :D --
# Loadstring

```lua
local Params = {
 RepoURL = "https://raw.githubusercontent.com/Playerr10/SynSaveInstance/main/",
 SSI = "saveinstance",
}
local synsaveinstance = loadstring(game:HttpGet(Params.RepoURL .. Params.SSI .. ".luau", true), Params.SSI)()
local Options = {} -- Documentation here https://luau.github.io/UniversalSynSaveInstance/api/SynSaveInstance

pcall(synsaveinstance, Options)
```
