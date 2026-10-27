# Patch 5.741

---

## Balance

- Cow value 10 → 5

---

## Performance

- Improved Shop performance on lower-end phones

---

## UI

- Improved character select scaling on phones
- Improved the puzzle screen layout on phones

---

## Bug Fixes

- Fixed 10-minute games sometimes ending in a forfeit before time ran out
- Fixed some endgames being called a stalemate when they weren't (e.g. King + Angel + Bishop vs King + Turtle)
- Fixed the Cow not being able to target Halo and Goop pieces
- Fixed the Cow not targeting Giants correctly
- Fixed the game sometimes starting twice
- Fixed draft board issues in Ranked
- Fixed point values not matching between the draft and the server
- Fixed approved puzzles going back to unapproved
- Fixed not being able to remove Giants from teams
- Fixed the bot's point amount setting not applying
- Fixed bans not showing correctly

# Patch 5.74

---

## New Features

- Added a new character: the Cow (10 points). It targets an enemy and charges 1 square towards it at the start of your turn, knocking out anything in its way, including your own characters
- Added a Cow tutorial
- Added the Toy Cow and Chocolate Cow skins, plus a Strawberry Cow color
- Added queueing for multiple modes at once
- Added Ranked Blind Pick, with its own rating, placements, streak and peak
- Added Unranked Draft Pick
- Added a New Player Queue so new players can choose to only play other new players
- Added a new character select: the pots are replaced by a scrollable card tray in Make a Team, Blind Pick and Draft Pick
- Added drag and drop for placing characters
- Added a Make a Team walkthrough for new players
- Rebuilt the Puzzle Maker as 3 steps: Setup, Record and Publish
- Added a Character Tray to the Puzzle Maker, and a menu on placed pieces to swap team, freeze or put to sleep
- Added hints between moves and wrong-answer lines in the Puzzle Maker
- Added Test Play to try your puzzle before submitting it
- Added a "+ New puzzle" button to the puzzle finder

---

## Balance

- Ranked matches are now always found before unranked ones
- Time controls are now 1 Min Each, 5 Mins Each, 10 Mins Each and 5 Mins + Turn Timer (Local Play also has Unlimited)
- Kings and Jesters can no longer castle out of, through or into check
- Capturing the enemy King now always ends the game, even if your own King is in check
- A move that would knock out both Kings is no longer allowed
- A Parasite that takes a Halo now rides it. When the Angel brings its piece back to that Halo, the piece joins the Parasite's side (Kings and Jesters excepted)
- A Parasite that takes over a piece now also takes over its Angels and Halos
- A Halo caught in its own Bomb's blast is now destroyed
- Unlock keys now require finishing a CPU game and are no longer given for resigning (your first CPU game always gives one)
- Draw offers are limited to one request at a time and once every 3 turns, and accepting takes a second tap
- You won't be matched with the same opponent again straight away

---

## UI

- Removed the Ranked button. Online now opens matchmaking and queues with your last picks
- Added Ranked Stats for Draft Pick and Blind Pick to Match History, and tagged every match with its mode and time control
- Rank borders now show your highest rank from either mode, and King skins unlock from your best rank
- Added a pick/ban order column with a turn timer to Draft Pick, and made the board bigger on PC
- Banned characters are now clearly marked
- Redesigned the puzzle screen, the puzzle finder rows and the Puzzles button
- Added phone layouts for every puzzle screen
- Game chat is now always the first chat tab, and stays open after the game until a player closes it
- Scrolling or pinching over a list no longer zooms the camera

---

## Performance

- Removed the freeze when the CPU makes a move
- Removed the hitch the first time you open character details
- Greatly reduced stutters during matches
- Graphics quality now detects your device properly, so most phones get sharper visuals
- Auto graphics now lowers quality if the game can't hold 45 fps
- Menus now stay sharp on lower graphics settings

---

## Stability

- Improved reconnecting to a game
- Returning to the app now re-syncs your game straight away
- Fixed rare cases where the server's board drifted from what players saw, causing resyncs or rejected moves
- Fixed games stopping without a result
- Fixed a game starting with one side's army missing

---

## Bug Fixes — Puzzles

- Fixed Checkers stopping partway through a capture chain at higher game speeds
- Fixed Copy Cat puzzles rejecting the correct move
- Fixed castling not being accepted as a solution
- Fixed Show Solution skipping a step
- Fixed puzzle pieces and pop-ups carrying over into the next match
- Fixed the camera not zooming back out when no puzzles were left
- Fixed the referee coming back down without his chair
- Fixed the mouse wheel not scrolling the puzzle list over buttons

---

## Bug Fixes — Puzzle Maker

- Fixed Take Back turning a Jester into a King
- Fixed clearing a sequence leaving the board in the wrong state
- Fixed going back to Setup wiping Freeze and Sleep settings

---

