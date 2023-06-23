# Adding Armor mods for Skyrim Outfit System

This guide will showcase how to add armor mods in a conflict-free manner for use with the mod [Skyrim Outfit System](https://www.nexusmods.com/skyrimspecialedition/mods/42162). This guide was originally made by user **firydoom3** on discord and has since been edited by **aljo**.

## Adding the Armor

The first thing to do it find an armor mod you want to add to the list. For this guide we will use the [Akaviri Dragonguard Armor](https://www.nexusmods.com/skyrimspecialedition/mods/85900/) as an example.

**Step 1**: Install the mod off of nexus.

**Step 2**: When installing the mod, prefix the file name with `[NoDelete]`, this will ensure that the mod is not removed when updating the list. Alternatively, you can name the mod something like `[NoDelete] 0.001A Akaviri Dragonguard Armor` in order to keep your additional mods in order after an update, as MO2 will sort them alphabetically.
![](https://raw.githubusercontent.com/Oghma-Infinium/Modding-Guides/main/images/Armor%20for%20Outfit%20System/NoDelete.png?token=GHSAT0AAAAAACC3VGYOGPR65M554VLPGQ7SZEV3QGQ)

**Step 3**: Activate the mod in the left pane of MO2.

**Step 4**: Find and launch the `xEdit64` executable in MO2.
![](https://raw.githubusercontent.com/Oghma-Infinium/Modding-Guides/main/images/xEdit64Executable.png?token=GHSAT0AAAAAACC3VGYOHIQFC53DHNPGIQGWZEV3PQA)

**Step 5**: Once xEdit is opened you should see a menu called `Module Selection`. Right click in the window and press `Select None` to disable all plugins.
![](https://raw.githubusercontent.com/Oghma-Infinium/Modding-Guides/main/images/Armor%20for%20Outfit%20System/ModuleSelectNone.PNG?token=GHSAT0AAAAAACC3VGYPGU6VZPVSJAPXHTZYZEV3PYQ)

**Step 6**: Find the plugin you wish to edit and select it in Module Selection. (Use the `Filter` bar at the top if you can't easily find it).
![](https://raw.githubusercontent.com/Oghma-Infinium/Modding-Guides/main/images/Armor%20for%20Outfit%20System/ModuleSelectionPlugin.PNG?token=GHSAT0AAAAAACC3VGYPCA37A4XAI7ULWRR4ZEV3QBA)

**Step 7**: After selecting the Armor mod's plugin, press `OK` and wait for xEdit to load up all of the mods.

**Step 8**: Once xEdit is finished loading, you will see your armor mod in the left pane, click the **plus** icon on the left side of the plugin name to expand the dropdown.
![](https://raw.githubusercontent.com/Oghma-Infinium/Modding-Guides/main/images/Armor%20for%20Outfit%20System/PluginExpanded.PNG?token=GHSAT0AAAAAACC3VGYPLGJAYARFSVSRB4PIZEV3QPQ)

**Step 9**: Holding `ctrl`, select every record type **except** `ARMOR`, `ARMOR ADDON`, and (if it exists) `TEXTURE SET`.
![](https://raw.githubusercontent.com/Oghma-Infinium/Modding-Guides/main/images/Armor%20for%20Outfit%20System/PluginRecordsSelected.PNG?token=GHSAT0AAAAAACC3VGYOEZVIW4YUWYVIZOI6ZEV3QYQ)

**Step 10**: Right click on the records you selected and click `Remove`. Optionally you can just press your `del` key.
![](https://raw.githubusercontent.com/Oghma-Infinium/Modding-Guides/main/images/Armor%20for%20Outfit%20System/PluginRemoveRecords.PNG?token=GHSAT0AAAAAACC3VGYOWMLDELGPTLTBWEWCZEV3RAA)

**Dummy Checkpoint**: After you remove the records from the plugin, it should look like the image below:
![](https://raw.githubusercontent.com/Oghma-Infinium/Modding-Guides/main/images/Armor%20for%20Outfit%20System/PluginEdited.PNG?token=GHSAT0AAAAAACC3VGYPYGBQKHNDUGZT6VUOZEV3QKQ)

**Step 11**: Press `ctrl+S` to save the plugin.
![](https://raw.githubusercontent.com/Oghma-Infinium/Modding-Guides/main/images/Armor%20for%20Outfit%20System/PluginSaveChanges.PNG?token=GHSAT0AAAAAACC3VGYO53R6MOG36KEZV2U4ZEV3RBA)

**Step 12**: Congrats you are now done and can exit xEdit. You can now use this armor in-game through the [Skyrim Outfit System](https://www.nexusmods.com/skyrimspecialedition/mods/42162) MCM without having to worry about any conflicts or balance issues!