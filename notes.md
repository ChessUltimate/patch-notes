# Patch 5.72

---

## New Features

- Added more Puzzle Maker capabilities
- Added account flares to spice up your profile name
- Added the first Patreon item

---

## Balance

- Bomb value 20 → 15

---

## UI

- Added a Patreon button to the main menu
- Added Brilliant and Blunder icons for puzzles

---

## Stability

- Added more reconnection safeguards, which should help players with weaker connections

---

## Bug Fixes — Puzzles

- Fixed Angel behavior in puzzles
- Fixed Copy Cats in puzzles
- Fixed enemy Jesters in puzzles
- Fixed Pawn promotion in puzzles
- Fixed a first-turn check on load incorrectly showing a character highlight
- Fixed being able to like a puzzle more than once

---

## Bug Fixes — Puzzle Maker

- Fixed a Giant issue in the Puzzle Maker
- Fixed enemy Ghosts not being usable in the Puzzle Maker
- Fixed Ghost not being removed when clearing a sequence
- Clearing a sequence now removes all Freeze and Sleep effects

---

## Bug Fixes — General

- Fixed Fisherman not being able to reach the end of the board (sorry about this one)
- Fixed Fisherman incorrectly flagging an invalid move when pulling through invisible enemy Ghosts
- Fixed ice material not setting its height properly
- Fixed an issue where spawning a Copy Cat from a pot via click-to-move wouldn't allow swapping its skin
- Fixed the wrong settings menu opening while spectating
- Fixed message notifications not showing in the minimized messages panel tab
- Fixed the camera not pointing at the board during a game
- Potential fix for being unable to click squares sometimes
- Potential fix for invalid draft errors

# Patch 5.7

---

## New Features

- Puzzles have been added to the game

---

## Balance

- Ghost nerf — When a non-attacking move enters a Ghost's square, both pieces are now knocked out instead of just the moving piece
- Fisherman buff — Fisherman can now move like a Queen and can pull diagonally
- Bomb nerf — Diagonal movement range reduced by 1

---

## UI

- Updated UI colors

---

## Bug Fixes

- Fixed issue selecting alternative Captain Bear skins
- Fixed Rook displaying a King skin
- Fixed time not expiring in local and bot games
- Fixed 50-move rule not resetting on certain knockouts
- Fixed issue with multiple Angels in local games
- Fixed a bug where playing against a Devil would complete the knockout quest in a single game
- Fixed a bug where a Pawn could still upgrade after capturing a Bomb
- Fixed a bug involving Giant, Bomb, and Angel interactions
- Various menu fixes
- Team Builder now correctly restores your selected tiles and environment when navigating to it

# Patch 5.652 — Hotfix

---

## Bug Fixes

- Fixed camera getting locked after opening messages
- Fixed board shadow rendering issues
- Fixed Giant not remaining frozen when you have a Mage or Fisherman
- Fixed knockout quest tracking incorrectly against Giants
- Fixed tombstones not being placed during draft for Ghosts

---

# Patch 5.65

---

## Cosmetics

- Added **Captain Fisherman** skin with alternate color variants
- Added **Green & White** tile set
- Added **Felt & Yarn** tile set
- Added **Chocolate Bar** tile set
- Added shadows to tiles
- Darkened the Dragon Knight skin to better distinguish it from the standard Knight

---

## Balance

### Fisherman Rework

Fisherman can now move up to 3 squares in all directions.

### Value Changes

- Fisherman: 8 → 12
- Ninja: 22 → 20
- Dragon: 16 → 15

---

## Bug Fixes

### Gameplay

- Fixed a bug where having a Jester with no legal moves and your King under attack would incorrectly declare checkmate
- Fixed Checker not calling check on double moves
- Fixed Fisherman pulling a King or Jester around Ghosts not revealing the Ghosts
- Fixed a bug where swapping with a frozen Giant via Mage or Fisherman would leave the Giant frozen
- Fixed multiple Angels on a Giant not interacting correctly
- Fixed a Bomb with an Angel attacking a Goop incorrectly requiring 2 hits and removing the Angel
- Fixed Minion, Mage, and Giant interaction
- Fixed Angel and Halo interaction
- Fixed the 50-move rule triggering at 25 moves instead of 50; it now also resets correctly when a Pawn or Checker is pushed
- Fixed insufficient material draw rule
- Fixed inaccurate Ghost grave counts
- Fixed Quest 3 not reporting the correct number of knockouts