## Bug Fixes — Gameplay

- Fixed Angels and Halos ending up in the wrong place after chains with Giants, Mages, Checkers, Minions and castling
- Fixed frozen pieces sometimes losing their freeze
- Fixed Giants not staying frozen, and pieces staying frozen after the Penguin left
- Fixed a Jester running out of moves while its King was attacked counting as stalemate instead of checkmate
- Fixed a move that takes every enemy royal at once being blocked
- Fixed a Prince stolen by a Parasite not counting its double move for check
- Fixed Copy Cats blocking each other after a Freeze, Mage or Fisherman lined them up
- Fixed being able to select a piece while it was being captured
- Fixed games starting with no pieces or ending in stalemate on move 0
- Fixed valid drafts being rejected when a Giant or Copy Cat was placed
- Fixed pieces staying on screen after a Bomb blast or Giant shockwave
- Fixed Mage swap dots, the check indicator and Jester animations giving away hidden Ghosts and the real King
- Fixed Ghosts not being revealed when a King arrives next to them by swap or teleport
- Fixed Take Back undoing only one of a Prince's two moves
- Fixed Checkers ending or keeping the turn wrongly after captures
- Fixed threefold repetition triggering when pieces only differed in freeze or cooldown
- Fixed a swapped or pulled Pawn keeping its two-square first move
- Fixed Angels vanishing along with a Parasite
- Fixed Copy Cat Halos staying behind after the cat was taken
- Fixed a Giant disappearing after crushing an enemy Giant and its Halo
- Fixed a Bomb carrying an Angel disappearing instead of returning to its Halo
- Fixed rare board errors when a hidden Ghost carrying an Angel was hit
- Fixed the capture warning showing on every square
- Fixed tapping a piece sometimes moving it one square
- Fixed a promoted Queen not adding to your score
- Fixed the Ghost counter and gravestones showing the wrong count
- Fixed the Penguin not moving again after a reconnect
- Fixed a stray Minion staying on the board after a reconnect
- Fixed a stolen Jester still showing as a King at the end of the game
- Fixed a frozen or sleeping Giant or Checker being marked as able to block check

---

## Bug Fixes — Matches

- Fixed the tournament draft auto-banning a piece before you could choose
- Fixed tournaments starting a rematch right after a game ended
- Fixed spectators receiving battle pass points
- Fixed losing on time with seconds still on the clock, and the wrong player losing on time
- Fixed being matched or invited into a new game while already in one
- Fixed blocked players being matched with you
- Fixed knock-out quests counting the wrong number of knock-outs
- Fixed "Couldn't find game" showing right as a game ended
- Fixed friendly invites starting a game the other player never saw
- Fixed the draft lock-in button disappearing when short of points (it now shows how many you need)
- Fixed draft picks being wiped by a resync or sent twice
- Fixed the draft auto-ban choosing an already banned piece
- Fixed banned characters not showing on the pick/ban display

---

## Bug Fixes — Vs CPU & Local Play

- Fixed the CPU not moving after a Take Back
- Fixed the CPU freezing instead of playing its last available move
- Fixed the CPU forfeiting games it could still play
- Fixed the CPU ignoring Dragons and Fishermen when planning its moves
- Fixed checkmate not being called when a frozen or sleeping Giant or Checker was your only way out
- Fixed being able to keep playing after giving up
- Fixed Play Again reusing the finished board
- The CPU no longer places its King where it can be taken on the first move
- Fixed time controls in Local and Friendly games
- Fixed a Local Play points setting carrying over into CPU and queue games
- Fixed Local and CPU replays not playing, and online replays going missing or appearing twice

---

## Bug Fixes — Friends, Shop & Quests

- Fixed unblocking showing "That user is not your friend" and moving friends into Blocked
- Fixed Add Friend not creating a pending request
- Fixed a friend's profile showing two Messages buttons
- Fixed bundles charging for items you already own
- Fixed shop icons being equippable without buying them
- Fixed players who owned every character being unable to buy new ones
- Fixed draws and losses completing "win" quests
- Fixed daily quests repeating, login days being skipped and daily gems being granted twice
- Fixed the daily bonus showing "Day -1" or "+0 gems" when the app was left open past midnight
- Fixed claiming a quest before the daily bonus blocking the bonus

---

## Bug Fixes — General

- Fixed the tutorial showing puzzle pop-ups
- Fixed the turn getting stuck on the opponent's side when starting a tutorial right after another
- Fixed clicking a Giant while it was moving sending it back to its old square
- Fixed the Devil's Minions having no shadow after spawning
- Fixed Ghosts being invisible while placing them in Make a Team
- Fixed angry eyebrows and other face effects being hidden by outlines
- Fixed shop and tutorial previews freezing after leaving a tutorial
- Fixed toggle buttons sometimes vanishing and not responding after reopening a menu
