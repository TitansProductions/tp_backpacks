# TP Backpacks    
We provide you a very interesting backpacks script to be used for your players, the script is based on TP Containers and its purpose is to increase the roleplay and allow players having extra capacity weight for carrying products such as food, consumables, tools or even weapons. 

## Development API Exports (CLIENT SIDE ONLY)

- Returns a boolean (true / false) if the player data has loaded related to this script (such as loading all backpack data on login).
```lua
exports.tp_backpacks:Loaded() -- cl
```

- Returns a boolean (true / false) if the player has a backpack attached (equipped) or not.
```lua
exports.tp_containers:HasBackpackAttached()
```

- The specified export @UnequipBackpack is used to unequip an attached (equipped) backpack.
```lua
exports.tp_containers:UnequipBackpack()
```
