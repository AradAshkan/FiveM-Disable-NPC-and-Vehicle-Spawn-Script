# NoNPC - Disable NPC and Vehicle Spawns in FiveM

## 📜 Overview
The **NoNPC** resource is a simple but effective script for FiveM servers that prevents NPCs and vehicles from spawning in the game world. This ensures a more controlled and optimized multiplayer environment.

## 🚀 Features
- Disables random NPC spawns, including police officers.
- Prevents garbage trucks and boats from spawning.
- Sets vehicle and pedestrian density to **0.0**.
- Clears all NPCs and vehicles in a specified radius around the player.
- Removes vehicle generators within a set area.

## 📂 Installation
### 1️⃣ Download and Extract
- Place the **NoNPC** folder into your **resources/** directory of your FiveM server.

### 2️⃣ Enable the Resource
Add the following line to your **server.cfg** file to ensure the script runs when the server starts:

```ini
ensure NoNPC
```

### 3️⃣ Restart Your Server
Restart your FiveM server to apply the changes.

## ⚙️ Customization
To adjust the NPC and vehicle density instead of completely disabling them, modify the values in `main.lua`:

```lua
SetVehicleDensityMultiplierThisFrame(0.1) -- 10% vehicle density
SetPedDensityMultiplierThisFrame(0.2) -- 20% NPC density
```

## 📌 Notes
- The script runs continuously in a loop to enforce the settings.
- Can be used alongside other mods to fine-tune NPC and vehicle behavior.

## 📜 License
This script is free to use and modify for any FiveM server.

---

For any questions or modifications, feel free to ask!

