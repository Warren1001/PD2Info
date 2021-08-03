# Season 3 Issues

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

## **Cannot press Create Game/Join Game/any button in the Realm menu**
###### You alt-tabbed while the Settings menu ingame was open.
- Delete `UI.ini` from your `ProjectD2` folder and restart your launcher.

# **For PlugY or Singleplayer players:**

## You get ANY error upon creating a new character or loading a pre-existing character
- There is something in your shared stash or on your character that needs to be dropped before it is functional.
  - You can either take the easy route and delete the shared stash file (.sss) or make a new character OR you can install S2 to load your saves and go through items that need to be dropped.
    - You can install S2 [here](https://www.mediafire.com/file/xrby5sogoop5ps2/ProjectD2.Season.2.zip/file).
      - `For anyone who didn't prepare Single Player characters for season 3 in time, here is a zip file with instructions inside. FOLLOW THEM CAREFULLY.
(Doesn't include plugy support to clean that stash yet, will be added)` - sajb
    - Items that need to be dropped: Anything with Enhanced Damage %, + to Maximum Damage per Level, maps, and Horadrim Scarabs.
      - This includes sets that give any of these modifiers as partial or full set bonus. Whistan's Guard and Angelic Sickle are two examples. Check the wiki for all sets with partial or full bonuses with Enhanced Damage %.

## **The PlugY Uberquest is causing an issue for some people (context unknown)**
- Go to your `PlugY.ini` (Configuration file) in your PD2 folder and set `ActiveUberQuest` to `0`.


