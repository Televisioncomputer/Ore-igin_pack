# Ore-igin_pack
this pack ports Origins Mod to Vanilla Minecraft, No Forge, No Fabric

## Installing

### Singleplayer
download Oreigins_pack.zip
It includes the Datapack and Resource pack. Put the Datapack into the datapacks folder inside your minecraft world's folder, and then put the resource pack into your resource pack folder.

### Multiplayer
if you are trying to get the Ore-igins pack to work on a server, you can follow the same steps
but you might need to enable the datapack using the `/datapack enable` command,
using the `/datapack list` command, you can see if the datapack is Red or Green,
if its green, then it should be working, if its red, just run `datapack enable "file/Ore-igin Pack"`

the resource pack needs to be installed differently, due to how servers work,
you can open your Server.properties text file and changes these settings
```
require-resource-pack=true
resource-pack=https://github.com/Televisioncomputer/Ore-igin_pack/blob/main/Ore-igin_resource_pack.zip?raw=true
```
and now the resource pack should automatically download when a player joins the server



## Missing Features
### Elytrian
  - Unable to add more Kinetic Damage
  - you cant put armor on the chestplate slot due to the elytra, but the elytra hads prot 5 on it to mimic a prot 4 chain, I do have a plan for a workaround in the future
### Shulk
  - I have no good and stable way to make the 9 slot storage, so I replaced it with another cool ability "Space Bubble"
### Enderian
  - Unable to increase reach
  - Unable to make them afraid of pumpkins
### Arachnid
  - didnt even add Arachnid, but no one has noticed it yet HAHAHA
### Feline
  - I replaced the Weak arms ability with just mining fatigue, Week Arms was too tedious to do with minecraft commands
