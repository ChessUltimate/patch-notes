# Version 5.5 Patch Notes

## Gameplay
- Added a Play Again button after matches.
- You can now avoid specific players to prevent matching with them in queue.
- If a tournament game is about to start while you are in a match, the current match will now be forfeited.
- Ghosts and Jesters are now revealed on Game Over.
- Changed draw and take back requests to appear at the top of the screen to prevent accidental accepts and reduce spam.
- Added a tournament description.
- The last tournament winner is now displayed in the Play menu.

---

## Tournaments
- Tournament sign ups now open 10 minutes before the start time to improve participation.
- Added a notification for weekly tournament start times.
- Added a message at the top of the screen indicating when you are waiting for a tournament game to start.
- Fixed an unnecessary delay after tournament games end.

---

## UI and Menu
- Menu fixes and improvements.
- Increased the maximum number of characters allowed in the email address field.
- Added ghost indicator count to the in game menu UI.
- Updated ghost move indicators.
- Made ghosts more transparent while invisible.
- Fixed issue where switching back to the default pawn icon was not possible.

---

## Balance and Mechanics Fixes
- Fixed Angel and Bomb interaction issues.
- Fixed multiple Angel related bugs.
- Fixed an issue where Giant and Copy Cat would not show knockout indicators correctly.
- Fixed Giant surviving an explosion when Mage swapped it onto Bomb.
- Fixed a Team Builder issue where Copy Cat and Giant could not be placed if you did not have enough points.
- Fixed Copy Cat partner still considering a frozen host’s position when calculating available moves.

---

## Bug Fixes
- Fixed session tokens not refreshing properly after 30 minutes.
- Fixed spectator desync when a Ghost revealed itself.
- Fixed pawn moving into an invisible Ghost causing a resync.
- Fixed Parasite taking a pawn that upgrades to Queen causing the game to stall until a sanity check.
- Fixed issue where banning the King was possible in Draft Mode.
- Fixed issue where a pawn with an attached Angel near an enemy Ghost could softlock the game.
- Fixed an issue with registering alternative accounts.
- Fixed players being able to drop below Bronze V and appear as unranked.
- Disabled the turn changer in the Jester tutorial to prevent a softlock.

---

## Analytics and Performance
- Added analytics tracking.
- General optimizations and performance improvements.

---

## Cosmetics

### New Bundles
- Bowling Bundle

### New Skins
- Bowling Bomb  
- Bowling Pawn  
- Bowling Bomb (Red Variant)  
- Bowling Bomb (Green Variant)  
- Bowling Bomb (Blue Variant)  
- Tournament Bowling Bomb Skin

---

## Miscellaneous
- Removed expiry time from verification emails.


# Version 5.4 Patch Notes (November 24 2025)

## Gameplay
- Matchmade games now randomize Player 1 and Player 2.
- Added threefold repetition draws.
- Added a Ban button to the bottom-left of character details in Draft Mode to make banning easier.

---

## Balance Changes
- Ninja: Points 25 → 22  
- Bomb: Points 18 → 20

---

## New Cosmetics

### Skin Variants
- Skin variants are now available.

### Bundles
- Cosmic Mage Bundle  
- Dog Pack

### New Skins
- Garden Gnome Mage  
- Cosmic Mage  
- Cosmic Mage (Red Variant)  
- Cosmic Mage (Blue Variant)  
- iwantcheckmage (Cosmic Mage Variant)  
- Pug Bishop  
- St. Bernard Bishop  
- Corgi Bishop  
- Dalmatian Bishop  
- Golden Retriever Bishop  
- German Shepherd Bishop

---

## Miscellaneous
- Added two new gem tiers: 5000 and 10000.

---

## Bug Fixes
- Fixed draw games showing incorrect rank point gains on the Game Over screen.  
- Fixed Draft King not defaulting to the selected skin.  
- Fixed issue with dragging characters in Team Builder.  
- Fixed exploit allowing ranked players to exceed 100 points.  
- Fixed Bomb + Angel halo interaction.  
- Fixed Bomb + Angel vs. Copy Cat bug.  
- Fixed Bomb not knocking out Giant.  
- Fixed Bomb teleporting when Angel attached against Parasite.  
- Fixed Penguin sometimes not freezing when Mage was on the team.  
- Fixed Bomb + Bomb + Angel vs. Giant.  
- Fixed Parasite + Jester issue that prevented moves after the acquired piece was knocked out.  
- Fixed Minion causing Bomb (with Angel attached) to teleport.  
- Fixed Sniper shooting into a target with Angel attached when multiple Angels were on board causing issues.  
- Fixed Mage-swapped characters not being freezable by Penguins.  
- Fixed Draft Lock-In button sometimes not appearing or not clickable.  
- Full timer now gives a warning when below 10 seconds.  
- Fixed issue where switching from the game menu with under 60 seconds remaining hid the turn timer.  
- Fixed crash when opening Messages tab right after a game ended.  
- Fixed multi-move characters (Prince or Checker) subtracting time from the opponent’s timer, allowing it to go negative and break the game.