### Audio & Visual

- Fixed Garden Mage attack not playing its sound effect
- Fixed scaling issues on characters
- Fixed last move indicator not displaying correctly for enemy moves

### Online

- Fixed an issue where joining a full queue from the new player queue could match you into a second game and kill the current one
- Various error message improvements

---

## Misc

- Added password reset for alternate accounts
- Disabled real-money purchase attempts on alternate accounts
- Messages now open faster; on mobile, the input field shifts up with the keyboard on supported devices
- Increased ranked ladder range from 5 to 25

---

# Version 5.62 — Hotfix

---

## Bug Fixes

- Fixed incorrect point values shown in the shop for characters
- Fixed Angel becoming unusable when playing against Fisherman and Ghost
- Fixed interaction issue with Giant, Fisherman, and Devil
- Fixed Fisherman threat detection not calling check when pulling into checkmate
- Fixed Bomb with Angel attached not exploding when attacked
- Fixed issue when Fisherman pulled Bomb into Ghost
- Fixed issue when Fisherman pulled Bomb with Angel into Ghost
- Fixed Giant centering incorrectly after being pulled by Fisherman
- Fixed Minion with Angel not returning properly to halo after reaching end of board
- Fixed Checker not playing sound when landing

---

# Version 5.6

---

## New Characters

Two brand new characters have been added to Chess Ultimate for the first time since launch.

### Dragon (16 Points)
- Moves like a Bishop + Knight
- Alternate colors added
- New skin: Dragon Knight
- New Dragon icon added

### Fisherman (8 Points)
- Can pull enemy characters toward itself
- New skin: Pooh Bear

---

## Balance

### Checker Rework

- Point cost increased: 1 → 2
- Forced attack now only triggers after an initial knockout that turn
- Checker King movement increased: 1 → 8

---

## Cosmetics

- Alternate skins moved to the bottom of the shop menu
- Fixed issues with setting skins
- Fixed Copy Cat now showing other Copy Cats' movement
- All character key costs are now 1

---

## Bug Fixes

### Combat and Abilities

- Fixed multiple Ghost issues
- Fixed Bomb exploding on game initialization
- Fixed Bomb plus Angel plus Mage plus Giant interaction
- Fixed Bomb vs Parasite square not clearing
- Fixed Angel plus Ghost revealing bug
- Rewrote large portions of Angel code
- Fixed Parasite swap while frozen removing ice material
- Fixed frozen pieces not unfreezing after resync or takeback

### Local and Online Play

- Fixed takeback in local games
- Fixed local time reset issues
- Fixed local team banner not closing
- Fixed resync issues
- Added new player queue
- Updated new user tutorials

### Draft and UI

- Dragging a character onto enemy squares during draft now removes it
- Changed board zoom colors
- Changed square hover highlight color
- Fixed glass tile shader
- Fixed danger move indicators showing incorrectly

### System and Social

- Improved translations
- Fixed blocked users appearing incorrectly
- Fixed tournament notifications
- Fixed battle pass 100 gems animation

---

## Economy

- Keys earned from winning matchmaking: 2 → 1
- All character key costs now standardized to 1

---

# Version 5.5

---

## Gameplay

- Added a Play Again button after matches
- You can now avoid specific players to prevent matching with them in queue
- If a tournament game is about to start while you are in a match, the current match will now be forfeited
- Ghosts and Jesters are now revealed on Game Over
- Changed draw and take back requests to appear at the top of the screen to prevent accidental accepts and reduce spam
- Added a tournament description
- The last tournament winner is now displayed in the Play menu

---

## Tournaments

- Tournament sign ups now open 10 minutes before the start time to improve participation
- Added a notification for weekly tournament start times
- Added a message at the top of the screen indicating when you are waiting for a tournament game to start
- Fixed an unnecessary delay after tournament games end

