# Season 3 Issues

| Issues |
| - |
| [Launcher: "Access is denied"](https://github.com/Warren1001/PD2Info/blob/main/Season_3_Issues.md#after-installing-project-diablo-2-you-get-the-error-access-is-denied) |
| [Launcher: Suddenly closes or disappears](https://github.com/Warren1001/PD2Info/blob/main/Season_3_Issues.md#upon-starting-the-project-diablo-2-launcher-it-does-not-launch-and-the-launchershortcut-suddenly-disappears) |
| [Game: "Wrong game version" or continuous disconnect after short duration](https://github.com/Warren1001/PD2Info/blob/main/Season_3_Issues.md#ingame-you-get-the-error-wrong-game-version-update-the-game-with-the-launcher-or-you-keep-getting-disconnected-after-about-10-seconds-in-a-game) |
| [Launcher: Play button is stuck on Updating](https://github.com/Warren1001/PD2Info/blob/main/Season_3_Issues.md#the-launcher-is-stuck-on-updating) |
| [Launcher: Uninstalling launcher "Access is denied"](https://github.com/Warren1001/PD2Info/blob/main/Season_3_Issues.md#trying-to-uninstall-the-projectd2-launcher-gives-a-access-is-denied-error) |
| [Game: Crashes upon visiting vendor](https://github.com/Warren1001/PD2Info/blob/main/Season_3_Issues.md#game-crashes-upon-visiting-a-vendor) |
| [Game: Crashes upon killing Ventar the Unholy](https://github.com/Warren1001/PD2Info/blob/main/Season_3_Issues.md#game-crashes-upon-killing-ventar-the-unholy-baals-wave-4-boss) |
| [Game: Cannot press Create Game/Join Game/Realm buttons](https://github.com/Warren1001/PD2Info/blob/main/Season_3_Issues.md#cannot-press-create-gamejoin-gameany-button-in-the-realm-menu) |
| [Game: Failed to Join Game](https://github.com/Warren1001/PD2Info/blob/main/Season_3_Issues.md#failed-to-join-game) |
| [PlugY: Generic Bad File or Bad Inventory Data](https://github.com/Warren1001/PD2Info/blob/main/Season_3_Issues.md#plugy-generic-bad-file-or-bad-inventory-data-upon-creating-a-new-character-or-loading-a-pre-existing-character) |
| [PlugY: Uberquest is broken for some people](https://github.com/Warren1001/PD2Info/blob/main/Season_3_Issues.md#plugy-the-plugy-uberquest-is-causing-an-issue-for-some-people-context-and-reasoning-unknown) |

This sheet will be updated constantly with new information.

## **After installing Project Diablo 2, you get the error "Access is denied"**
- Your anti-virus flagged `PD2Launcher.exe`. Usually Avast.
  - Check your anti-virus. Restore the file and then whitelist/make an exclusion for the entire PD2 folder. Then try again.

## **Upon starting the Project Diablo 2 Launcher, it does not launch and the launcher/shortcut suddenly disappears**
- Your anti-virus flagged `PD2Launcher.exe`. Usually Avast.
  - Check your anti-virus. Restore the file and then whitelist/make an exclusion for the entire PD2 folder. Then try again.

## **Ingame you get the error "Wrong game version. Update the game with the launcher" OR You keep getting disconnected after about 10 seconds in a game**
- Restart your launcher and launch PD2 again.
- Your anti-virus flagged `BH.dll` or `ProjectDiablo.dll`. Usually Windows Defender.
  - Check your anti-virus. Restore the file and then whitelist/make an exclusion for the entire PD2 folder. Then try again.
    - You can check your anti-virus by going to clicking your Start Menu button and typing `Windows Security` and opening it, go to `Virus & threat protection`, in the recent items, find the most recent entry that says `Threat quarantined` and you should see an option to allow it through. Then add the entire PD2 folder as an exclusion to Windows Defender.
- If `BH.dll` and `ProjectDiablo.dll` exist in the `ProjectD2` folder and have a file size greater than a few bytes and you are absolutely sure your anti-virus isn't the issue, then:
  - You may be running an outdated launcher. Delete the entire `ProjectD2` folder, redownload the launcher from the [Project Diablo 2 website](https://www.projectdiablo2.com/download), and install PD2 again.
  - You may be installing into a folder that the PD2 launcher can't recognize. This commonly happens with letters that are not in the English alphabet (such is the case for many Asian languages). Try installing to a folder with only English letters (numbers and symbols allowed by Windows are also fine).

## **The launcher is stuck on updating**
- Close your launcher. Launch it again in Admin mode.
- Close your launcher. Check Task Manager and see if there's a ghost Game.exe process and end it. If you don't know how, just restart your PC as this will solve that issue.
- Close your launcher. Your anti-virus flagged `updater.exe`. Check your anti-virus, restore the file, and whitelist/make an exclusion for the entire PD2 folder.

## **Trying to uninstall the ProjectD2 Launcher gives a "Access is denied" error**
###### Your anti-virus flagged something that belongs to PD2 and as such it won't let you delete or interact with the files, so uninstalling fails.
- Go to your anti-virus and restore the file. Whitelist/make an exclusion for the entire PD2 folder in your anti-virus.
- If you cannot restore the file or there is no file to restore, restart your PC. Check your anti-virus again, and whitelist/make an exclusion for the entire PD2 folder, then try installing/re-installing the launcher.

## **Game crashes upon visiting a vendor**
- Kryszard's filter had a crash issue with Thawing Potions. Restart your launcher to update the loot filter.

## **Game crashes upon killing *Ventar the Unholy* (Baal's Wave 4 Boss)**
- One person has reported fixing this issue by installing Diablo 2/PD2 to the same drive that Windows is on.
- One person has reported fixing this issue by using the online installers from Blizzard. They were originally using a Diablo 2 install on a USB from the D3 Collector's Edition (or something like that). Redownload the online installers from the Blizzard site.

## **Cannot press Create Game/Join Game/any button in the Realm menu**
###### You alt-tabbed while the Settings menu ingame was open.
- Delete `UI.ini` from your `ProjectD2` folder and restart your launcher.

## **Failed to Join Game**
- The game server you were in crashed. The realm server still thinks your character is in-game because the game server did not report you leaving the game since it crashed. Therefore, the realm doesn't let your character into another game. The only fix is to wait for the game server to restart and let your character out of the void.

## PlugY: Generic Bad File or Bad Inventory Data upon creating a new character or loading a pre-existing character
- There is something in your shared stash or on your character that needs to be dropped before it is functional.
  - You can either take the easy route and delete the shared stash file (.sss) or make a new character OR you can install S2 to load your saves and go through items that need to be dropped.
    - You can install S2 [here](https://www.mediafire.com/file/xrby5sogoop5ps2/ProjectD2.Season.2.zip/file).
      - ```For anyone who didn't prepare Single Player characters for season 3 in time, here is a zip file with instructions inside. FOLLOW THEM CAREFULLY.``` - sajb
    - Items that need to be dropped: Anything with Enhanced Damage %, + to Maximum Damage per Level, maps, and Horadrim Scarabs.
      - This includes sets that give any of these modifiers as partial or full set bonus. Whistan's Guard and Angelic Sickle are two examples. Check the wiki for all sets with partial or full bonuses with Enhanced Damage %.

## **PlugY: The PlugY Uberquest is causing an issue for some people (context and reasoning unknown)**
- Go to your `PlugY.ini` (Configuration file) in your PD2 folder and set `ActiveUberQuest` to `0`.

