# Dodge-The-Teapots
A remake of Clockwork's "Classic Dodge the Teapots of Doom." This will be an obby in my upcoming game "Teapot Tycoon Remastered"
 
 ## How to Install
 1. Download the repository and extract the zip file
 2. Scripts are in their respective types: 
 a. server contains a script that is executed on the server
 b. client contains a local script
 3. Insert *ObbyModel.rbxm* into the **workspace**
 4. Move the scripts to their respective locations:
 a. Place *playerCollisions.client.lua* under **game.StarterPlayer.StarterPlayerScripts**
 b. Place obby.server.lua under **ServerScriptService**
 

 ## Modifying Obby Attributes
 Update these variables in order to manipulate the obby's teapot generation speed, teapot size, amount of force, and the lifetime of the teapot

 ```lua
 local DEBRIS_COOLDOWN = 2.5 --Teapot is destroyed after 2.5 seconds
 local FORCE_AMOUNT = 45000
 local SPAWN_COOLDOWN = 0.5
 local TEAPOT_SIZE = Vector3.new(12,10,18.69)
 ```

### Missing Components
I did not program the checkpoint since I will program it differently than the original game. 