Version 5.29 - (October 05 2025)

--Balance Change--

-Sniper no longer starts sleeping. (changed due to first turn stalemates)

-Point Changes-

-Angel 15->13

-Sniper 15->17

-Bug Fixes-

-In draft mode the minimum point usage on 3rd pick phase is now 0.

-Parasite/Angel interaction.

-Checker/Bomb causing random knock out victories.

-Prince/Angel interaction.

Version 5.28 - (October 01 2025)

-Added turn timer.

-In draft pick player 2's second pick phase minimum points to use is 40.

-Tournament moved from 1pm EST to 4pm EST Saturday.

-You can now sign up for the tournament 1 minute before it starts instead of 30 minutes.

--Bug Fixes--

-Sludge hot fix.

-Added self healing to the tournament ladder if a game breaks itll restart it within 2 minutes.

--Balance Change--

-Point Changes-

-Angel 20->15

Version 5.27 - (September 29 2025)

-Sludge/Ghost interaction fix.

-Mage/Giant interaction fix.

-Mage/Giant/Parasite interaction fix.

-Giant/Angel interaction fix.

Version 5.26 - (September 27 2025)

-Timer changed to 5:5.

-Sludge goop now spawn on your own team.

-Angel hot fix.

-Bomb hot fix.

-Ghost hot fix.

Version 5.21 - (September 25 2025)

-Match made games are now 10 minutes each time mode.

-Sleep now last 2 turns instead of 3 for clarity purposes.

-Added more descriptions and a visual representation for characters moves.

-Steam prices are always in USD now.

-Added busy toggle to hide game invites.

-Added alternative login method

--Bug Fixes--

-Prince bug when taking back the game only lets you move the Prince.

-Multiple Penguin freeze bugs.

-Bomb/Minion interaction.

-Double ban bug where you were able to ban the same character more than once.

-Fixed bug where after a take back or reconnect a visible ghost would go invisible.

-Fixed timer issues.

--Balance Change--

-Point Changes-

-Turtle 3->4

-CopyCat 3->5

-Knight 5->6

-Bishop 8->9

-Sniper 13->15

-Ninja 30->25

-Angel 40->20

-Sniper now starts sleeping.

-Angel rework.  Angel now spawns a Halo that serves a recall point when the attached character gets knocked out.  The Angel no longer retaliates attacks.

---Version 5.1 - (August 22 2025)---

-Changed time modes for draft pick to be 1 minute per turn until game starts.

-Can now withdraw from the tournament.

--Bug fixes--

-Spectating issues.

-Added a way to rejoin a tournament game if not prompted on login via the tournament ladder.

-Menu fixes.

---Version 5.0 - (August 13 2025)---

-Weekly Tournaments will now be held in game every Saturday.

-Custom rules added to friendly and vs Cpu games.

-Added ally outline.

-Changed character descriptions to be more concise.

-You can now view your standing in the rank ladder.

--Balance--

-Bomb point cost 20->18.

-Devil point cost 16->15.

--Skins--

-Tournament Pawn.

-Tournament Checker.

-Tournament Berserker.

-Tournament Penguin.

-Tournament Sniper.

--Bug Fixes--

-Menu fixes.

---Version 4.92 - (June 28 2025)---

-Added automatic reconnect.

--Bug Fixes--

-Angel/Giant interaction.

-UI fixes.

-Angel/Pawn interaction.

-Freeze/Minion Interaction.

-Fixed bot issues.

---Version 4.9 - (June 11 2025)---

--Battle Pass Update--

-Added free items.

-You now get a 30% exp boost when you buy the battle pass.

-Added icons-

-Crying Cloud Icon.

-Referee Icon.

-Fishing Bear Icon.

-Added Emotes-

-Thinking Emote.

-Angry Emote.

-Added Skins-

-Donut Checker.