---

## UI

- Menu fixes and improvements
- Increased the maximum number of characters allowed in the email address field
- Added ghost indicator count to the in-game menu UI
- Updated ghost move indicators
- Made ghosts more transparent while invisible
- Fixed issue where switching back to the default pawn icon was not possible

---

## Balance

- Fixed Angel and Bomb interaction issues
- Fixed multiple Angel related bugs
- Fixed an issue where Giant and Copy Cat would not show knockout indicators correctly
- Fixed Giant surviving an explosion when Mage swapped it onto Bomb
- Fixed a Team Builder issue where Copy Cat and Giant could not be placed if you did not have enough points
- Fixed Copy Cat partner still considering a frozen host's position when calculating available moves

---

## Bug Fixes

- Fixed session tokens not refreshing properly after 30 minutes
- Fixed spectator desync when a Ghost revealed itself
- Fixed pawn moving into an invisible Ghost causing a resync
- Fixed Parasite taking a pawn that upgrades to Queen causing the game to stall until a sanity check
- Fixed issue where banning the King was possible in Draft Mode
- Fixed issue where a pawn with an attached Angel near an enemy Ghost could softlock the game
- Fixed an issue with registering alternative accounts
- Fixed players being able to drop below Bronze V and appear as unranked
- Disabled the turn changer in the Jester tutorial to prevent a softlock

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

## Misc

- Added analytics tracking
- General optimizations and performance improvements
- Removed expiry time from verification emails

---

# Version 5.4

---

## Gameplay

- Matchmade games now randomize Player 1 and Player 2
- Added threefold repetition draws
- Added a Ban button to the bottom-left of character details in Draft Mode to make banning easier

---

## Balance

### Point Changes

- Ninja: 25 → 22
- Bomb: 18 → 20

---

## Cosmetics

### New Bundles

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

### Skin Variants

- Skin variants are now available

---

## Misc

- Added two new gem tiers: 5000 and 10000

---

## Bug Fixes

- Fixed draw games showing incorrect rank point gains on the Game Over screen
- Fixed Draft King not defaulting to the selected skin
- Fixed issue with dragging characters in Team Builder
- Fixed exploit allowing ranked players to exceed 100 points
- Fixed Bomb + Angel halo interaction
- Fixed Bomb + Angel vs. Copy Cat bug
- Fixed Bomb not knocking out Giant
- Fixed Bomb teleporting when Angel attached against Parasite
- Fixed Penguin sometimes not freezing when Mage was on the team
- Fixed Bomb + Bomb + Angel vs. Giant
- Fixed Parasite + Jester issue that prevented moves after the acquired piece was knocked out
- Fixed Minion causing Bomb (with Angel attached) to teleport
- Fixed Sniper shooting into a target with Angel attached when multiple Angels were on board causing issues
- Fixed Mage-swapped characters not being freezable by Penguins
- Fixed Draft Lock-In button sometimes not appearing or not clickable
- Full timer now gives a warning when below 10 seconds
- Fixed issue where switching from the game menu with under 60 seconds remaining hid the turn timer
- Fixed crash when opening Messages tab right after a game ended
- Fixed multi-move characters (Prince or Checker) subtracting time from the opponent's timer, allowing it to go negative and break the game

---

# Version 5.29

---

## Balance

### Sniper

- Sniper no longer starts sleeping (changed due to first turn stalemates)

### Point Changes

- Angel: 15 → 13
- Sniper: 15 → 17

---

## Bug Fixes

- In Draft Mode the minimum point usage on 3rd pick phase is now 0
- Fixed Parasite/Angel interaction
- Fixed Checker/Bomb causing random knockout victories
- Fixed Prince/Angel interaction

---

# Version 5.28

---

## Gameplay

- Added turn timer
- In Draft Pick, Player 2's second pick phase minimum points to use is 40
- Tournament moved from 1pm EST to 4pm EST Saturday
- You can now sign up for the tournament 1 minute before it starts instead of 30 minutes

---

## Balance

### Point Changes

