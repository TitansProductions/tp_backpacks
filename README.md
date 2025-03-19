# TP Backpacks    
We provide you a very interesting backpacks script to be used for your players, the script is based on TP Containers and its purpose is to increase the roleplay and allow players having extra capacity weight for carrying products such as food, consumables, tools or even weapons. 

## Commands

`searchbackpack` - Search a backpack from a nearby player who is unconscious.

`pickupbackpack` - Pickup a backpack from a nearby player who is unconscious.

`dropbackpack` - Place the attached (holding) backpack on the ground.

`/deletebackpacks` - To delete all the placed backpacks on the world permanently from the server (it also unregisters their containers).

**All commands can be modified and changed based on your preferences through the configuration file.**

## Development API Exports (CLIENT SIDE ONLY)

- Returns a boolean (true / false) if the player data has loaded related to this script (such as loading all backpack data on login).
```lua
exports.tp_backpacks:Loaded()
```

- Returns a boolean (true / false) if the player has a backpack attached (equipped) or not.
```lua
exports.tp_containers:HasBackpackAttached()
```

- The specified export @UnequipBackpack is used to unequip an attached (equipped) backpack.
```lua
exports.tp_containers:UnequipBackpack()
```
