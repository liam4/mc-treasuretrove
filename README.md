![# Treasure Trove](http://i1279.photobucket.com/albums/y523/textcraft/Oct%202015%20-%204/af00dc116fb23b2457ab1d7dc21b638f439bc9c794bb7e6433032e7c67b495768abe400d7f91e49a29ee04095130eb48d7299d1757177861a87ba3e24758_zpsxdmhdok4.png)

## Installation

### Install the `loot_tables` directory:
1. [Download](https://github.com/liam4/mc-treasuretrove/archive/master.zip) this repository.
2. [Unzip](https://answers.stanford.edu/solution/how-do-i-zip-and-unzip-files-and-folders-do-i-need-winzip-or-stuffit) the file you downloaded.
3. Rename the new folder to `loot_tables`.
4. [Find](http://gaming.stackexchange.com/a/14703/116361) your world save.
5. Inside of that folder, open up the `data` folder.
6. Move `loot_tables` into `data`.
7. If your world was opened as you were installing:
   * Reload Minecraft's resources (`F3+t` on Windows, `fn+f3+t` on OS X).
   * Else, open up your world.
8. ???
9. Profit!

### Create scoreboard variables:
In order for Treasure Trove to work properly, you will need to initialize some scoreboard variables. To do so, simply run each of these commands (i.e. paste into the chat):

    /scoreboard objectives add sMobKills stat.mobKills

## Documentation
You can find documentation within [`treasuretrove/docs`](treasuretrove/docs).

## Troubleshooting

**Running the commands you gave me shows red text saying I don't have permission to run this command.** This is because your world does not have cheats enabled. To enable them temporarily, simply pause the game (`esc`), click on the big **Open to LAN** button, click on **Allow Cheats**, and finally click on **Start LAN world**. Then run the commands. You can disable cheats and close the LAN server by exiting the world (and then entering).