- Angel: 20 → 15

---

## Bug Fixes

- Sludge hotfix
- Added self-healing to the tournament ladder — if a game breaks it will restart within 2 minutes

---

# Version 5.27

---

## Bug Fixes

- Fixed Sludge/Ghost interaction
- Fixed Mage/Giant interaction
- Fixed Mage/Giant/Parasite interaction
- Fixed Giant/Angel interaction

---

# Version 5.26

---

## Gameplay

- Timer changed to 5:5
- Sludge goop now spawns on your own team

---

## Bug Fixes

- Angel hotfix
- Bomb hotfix
- Ghost hotfix

---

# Version 5.21

---

## Gameplay

- Matchmade games are now 10 minutes each time mode
- Sleep now lasts 2 turns instead of 3 for clarity purposes
- Added more descriptions and a visual representation for character moves
- Steam prices are always in USD now
- Added busy toggle to hide game invites
- Added alternative login method

---

## Balance

### Point Changes

- Turtle: 3 → 4
- CopyCat: 3 → 5
- Knight: 5 → 6
- Bishop: 8 → 9
- Sniper: 13 → 15
- Ninja: 30 → 25
- Angel: 40 → 20

### Angel Rework

Angel now spawns a Halo that serves as a recall point when the attached character gets knocked out. The Angel no longer retaliates attacks.

### Sniper

- Sniper now starts sleeping

---

## Bug Fixes

- Fixed Prince bug where taking back the game only lets you move the Prince
- Fixed multiple Penguin freeze bugs
- Fixed Bomb/Minion interaction
- Fixed double ban bug where you were able to ban the same character more than once
- Fixed bug where after a takeback or reconnect a visible ghost would go invisible
- Fixed timer issues

---

# Version 5.1

---

## Gameplay

- Changed time modes for Draft Pick to be 1 minute per turn until game starts
- Can now withdraw from the tournament

---

## Bug Fixes

- Fixed spectating issues
- Added a way to rejoin a tournament game if not prompted on login via the tournament ladder
- Menu fixes

---

# Version 5.0

---

## Gameplay

- Weekly Tournaments will now be held in game every Saturday
- Custom rules added to friendly and vs CPU games
- Added ally outline
- Changed character descriptions to be more concise
- You can now view your standing in the rank ladder

---

## Balance

### Point Changes

- Bomb: 20 → 18
- Devil: 16 → 15

---

## Cosmetics

- Tournament Pawn
- Tournament Checker
- Tournament Berserker
- Tournament Penguin
- Tournament Sniper

---

## Bug Fixes

- Menu fixes

---

# Version 4.92

---

## Gameplay

- Added automatic reconnect

---

## Bug Fixes

- Fixed Angel/Giant interaction
- Fixed Angel/Pawn interaction
- Fixed Freeze/Minion interaction
- Fixed bot issues
- UI fixes

---

# Version 4.9

---

## Battle Pass

- Added free items
- You now get a 30% exp boost when you buy the battle pass

### New Icons

- Crying Cloud Icon
- Referee Icon
- Fishing Bear Icon

### New Emotes

- Thinking Emote
- Angry Emote

### New Skins

- Donut Checker
- Potion Bomb
- Bookworm Parasite
- Grey Mage
- Pixel Pawn
- Body Guard Turtle
- Slime Sludge
- NecroMancer Devil

---

## UI

- All shop related menus have changed and are easier to navigate and equip your skins

---

## Optimization

- Ice material changed to improve performance

---

## Ranked

- Updated ranked skins

---

## Bug Fixes

- Fixed Checker bot issue
- Fixed Copy Cat bot issue
- Fixed Penguin tutorial
- Fixed Sniper tutorial
- Fixed Bomb/Bomb/Angel interaction
- Fixed Checker/Giant interaction
- Fixed Parasite/Goop interaction
- Fixed Parasite/Angel interaction
- Fixed Minion/Angel interaction
- Fixed Angel/Angel/Copy Cat interaction
- Fixed Angel/Giant interaction

---

# Version 4.89

---

## Gameplay

