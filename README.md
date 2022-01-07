# Ore-igin_pack
this pack ports Origins Mod to Vanilla Minecraft, No Forge, No Fabric

## Installing
download either the Ore-igin_pack.zip and the Ore-igin_resource_pack.zip or just download Oreigins_pack.zip
which already includes the Datapack and Resource pack.
Put the Datapack into the datapacks folder in your minecraft save 
and then put the resource pack into your resource pack folder 
or in your save folder (same folder as level.dat and stuff) and rename it to Resources.zip

if you are trying to get the Ore-igins pack to work on a server, you can follow the same steps
but you might need to enable the datapack using the `/datapack enable` command,
using the `/datapack list` command, you can see if the datapack is Red or Green,
if its green, then it should be working, if its red, just run `datapack enable "file/Ore-igin Pack"`

the resource pack needs to be installed differently, due to how servers work
you can open your Server.properties text file and changes these settings
```
require-resource-pack=true
resource-pack=https://github.com/Televisioncomputer/Ore-igin_pack/blob/main/Ore-igin_resource_pack.zip?raw=true
```
and now the resource pack should automatically download when a player joins the server



If you have any issues with the pack you can report them in the issues tab = )
