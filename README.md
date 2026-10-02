# Mira Mini Apps

Community\-made mini apps, games, utilities, and experiments for Mira smart glasses, built using the public Mira SDK\.

This repository is intended as a simple place to collect and share small Mira applications that can be loaded through the Mira app\-creation interface\.

## Download and Install

Each finished mini app is distributed as a single `.html` file\. The WebAssembly code and phone companion are already contained inside it, so you do not need a separate `.wasm` file\.

To download an app from GitHub:

1. Open the `.html` file for the app you want\.
2. Select **Download raw file** &#40;the download icon on the file page&#41;\. If GitHub opens the raw file instead, use your browser’s share/download option and save the file with its `.html` extension\.
3. Save the file somewhere you can access from the phone running the Mira app, such as the Files app on iPhone or iPad\.

To load it into Mira:

1. Open the **Mira** app and go to **Apps**\.
2. Choose **Create an app**\.
3. Select **Upload/Paste** and upload the downloaded `.html` file\. You can also paste the complete raw HTML if you prefer\.
4. Select **Check code**\.
5. Add and install the app, then open it on the glasses\.

For an update to an app you already installed, long\-press its app card and choose **Edit App**, then upload the newer HTML file, save it, update it, and reopen the app\.

## Current Apps

### Lunar Descent

A retro moon\-landing game designed for the Mira glasses display and input system\.

Features include:

- Glasses\-friendly 640×480 interface
- Multiple missions with varied terrain and landing\-pad placement
- Fuel, altitude, vertical speed, horizontal speed, and attitude displays
- Landing evaluation based on pad position, descent speed, sideways speed, and lander angle
- Scoring for successful landings and mission progression
- Persistent best score retained between app sessions
- Ring / touch\-bar controls
- Phone companion controls for rotation, thrust, starting the next mission, and restarting a run

Glasses controls:

- Swipe one way or the other to rotate the lander
- Tap for a short engine burst
- Hold for sustained thrust
- Release to stop sustained thrust
- Tap to begin, advance after a successful landing, or start a new run after a crash

### Fleet Grid

A Battleship\-style strategy game designed for Mira glasses, with head aiming, ring / touch\-bar controls, and a phone companion\.

Features include:

- 10×10 enemy targeting grid
- Standard fleet sizes of 5, 4, 3, 3, and 2
- Automatically placed player and enemy fleets
- Head\-position aiming for selecting target cells
- Adjustable horizontal and vertical head\-selection range
- Optional X and Y axis inversion
- Swipe\-based cell\-by\-cell backup controls
- Long\-press recentering for head aiming
- Tap\-to\-fire controls
- Hit, miss, sunk\-ship, win, and loss tracking
- Computer opponent with hunt/parity targeting behavior
- Phone companion showing your fleet, incoming hits and misses, remaining ships, shot count, and controls

Glasses controls:

- Look around to select a target cell while head aiming is active
- Tap to fire at the selected cell
- Swipe forward or backward to step through cells manually
- Long\-press to recenter head aiming
- Tap after the game ends to start a new game

### Minesweeper

Classic beginner Minesweeper adapted for Mira glasses, with head\-position selection, ring / touch\-bar controls, and a phone companion\.

Features include:

- 9×9 beginner field with 10 mines
- Safe first reveal: mines are placed only after the first selection, excluding the selected cell and its surrounding 3×3 area
- Automatic flood reveal for empty areas
- Head\-position aiming for selecting cells
- Adjustable horizontal and vertical head\-selection range
- Optional left/right and up/down inversion
- Swipe\-based cell\-by\-cell backup navigation
- Tap\-to\-reveal and hold\-to\-flag controls
- Flag limit matching the 10\-mine field
- Win, loss, mine reveal, and incorrect\-flag display
- Phone companion showing the full board state and providing New Game, Flag, Reveal, Recenter, and head\-control settings

Glasses controls:

- Look around to select a cell while head selection is active
- Tap to reveal the selected cell
- Hold to place or remove a flag
- Swipe forward or backward to move through cells manually
- Tap or hold after a win or loss to start a new game

### Sudoku

A full\-featured Sudoku game for Mira glasses, with three difficulty levels, head\-position selection, ring / touch\-bar controls, and a phone companion\.

Features include:

- 9×9 Sudoku board
- Easy, Medium, and Hard difficulty levels
- 1,000 puzzles per difficulty
- Puzzle tracking to avoid repeats until the difficulty deck has been exhausted
- Immutable clue cells and editable player cells
- Conflict detection for rows, columns, and 3×3 boxes
- Check, Hint, Undo, and Erase functions
- Move and hint counters
- Persistent current\-game progress and played\-puzzle history
- Head\-position selection with adjustable horizontal and vertical range
- Optional X and Y axis inversion
- Phone companion with full board, number keypad, difficulty selection, game actions, and head\-control settings

Glasses controls:

- Look around to select a cell when head selection is enabled
- Tap an editable cell to enter number\-selection mode
- Swipe through 1–9 and Erase, then tap to place the selected value
- Swipe through cells for manual navigation when head selection is off
- Hold to recenter while head selection is enabled
- Hold to erase the selected cell when using manual navigation
- Hold while choosing a number to cancel number entry
- Hold after solving a puzzle to start the next puzzle

### SoliMira

An unofficial community\-made Klondike\-style solitaire game designed for Mira glasses, with ring / touch\-bar controls and a phone companion\.