- Ranking calculation change
- In Draft Mode the game will auto send draft or make a ban for you if time is running out

---

## Bug Fixes

- Fixed Mage/Penguin interactions
- Fixed Sniper/Ghost interaction
- Fixed Checker/Goop interaction
- Fixed Parasite/Jester interaction
- Fixed Parasite/Angel/King interaction
- Fixed Penguin/Devil interaction
- Fixed Ghost/Checker interaction
- Fixed timer issues
- Fixed Penguin not being able to move after Draft Pick
- Fixed environment and tiles resetting after games
- Fixed frozen Copy Cat in replay
- Fixed Ninja movement

---

# Version 4.89 — Server Hotfix

---

## Bug Fixes

- Patched duplication bug
- Fixed some checkmates not being recorded if the enemy had a Jester
- Fixed ability to spectate while in queue without potential conflict
- Fixed adding friend issue
- Fixed game chat issue

---

# Version 4.88

---

## Balance

- You can now move through your own Ghost
- Sniper can no longer shoot their own team

---

## Bug Fixes

- Fixed random disconnects from the server
- Fixed Jester bug
- Fixed Parasite bug
- Fixed Penguin bugs
- Fixed Mage/Minion interaction
- Bot can no longer move into check
- Bot King knockouts are now accounted for
- Fixed Bomb/Angel — if Angel is attached to Bomb and Bomb attacks, it will still blow up
- Fixed Sludge getting knocked to Ghost when moving through it; the goop should knock the Ghost instead
- Fixed Mage/Penguin interaction
- Fixed square notation letters not rotating when you are Player 2

---

# Version 4.87

---

## Bug Report Feature

- You can now send a replay and description to help report bugs

---

## Translations

- Language translations are now more accurate

---

## Bug Fixes

- Fixed Copy Cat bug
- Fixed Sniper bullet visual bug
- Fixed King little pawns visual bug
- Fixed Angel/Angel interaction
- Fixed Giant going through ground at high unit speed
- Fixed being unable to lock in a pick after opening a menu during Draft Pick phase
- Fixed Sludge causing a resync at high FPS and unit speed

---

# Version 4.862

---

## Bug Fixes

- Fixed issue with messages writing lines backwards; numbers and symbols were writing incorrectly

---

# Version 4.861

---

## Bug Fixes

- Fixed Penguin/Giant interaction where Giant was indefinitely frozen
- Fixed Penguin takeback not unfreezing characters if it had moved once

---

# Version 4.86

---

## Gameplay

- Added creator code functionality — if you're a content creator and want a code, reach out via Discord
- Added Discord button on main menu
- Added a way to set your default camera view (Settings → Visual → Default View)

---

## Bug Fixes

- Menu fixes

---

# Version 4.852

---

## Bug Fixes

- Visual fixes
- Menu fixes
- Fixed resync issue with characters on cooldown

---

# Version 4.85

---

## Bug Fixes

- Visual fixes
- Menu fixes
- Added missing translations

---

# Version 4.84

---

## Bug Fixes

- Visual fixes
- Menu fixes

---

# Version 4.83

---

## Visual Update

- Visual update

---

## Bug Fixes

- Fixed game queue bug
- Fixed camera pivot not moving to board when accepting game queue/invite while looking at an item preview
- Menu fixes

---

# Version 4.82

---

## Balance

### Point Changes

- Giant: 5 → 1 (buff)
- Pawn: 2 → 3 (nerf)
- Copy Cat: 2 → 3 (nerf)
- Turtle: 2 → 3 (nerf)

---

## Bug Fixes

- Fixed bot games not rewarding you if you were in queue
- Menu fixes

---

# Version 4.811

---

## Bug Fixes

- Hotfix replay menu fix

---

# Version 4.81

---

## Bug Fixes

- UI fixes
- Fixed Penguin description
- Fixed Penguin/Checker interaction
- Visual fixes

---

# Version 4.8

---

## Balance

- Penguin nerf

---

## Bug Fixes

- Fixed Black Pawn skin
- Fixed Red Checker skin
- Bot fixes
- Gameplay fixes
- UI fixes

---