-Potion Bomb.

-Bookworm Parasite.

-Grey Mage.

-Pixel Pawn.

-Body Guard Turtle.

-Slime Sludge.

-NecroMancer Devil.

--UI Changes--

-All shop related menus have changed and are easier to navigate and equipped your skins.

--Opimization--

-Ice material changed to improve performance.

--Updated Ranked Skins--

--Bug Fixes--

-Checker bot issue.

-Copy cat bot issue.

-Penguin tutorial.

-Sniper tutorial.

-Bomb/Bomb/Angel interaction.

-Checker/Giant interaction.

-Parasite/Goop interaction.

-Parasite/Angel interaction.

-Minion/Angel interaction.

-Angel/Angel/copy cat interaction.

-Angel/Giant interaction.

-Sniper/Ghost interaction.

---Version 4.89 - (May 18 2025)---

-Ranking calculation change.

-In draft mode the game will auto send draft or make a ban for you if time is running out. (I will tackle the UI glitches next update)

--Bug fixes--

-Mage/Penguin interactions.

-Sniper/Ghost interaction.

-Checker/Goop interaction.

-Parasite/Jester interaction.

-Parasite/Angel/King interaction.

-Penguin/Devil interaction.

-Ghost/Checker interaction.

-Timer issues.

-Fixed Penguin not being able to move after draft pick.

-Environment and tiles were resetting after games.

-Frozen Copy Cat in replay.

-Ninja movement.

SERVER HOT FIXES (May 13 2025)

--Bug Fixes--

-Duplication bug patched.

-Some checkmates weren't recorded if the enemy had a Jester.

-Can now spectate while in queue without potential conflict.

-Adding friend issue.

-Game Chat issue.

---Version 4.88 - (May 06 2025)---

--Balance--

-You can now move through your own ghost!

-Sniper can't shoot their own team anymore.

--Bug Fixes--

-Random disconnects from the server.

-Jester bug.

-Parasite bug.

-Penguin bugs.

-Mage/Minion interaction.

-Bot can no longer move into check.

-Bot King knock outs are now accounted for.

-Bomb/Angel if angel is attached to bomb and bomb attacks it'll blow up still.

-Sludge shouldn't get knocked to ghost when moving through it. The goop should knock the ghost. (still gets knocked out when moving into a ghost)

-Mage/Penguin interaction.

-Square notation letters didn't get rotated when you are player 2.

---Version 4.87 - (April 25 2025)---

--Bug Report Feature Added--

-You can now send me a replay and description of the replay to help squash those bugs.

--UPDATED TRANSLATIONS--

-The language translations should be more accurate now.

--Bug Fixes--

-Copy Cat bug.

-Sniper bullet visual bug.

-King little pawns visual bug.

-Angel/Angel interaction.

-Giant world go through ground at high unit speed.

-After opening a menu in draft pick phase you couldn't lock in your pick.

-Sludge would cause a resync at high fps and unit speed.

---Version 4.862 - (April 12 2025)---

--Bug Fix--

-Issue with messages writing lines backwards numbers and symbols writing incorrectly.

---Version 4.861 - (April 11 2025)---

--Bug Fixes--

-Penguin/Giant interaction giant was indefinitely frozen.

-Penguin take back wouldn't unfreeze characters if it moved once.

---Version 4.86 - (April 08 2025)---

