# Resource Pack Credits datapack

This Minecraft datapack was created as a simple way give credit to the authors of various resource packs distributed in a server resource pack, via an advancement page. <br> It should be compatible with all versions of Minecraft that support custom advancements in datapacks, though it has been tested and found to work on versions 1.16 and 1.17.

It is compliant with Minecraft Datapack conventions. That is, this data pack in its unmodified form is compatible with any datapacks and resource packs, and contains a set of advancements containing the author and title. If you do not want these advancements, simply delete the 'global' and 'resourcepackcredits' namespace folders.

<br>
<h2>Instructions</h2>
To add a resourcepack to the advancements page, create a new folder with the resource pack's name. This is your namespace. Within that folder, create another called advancements. Within the advancements folder, create two json files, one with the name of the author or group that created it, and the other with the name of the resource pack. The content inside should be the same as the files found in the 'templates/advancements' folder, with content replacing the text enclosed by '< >' respectively. Descriptions are optional, and you can omit it by removing the text between the double quotes.

If you want to add multiple resource pack listings, and they were made by one person or group, you can simplify the process by following the steps above, but with the following two modifications:
1. Name the namespace folder the same as the name of the person or group who made the resource packs.
2. Create one json file per resource pack, each following the template file the same way as described above.

<h4>Be sure to remove the template folder from the version of this datapack you put in-game, or the pack may not load.</h4>
Finally, the pack format in 'pack.mcmeta' is set to '7'. If you do not want earlier versions of Minecraft to complain, just change that value to correspond with the correct version.
<br><br><hr>

iijj22gg claims all rights to this datapack, except those revoked by the "Creative Commons Zero v1.0 Universal" license as described in the LICENSE file. <br> Meaning, feedback and suggestions are welcome.