# Version 4.79

---

## UI

- Changed color of square indicator

---

## Bug Fixes

- Fixed quests progress not showing properly on game over menu
- Fixed castling
- Fixed cooldown tracking display
- Fixed Checker forced move display
- Fixed Tornado blinking for one frame

---

# Version 4.78

---

## Bug Fixes

- Fixed emote list going off screen on mobile when you had too many emotes
- Fixed emote button blocking the lock-in button on mobile in Draft Pick; moved and resized the lock-in button
- Fixed Penguin/Checker interaction
- Fixed Penguin bugs
- Fixed trying to start a replay from match history not working
- Fixed Penguin/Ghost interaction

---

# Version 4.77

---

## UI

- Increased emote resolution for PC

---

## Bug Fixes

- Fixed being unable to watch bot replays
- Fixed CopyCat/Penguin interaction
- Fixed being unable to play against certain bot levels
- Fixed not receiving battle pass exp for bot games
- Fixed unlink account

---

# Version 4.76

---

## UI

- Added a tooltip for players trying to play ranked for the first time
- Added more translations for supported languages

---

## Bug Fixes

- Fixed Minion not getting the frozen material when frozen
- Fixed Penguin bugs
- Menu fixes

---

# Version 4.75

---

## UI

- Menu size changes

---

## Bug Fixes

- Fixed Penguin bugs
- Fixed Penguin/Sludge — Sludge went invisible
- Fixed Penguin/Checker interaction
- Menu fixes
- Fixed turn indicator
- Fixed disconnect login not letting you log back in
- Fixed account linking

---

# Version 4.74

---

## Gameplay

- Freeze character rework (now named Penguin)
- Added more turn indicators
- Added transaction history

---

## Bug Fixes

- Menu fixes
- Fixed bug where clearing the board and pressing ready in a blind friendly match would give an error
- Fixed Copy Cat partner not setting color properly
- Tutorial fixes

---

# Version 4.73

---

## UI

- Updated rank border art
- Added seasonal ranked rewards

---

## Bug Fixes

- Menu fixes

---

# Version 4.721

---

## Bug Fixes

- Fixed Turtle bug
- Menu fixes

---

# Version 4.72

---

## Gameplay

- Everyone gets the thumbs up emote for free
- Bot improvements
- Can only send 3 emotes per turn now

---

## Bug Fixes

- Removed text from emotes
- Fixed daily bonus not resetting
- Menu fixes

---

# Version 4.711

---

## Gameplay

- You can now be in Check, Checkmate, and Stalemate on the first move

---

## Bug Fixes

- Menu fixes

---

# Version 4.71

---

## Gameplay

- Added profanity filter
- Added game chat

---

## Bug Fixes

- Many menu bugs since last update

---

# Version 4.7

---

## Gameplay

- Friendly invites have been improved
- Minions now only show their movement indicator before they are about to move

---

## UI

- Menu updates

---

## Bug Fixes

- Fixed daily bonus issue
- Fixed mobile version check issue
- Menu fixes

---

# Version 4.69

---

## UI

- Visual update for the Rubber Duck Freeze skin

---

## Bug Fixes

- Fixed Ghost not revealing when moving into range of King/Jester
- Fixed Sludge/Goop being broken
- Fixed the commit draft button showing during Draft Pick before meeting the minimum point threshold

---

# Version 4.681 — Hotfix

---

## Bug Fixes

- Fixed game invites not working since last update

---

# Version 4.68

---

## Gameplay

- You can now download and watch anyone's replay via match history
- You can now navigate the game while in queue
- You can now earn battle pass experience and character unlock keys against the bot while connected to the game server
- You can now earn battle pass experience and character unlock keys in friendly matches

---

## Bug Fixes

- Fixed resolution not updating until game restart
- Fixed battle pass issue

---

# Version 4.67

---

## Bug Fixes

- Fixed Sludge/Bomb interaction
- Fixed coin being flipped backwards for Player 2

---

# Version 4.663

---

## Bug Fixes

- Replay bug fixes

---

# Version 4.66

---

## Gameplay

- Languages added

---