-Added creator code functionality.  (If you're a content creator and want a code let me know via discord!)

-Added discord button on main menu.

-Added a way to set your default camera view. (Settings -> Visual -> Default View)

--Bug Fixes--

-Menu fixes.

Version 4.852 - (March 31 2025)

--Bug Fixes--

-Visual fixes.

-Menu fixes.

-Resync issue with characters on cooldown.

---Version 4.85 - (March 27 2025)---

--Bug Fixes--

-Visual fixes.

-Menu fixes.

-Added missing translations.

---Version 4.84 - (March 25 2025)---

--Bug Fixes--

-Visual fixes.

-Menu fixes.

---Version 4.83 - (March 18 2025)---

--Visual Update--

--Bug Fixes--

-Game queue bug.

-Camera pivot didn't move to board when accepting game queue/invite and looking at an item preview.

-Menu fixes.

---Version 4.82 - (Feb 19 2025)---

--Balance Change--

-Buffed Giant point cost changed from 5 -> 1.

-Nerfed Pawn point cost changed from 2 -> 3.

-Nerfed Copy Cat point cost changed from 2 -> 3.

-Nerfed Turtle point cost changed from 2 -> 3.

--Bug Fixes--

-Bot games wouldn't reward you if you were in queue.

-Menu fixes.

---Version 4.811 - (Feb 01 2025)---

--Bug Fixes--

-Hotfix replay menu fix.

---Version 4.81 - (Jan 31 2025)---

--Bug Fixes--

-UI fixes.

-Fixed Penguin description.

-Penguin/Checker interaction.

-Visual fixes.

---Version 4.8 - (Jan 31 2025)---

-Penguin nerf.

--Bug Fixes--

-Black Pawn skin fixed.

-Red Checker skin fixed.

-Bot fixes.

-Gameplay fixes.

-UI fixes.

---Version 4.79 - (Jan 10 2025)---

-Changed color of square indicator.

--Bug Fixes--

-Quests progress didn't show properly on game over menu.

-Castling fix.

-Cooldown tracking display fixed.

-Checker forced move display fixed.

-Tornado blinked for one frame.

---Version 4.78 - (Jan 10 2025)---

--Bug Fixes--

-On mobile if you had too many emotes the list of emotes would go off screen in game.

-On mobile in draft pick mode the emote button blocked the lock-in button and i've moved and resized the lock-in button.

-Penguin/Checker interaction.

-Penguin bugs.

-Trying to start a replay from match history didn't work.

-Penguin/Ghost interaction.

---Version 4.77 - (Jan 07 2025)---

-Increased emote resolution for PC.

--Bug Fixes--

-Fixed unable to watch bot replays.

-CopyCat/Penguin interaction.

-Not able to play against certain bot levels.

-Not receiveing battle pass exp for bot games.

-Fixed unlink account.

---Version 4.76 - (Jan 06 2025)---

-Added a tooltip for people who are trying to play ranked for the first time.

-More translations added for supported languages.

--Bug Fixes--

-Minion didn't get the frozen material when frozen.

-Menu fixes.

-Penugin fixes.

---Version 4.75 - (Jan 05 2025)---

-Menu size changes.

--Bug Fixes--

-Penguin fixes.

-Penguin/Sludge sludge went invisible.

-Penguin/Checker interaction.

-Menu fixes.

-Turn indicator fix.

-Disconnect login wouldn't let you log back in.

-Fixed account linking.

---Version 4.74 - (Dec 29 2024)---

-Freeze character rework (Now named Penguin).

-Added more turn indicators.

-Added transaction history.

--Bug Fixes--

-More menu fixes.

-Fixed bug where when making a team in blind game friendly match and clearing board pressing ready will give an error.

-Copy Cat partner wasn't setting color properly.

-Tutorial fixes.

---Version 4.73 - (Dec 18 2024)---

-Updated rank border art.

-Added seasonal ranked rewards.

--Bug Fixes--

-More menu fixes.

---Version 4.721 - (Dec 09 2024)---

--Bug Fixes--

-Turtle fix.

-More menu fixes.

---Version 4.72 - (Dec 08 2024)---

-Everyone gets the the thumbs up emote for free!

-Bot improvements.

-Can only send 3 emotes per turn now.

--Bug Fixes--

-Removed text from emotes.

-Daily bonus wasn't resetting.

-More menu fixes.

---Version 4.711 - (Dec 06 2024)---

-You can now be in Check, Checkmate and Stalemate on the first move.

--Bug Fixes--

-More menu fixes

---Version 4.71 - (Dec 06 2024)---

-Profanity filter.

-Game chat added.

--Bug Fixes--

-Many menu bugs since last update.

---Version 4.7 - (Dec 02 2024)---

-Friendly invites have been improved.

-Menu Updates.

-Minions only show their movement indicator before they are about to move now.

--Bug Fixes--

-Daily bonus issue.

-Mobile version check issue.

-Menu issues.

---Version 4.69 - (Nov 28 2024)---

-Visual update for the Rubber Duck Freeze skin.

--Bug Fixes--

-Ghost wasn't revealing when moving into range of King/Jester.

-Sludge/Goop was broken.

-During draft pick the commit draft button was showing before meeting the minimum point threshold.

---Version 4.681 - (Nov 26 2024) **hot fix**---

--Bug Fixes--

-Game invites weren't working since last update.

---Version 4.68 - (Nov 24 2024)---

-You can now download and watch anyones replay via match history.

-You can now navigate the game while in queue.

-You can now earn battle pass experience and character unlock keys against the bot and connected to the game server.

-You can now earn battle pass experience and character unlock keys in friendly matches.

--Bug Fixes--

-Resolution wasn't updating until game restart.

-Battle pass issue.

---Version 4.67 - (Nov 17 2024)---

--Bug Fixes--

-Sludge/Bomb interaction.

-Coin was flipped backwards for player 2.

---Version 4.663 - (Nov 13 2024)---

--Bug Fixes--

-Replay bugs.

---Version 4.66 - (Nov 12 2024)---

-Languages added.

--Bug Fixes--

-Sniper/Bomb caused a resync.

-Bug when watching an online replay that had a Ghost on the enemy team.

-Angel bug.

-Mage bug.

-Prince lilipad didn't go away when attacking into an Angel.

-draft text blocked by raccoon head on start.

-score keepers wrong on game start.

-spawn piece group issue.

-issue when going into blind invite then going to team maker will have a blank board.

---Version 4.65 - (Nov 2 2024)---

-You can now save and watch replays of games.

-Menu changes.

--Bug Fixes--

-King/Jester/Sludge interaction.

-Tutorial fixes.

---Version 4.64 - (Oct 27 2024)---

-Should work better for worse connections.

--Bug Fixes--

-Mage/Ghost interaction.

-Sludge/Ghost interaction.

-Draft bug when picking and another menu gets opened.

-Checkmate being recorded as a stalemate.

-Maintenance warning showing for only 1 second before connecting.

---Version 4.63 - (Oct 22 2024)---

-Added queue timer and average queue wait time.

-Added scheduled maintenance notification.

-Added 50 move rule where if no character is knocked-out within 50 turns the game is a draw.

-Added draw when no checkmate is available.

--Bug Fixes--

-Bomb issues.

-Copy Cat Partner wasnt getting assigned skin.

-Couldn't properly scroll on friends list while dragging.

-Battle pass unlocks weren't unlocking until game reset.

-Main menu displayed rank wasnt updated properly when coming out of placement matches.

-Score board issues.

-Sniper/Bomb interaction.

-Copy Cat in draft mode.

-Angel issue when reconnecting/take back.

-Copy Cat/Mage interaction.

-Issue when clicking a character that was moving would cause a desync.

-Issue when buying a character from the team maker.

---Version 4.62 - (Oct 16 2024)---

-Added quality setting and should now run better on mobile devices.

--Bug Fixes--

-Issue with Checker pinned Checkmate.

-Stalemate recorded as a Checkmate.

---Version 4.611 - (Oct 15 2024)---

-Account linking is fixed.

---Version 4.61 - (Oct 14 2024)---

--Bug Fixes--

-Parasite bug was introduced while fixing the Devil/Parasite issue and is now fixed.

-Parasite/Copy Cat interaction.

-Parasite/Goop interaction.

-Sludge/Devil interaction.

-Minion/Minion interaction.

-Parasite wasn't getting knocked out to explosion.

-Bomb/Copy Cat interaction.

-When Mage swapped a Giant it wasn't properly knocking out characters beneath the Giant.

---Version 4.6 - (Oct 13 2024)---

--Bug Fixes--

-Angel/Copy Cat interaction.

-Bomb/Angel interactions.

---Version 4.59 - (Oct 11 2024)---

--Bug Fixes--

-Devil/Parasite interaction minions were changing teams when placed.

-Rabi skin for Bishop didn't attack.

-Angel/Goop interaction causing desync.

---Version 4.58 - (Oct 10 2024)---

--Bug Fixes--

-Copy Cat/Parasite interaction.

-Bomb/Parasite interaction Parasite wasn't knocked-out correctly on client.

-Copy Cat/Goop interaction fixed.

-Devil/Ghost revealing ghost on server.

-Checker landing on ghost desync.

-Moving a ghost into a checker soft locked the game.

---Version 4.57 - (Oct 9 2024)---

--Bug Fixes--

-Jester/Parasite interaction.

-King could attack a Goop and the game would continue.

-Issue with the CPU(BOT) not generating a team in certain situations.

-Prince checkmate soft locking the game.

-Angel/Goop interaction.

-Devil/Angel interaction and the Devil is re-enabled for use.

-Giant was crashing unranked(blind pick) games during game start

-Added the ability to see patch notes and known bugs in game.

-Bug where after failing to connect to a game an error would continuously appear.

-Bug where server would fail to terminate an invalid game in unranked games (bad team configuration).
