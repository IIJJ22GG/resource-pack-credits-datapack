# Resource Pack Credits datapack

This Minecraft datapack was created as a simple way give credit to the authors of various resource packs distributed in a server resource pack, via an advancement page. <br> It should be compatible with all versions of Minecraft that support custom advancements in datapacks, though it has been tested and found to work on versions 1.16 and 1.17.

It is compliant with Minecraft Datapack conventions. That is, this data pack in its unmodified form is compatible with any datapacks and resource packs, and contains a set of advancements containing the author and title. If you do not want these advancements, simply delete the 'global' and 'resourcepackcredits' namespace folders.

<br>
<h2>Instructions</h2>
To add a resourcepack to the advancements page, follow these steps:
1. Create a new folder inside the 'data' folder with the resource pack's name. This is your namespace.
2. Copy the advancements folder from inside the 'templates' folder, and paste it inside the folder you just created.
3. Open the advancements folder you just pasted, and rename 'author-group_name' to the name of the author or group that created the resourcepack, and 'resource_pack_name' to the name of the resource pack. If you see '.json' at the end of the file name, make sure it remains at the end.
4. Open each of the files you just renamed with any text editor and replace all text enclosed with '< >' like you did in the previous step. Make sure all instances of '< >' are removed. The description field can be left blank by removing all text in-between the double quotes.

If you want to add multiple resource pack listings which were made by the same person or group, you can simplify the process by following the steps above, but with the following two modifications:
1. Name the namespace folder the same as the name of the person or group who made the resource packs.
2. Make a copy of the 'resource_pack_name' file for every resource pack you want to include. They should be renamed and have their contents edited according to the packs they represent.

<h4>Be sure to remove the template folder from the version of this datapack you put in-game, or the pack may not load.</h4>
Finally, the pack format in 'pack.mcmeta' is set to '7'. If you do not want earlier versions of Minecraft to complain, just change that value to correspond with the correct version.
<br><br><hr>

iijj22gg claims all rights to this datapack, except those revoked by the "Creative Commons Zero v1.0 Universal" license as described in the LICENSE file. <br> Meaning, feedback and suggestions are welcome. A program to perform the instructions for the user is coming soon, unless someone does it first, in which case a link may be provided in this file upon request.