## Bug Fixes

- Fixed Sniper/Bomb causing a resync
- Fixed bug when watching an online replay that had a Ghost on the enemy team
- Fixed Angel bug
- Fixed Mage bug
- Fixed Prince lilypad not going away when attacking into an Angel
- Fixed draft text being blocked by raccoon head on start
- Fixed score keepers being wrong on game start
- Fixed spawn piece group issue
- Fixed issue when going into blind invite then going to Team Maker resulting in a blank board

---

# Version 4.65

---

## Gameplay

- You can now save and watch replays of games
- Menu changes

---

## Bug Fixes

- Fixed King/Jester/Sludge interaction
- Tutorial fixes

---

# Version 4.64

---

## Gameplay

- Improved performance for worse connections

---

## Bug Fixes

- Fixed Mage/Ghost interaction
- Fixed Sludge/Ghost interaction
- Fixed Draft bug when picking and another menu gets opened
- Fixed checkmate being recorded as a stalemate
- Fixed maintenance warning showing for only 1 second before connecting

---

# Version 4.63

---

## Gameplay

- Added queue timer and average queue wait time
- Added scheduled maintenance notification
- Added 50-move rule — if no character is knocked out within 50 turns the game is a draw
- Added draw when no checkmate is available

---

## Bug Fixes

- Fixed Bomb issues
- Fixed Copy Cat partner not getting assigned skin
- Fixed being unable to properly scroll on friends list while dragging
- Fixed battle pass unlocks not unlocking until game reset
- Fixed main menu displayed rank not updating properly when coming out of placement matches
- Fixed scoreboard issues
- Fixed Sniper/Bomb interaction
- Fixed Copy Cat in Draft Mode
- Fixed Angel issue when reconnecting/taking back
- Fixed Copy Cat/Mage interaction
- Fixed clicking a character that was moving causing a desync
- Fixed issue when buying a character from the Team Maker

---

# Version 4.62

---

## Performance

- Added quality setting; should now run better on mobile devices

---

## Bug Fixes

- Fixed issue with Checker pinned checkmate
- Fixed stalemate being recorded as a checkmate

---

# Version 4.611

---

## Bug Fixes

- Fixed account linking

---

# Version 4.61

---

## Bug Fixes

- Fixed Parasite bug introduced while fixing the Devil/Parasite issue
- Fixed Parasite/Copy Cat interaction
- Fixed Parasite/Goop interaction
- Fixed Sludge/Devil interaction
- Fixed Minion/Minion interaction
- Fixed Parasite not getting knocked out by explosion
- Fixed Bomb/Copy Cat interaction
- Fixed Mage swapping a Giant not properly knocking out characters beneath the Giant

---

# Version 4.6

---

## Bug Fixes

- Fixed Angel/Copy Cat interaction
- Fixed Bomb/Angel interactions

---

# Version 4.59

---

## Bug Fixes

- Fixed Devil/Parasite interaction — minions were changing teams when placed
- Fixed Rabi skin for Bishop not attacking
- Fixed Angel/Goop interaction causing desync

---

# Version 4.58

---

## Bug Fixes

- Fixed Copy Cat/Parasite interaction
- Fixed Bomb/Parasite interaction — Parasite wasn't knocked out correctly on client
- Fixed Copy Cat/Goop interaction
- Fixed Devil/Ghost revealing ghost on server
- Fixed Checker landing on Ghost causing desync
- Fixed moving a Ghost into a Checker softlocking the game

---

# Version 4.57

---

## Gameplay

- Added the ability to see patch notes and known bugs in game

---

## Bug Fixes

- Fixed Jester/Parasite interaction
- Fixed King being able to attack a Goop and the game continuing
- Fixed CPU (bot) not generating a team in certain situations
- Fixed Prince checkmate softlocking the game
- Fixed Angel/Goop interaction
- Fixed Devil/Angel interaction — Devil is re-enabled for use
- Fixed Giant crashing unranked (blind pick) games during game start
- Fixed bug where after failing to connect to a game an error would continuously appear
- Fixed bug where server would fail to terminate an invalid game in unranked games