Features include:

- Standard 52\-card Klondike layout with seven tableau columns
- One\-card stock draws and stock recycling
- Four suit foundations built upward from Ace to King
- Descending, alternating\-color tableau runs
- Multi\-card tableau moves
- King\-only moves to empty tableau columns
- Automatic flipping of newly exposed tableau cards
- Auto\-home for legal foundation moves
- Undo history for recent moves
- Move counter and foundation progress display
- Compact text\-based card layout designed for the 640×480 glasses display
- Optional suit glyph display using ♠ ♥ ♦ ♣, with ASCII S/H/D/C fallback
- Phone companion controls for Previous, Tap/select, Next, Auto home, Cancel, Undo, and New game
- Phone status display for moves, home progress, stock, waste, and current game message

Glasses controls:

- Swipe to move focus between Stock, Waste, Foundations, and Tableau columns
- Tap to draw, select a card/run, or move the selected card/run to the focused destination
- When choosing among multiple face\-up cards in a tableau column, swipe to pick the starting card and tap to select that run
- Hold on Stock to start a new game
- Hold on Waste or Tableau to auto\-home available cards
- Hold on a Foundation to undo
- Hold while a picker or card selection is active to cancel it

### Alpine Ziggy 1

A classic third\-person downhill skiing game for Mira glasses, using head yaw to steer the skier through slalom gates while avoiding trees and rocks\.

Features include:

- Head\-yaw steering with a 20° default range, adjustable from 12–30°
- Optional left/right steering inversion
- Slalom gates worth 100 points each
- Trees and rocks that end the run on collision
- Gradually increasing speed and difficulty
- Narrowing gates as the run progresses
- Persistent best score retained between app restarts
- Sensor\-wait behavior that freezes the run if head tracking becomes unavailable
- Retro 640×480 vector presentation with snow, gates, obstacles, skier, score, speed, and best\-score display
- Phone companion controls for steering range, inversion, recentering, start/restart, status, and built\-in test results

Glasses controls:

- Turn your head left or right to steer
- Tap to start or restart a run
- Long\-press to recenter head steering

### Ziggy I, II, and III

A combined Mira text\-adventure app containing Ziggy I, Ziggy II, and Ziggy III, with the full adventure interpreter and story state maintained on the phone and a glasses\-optimized reading, paging, dictation, and command interface\.

Features include:

- Three adventures in one app with a glasses game chooser
- Full phone transcript and typed\-command entry
- Glasses output wrapped for the 640×480 display with multi\-page navigation
- Tap\-to\-dictate command entry with confirmation before a dictated command is sent
- Quick commands including LOOK, INVENTORY, SCORE, SAVE, RESTORE, UNDO, SAVE SLOT, SWITCH GAME, and CANCEL
- Automatic per\-turn autosave
- Three manual save slots per adventure
- One\-turn Undo
- Parser continuation handling for clarification questions
- Recovery handling if an adventure session cannot be reconstructed cleanly
- Separate progress and saves for Ziggy I, Ziggy II, and Ziggy III
- Phone\-side attribution and license information for the included adventure materials

Glasses controls:

- In the game chooser, swipe to select an adventure and tap to open it
- During play, swipe to move through output pages
- Tap to dictate a command
- Long\-press to open quick commands
- When confirming dictated text, tap to send, swipe to retry, or hold to cancel

## Testing Status

**Lunar Descent, Fleet Grid, Minesweeper, and Sudoku have been tested and verified directly on physical Mira glasses\. SoliMira and Alpine Ziggy 1 have been tested using Mira’s hardware\-backed Glasses Preview while the apps were running on physical Mira glasses\. Ziggy I, II, and III has not yet had a completed hardware\-backed preview or direct optical\-display verification recorded here\.**

- **Lunar Descent** — confirmed working with the Mira glasses and companion\-app software current at the time of testing in **September 2026**
- **Fleet Grid** — confirmed working with the Mira glasses and companion\-app software current at the time of testing in **September 2026**
- **Minesweeper** — confirmed working directly on physical Mira glasses with the Mira glasses and companion\-app software current at the time of testing in **September 2026**
- **Sudoku** — confirmed working directly on physical Mira glasses with the Mira glasses and companion\-app software current at the time of testing in **September 2026**
- **SoliMira** — tested successfully using Mira’s hardware\-backed **Glasses Preview**, with the app running on physical Mira glasses and controlled through the glasses\. Direct optical\-display verification is pending because of a separate glasses display issue\.
- **Alpine Ziggy 1** — confirmed running using Mira’s hardware\-backed **Glasses Preview** with the WASM app executing on physical Mira glasses\. The preview itself refreshed at a visibly reduced frame rate, so smoothness of the direct optical display remains unverified pending repair of the separate glasses display issue\.
- **Ziggy I, II, and III** — included as the combined three\-adventure app\. Final hardware\-backed Glasses Preview and direct optical\-display verification have not yet been recorded\.

Mira’s connected\-device Glasses Preview mirrors the retained vector output of the WASM app running on the glasses\. Its phone\-side refresh rate should not be treated as proof of the direct optical display’s frame rate\.

Future Mira firmware, app, SDK, or runtime changes may require an app to be updated or rebuilt\.

## Development

These apps were created with ChatGPT and reviewed against the public Mira mini\-app / WASM API\. They are independent community projects and are not official Mira software\.
