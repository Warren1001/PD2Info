# Possible Fixes to Issues Regarding Servers in Project D2

#### It is recommended that you read everything here! There are many useful tips that may prevent you from experiencing these issues in the future incase you have not yet experienced them. It should also be noted that not all of these fixes apply to everyone nor do they have a 100% success rate. Additionally, most of these are workarounds and not legitimate fixes. All of us have to deal with these issues. It is the best we as a community can do until the servers have a more permanent fix. Keep up to date on the `# announcements` channel in the PD2 Discord.

| Issues |
| :-: |
| [Failed to Join Game](https://github.com/Warren1001/PD2Info/blob/main/PD2%20Server%20Fixes.md#failed-to-join-game) |
| [Server Down](https://github.com/Warren1001/PD2Info/blob/main/PD2%20Server%20Fixes.md#server-down--lost-connection-to-battlenet) |
| [Lost Connection to Battle.net](https://github.com/Warren1001/PD2Info/blob/main/PD2%20Server%20Fixes.md#server-down--lost-connection-to-battlenet) |
| [Stuck in Queue](https://github.com/Warren1001/PD2Info/blob/main/PD2%20Server%20Fixes.md#stuck-in-queue) |
| [Realm Down / 6112](https://github.com/Warren1001/PD2Info/blob/main/PD2%20Server%20Fixes.md#realm-down--6112) |
| [Connection Interrupted](https://github.com/Warren1001/PD2Info/blob/main/PD2%20Server%20Fixes.md#connection-interrupted) |
| [Game Frozen / Black Walls](https://github.com/Warren1001/PD2Info/blob/main/PD2%20Server%20Fixes.md#game-frozen--black-walls) |
| [Character Level Lower Than Expected](https://github.com/Warren1001/PD2Info/blob/main/PD2%20Server%20Fixes.md#character-level-lower-than-expected) |

## **Failed to Join Game**
###### This issue happens when the server that your game was in crashed. The realm server still thinks your character is in the game because the game server did not report your character leaving the game since it crashed, so the realm server does not allow your character to join another game.
##### Fixes
- On a rare occasion, creating a new character, joining a game, then going back to your main character frees your character from the void.
- You can also try rejoining the game you were booted from and see if it changes anything.
- 99% of the time, you have to wait until the server that you were in restarts to let your character out of the void. The time it takes for the server to restart is mostly random. For the character to be released from the void, for some it's 5 minutes, for others it's 4 hours. I have yet to see anyone report anything higher than 6 hours, so that is likely the max you have to wait. Most people report 3-4h wait.

## **Server Down / Lost Connection to Battle.net**
###### This happens for a similar reason to the "Failed to Join Game" issue. The minor difference is the realm likely thinks you're logged into the realm twice (in Vanilla, "Server Down" and "Lost Connection to Battle.net" happen when you're logged into the same account twice and both are sitting in the realm menu). Why this happens is still a mystery, but the root cause is a game server crashed, so it is effectively the same as "Failed to Join Game".
###### Note: Despite the message saying so, the server is not actually down. It is a poor server message implemented by Blizzard that does not describe the situations it usually happens in. The servers are down when you see a persistent "Realm Down / 6112" message or "Unable to Connect to Battle.net" message in the main menu.
##### Fixes
- On a slightly more common occasion compared to "Failed to Join Game", creating a new character, joining a game, then going back to your main character frees your character from the void.
- You can also try rejoining the game you were booted from and see if it changes anything.
- Most of the time, you have to wait until the server that you were in restarts to let your character out of the void. The time it takes for the server to restart is mostly random. For the character to be released from the void, for some it's 5 minutes, for others it's 4 hours. I have yet to see anyone report anything higher than 6 hours, so that is likely the max you have to wait. Most people report 3-4h wait.

## **Stuck in Queue**
###### Queues generally only form for broken game servers. As such, you should not wait in any queues.
##### Fixes
- Simply cancel the queue every time it pops up and create another game until it lets you in. Try joining a different server (or leave the GS box empty to let PD2 put you in the least active server) if the server you're trying to join is too full or broken.

## **Realm Down / 6112**
##### Fixes
- Check to see if you are able to press "Create a New Character". If you can, there was simply a small connection issue. Creating a new character then going back to the character screen should fix this issue.
- If you cannot press the button, the realm server is restarting and you will have to wait until it's back up.

## **Connection Interrupted**
##### Fixes
- Sometimes this happens (especially when it is frequently) because a patch was released that you did not get. Close your game and launch from the launcher again. If your launcher says "Coming soon" for the lootfilter section, your launcher is outdated. Update your launcher from the [download page of the PD2 website](https://www.projectdiablo2.com/download).
- This also happens due to a bug with Whirlwind. If you are a Whirlwind Barbarian, right now it is suggested that you avoid Shenk the Overseer and the Chaos Sanctuary. Spinning in these areas will kick you and everyone else in the game. It is unknown if it is simply a state bug and you simply get booted or if it forcibly crashes the server.
- This usually happens when the game server crashes. To avoid rolling back and losing progress, save and quit frequently! Save and quit after every good item, every waypoint, and every quest. Yes, it sucks to have to do this.

## **Game Frozen / Black Walls**
##### Fixes
- There is no fix. The game server you were in crashed. It seems that manually leaving the game will cause the "Failed to Join Game" bug. Wait for the server to forcibly kick you (~5-30 minutes) from the frozen game with "Connection Interrupted" and try joining a new game afterwards. Many have reported that while you may have to wait a while for the game to kick you, it is still significantly faster than leaving and waiting for the "Failed to Join Game" issue to fix itself.
  - If you are playing on Hardcore, you still should not leave. The reason is because if the server is frozen, the monsters aren't moving or attacking so you won't die. The only time you would die is if you died before the server actually froze. If you end up dead after not saving and exiting, you technically died before the server froze and the packets were never sent to your computer in time, so it would already be too late by the time you decide to save and exit when you notice the freeze (as the freeze means the server already will not process you leaving and your character will be in-game anyway. If you died, it was unavoidable, even if it was due to server lag).

## **Character Level Lower Than Expected**
###### This is USUALLY a visual bug. The character selection and realm screens do not update properly.
##### Fixes
- Log out of your Battle.net account and log back in and you should see what your level actually is. You may have still rolled back, but it likely won't be as far as what the screens were originally showing.
