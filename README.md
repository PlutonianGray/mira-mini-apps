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

1. Open the Mira app and go to **Apps**\.
2. Choose **Create an app**\.
3. Select **Upload/Paste** and upload the downloaded `.html` file\. You can also paste the complete raw HTML if you prefer\.
4. Select **Check code**\.
5. Add and install the app, then open it on the glasses\.

For an update to an app you already installed, long\-press its app card and choose **Edit App**, then upload the newer HTML file, save it, update it, and reopen the app\.

## Current Apps

### Lunar Descent

A retro moon\-landing game designed for the Mira glasses display and input system\.

Features:

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

Features:

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

Features:

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

Features:

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

Features:

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

Features:

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

### ZiggyBalance

A book\-balancing game for Mira glasses inspired by the classic challenge of walking with a book on your head\. Tilt your head gently to keep a virtual hardcover book from sliding off, with a phone companion for game settings and live statistics\.

Features:

- Glasses\-friendly 640×480 grayscale game display with an animated book, stylized head, and top\-view balance indicator
- Head pitch and roll control for forward/backward, left/right, and diagonal book movement
- Stable head\-position calibration before each challenge
- Simulated sliding physics with friction, inertia, recoverable near\-falls, and book\-drop animations
- Seated, Standing, and Walking practice modes
- Easy, Normal, and Hard difficulty levels
- Selectable 30\-second, 1\-minute, and 3\-minute sessions
- Walking mode with a 1\.5× score multiplier and extra tolerance for natural head movement
- Score, book\-drop count, balanced\-time percentage, and longest uninterrupted streak
- Left/right and forward/back steadiness scores based on virtual\-book slippage and sliding speed in the latest scoring revision
- Automatic replacement of the book after a drop, without restarting the session
- Phone companion for starting, pausing, resuming, restarting, recalibrating, selecting settings, and checking game statistics
- Optional left/right sensor\-direction inversion and diagnostic readouts
- Software workaround for a repeatable discontinuity in Mira’s reported roll angle

Glasses controls:

- Hold your head comfortably level during calibration
- Gently tilt or correct your head position to keep the virtual book balanced
- On the setup screen, swipe to select the practice mode, difficulty, session length, Start, or Recalibrate
- Tap to change the selected setup option or begin the challenge
- Tap during a session to pause
- Tap while paused to resume after a countdown
- Tap after the results screen to return to calibration for another challenge

### Ziggy Calendar

A read\-only iCloud Calendar app for Mira glasses, with agenda, week, month, day, event\-detail, and long\-note views designed for the 640×480 display\.

Features:

- Live read\-only iCloud Calendar access through CalDAV
- NEXT, TODAY, TOMORROW, UPCOMING, WEEK, and MONTH views
- Day\-by\-day drill\-down from week and month views
- Weekly planner\-style timeline with appointments positioned by time of day
- Month view with selectable weeks and exact dates, including visible month transitions
- Event details including title, date, start/end time, all\-day status, calendar, location, and notes when available
- Multi\-page display for long event notes
- Support for recurring events, exclusions, modified recurring instances, month\-end recurrence behavior, and recurrence limits
- Stable event selection across companion refreshes
- Phone companion for iCloud connection, refresh, setup, status, and diagnostics
- Read\-only security model: live calendar writes and scheduling side effects are disabled
- Apple app\-specific password is kept only in transient phone memory for the active session and is not sent to the glasses or stored by Ziggy Calendar

Glasses controls:

- Swipe to move through events, dates, weeks, months, or note pages
- Tap to open or select
- Hold to go back one level
- Tap an event to open its details

iCloud setup:

- Ziggy Calendar uses an Apple **app\-specific password**, not the normal Apple Account password
- App\-specific passwords can be generated at [account\.apple\.com](https://account.apple.com/) under **Sign\-In and Security → App\-Specific Passwords**
- The app\-specific password normally only needs to be generated once and may be reused until revoked or otherwise invalidated by Apple
- Ziggy Calendar currently does not persist the password, so the same app\-specific password must be entered again when starting a new session

Possible future enhancements:

- Persistent sign\-in using a Mira\-supported secure credential store or Apple account\-authorization flow, if such support becomes available
- Optional calendar write features such as creating, editing, or deleting events, with explicit confirmation and appropriate safeguards
- Voice and natural\-language calendar navigation, queries, or actions using supported Mira services

These are possible future improvements and are not features of the current read\-only release\.

### Ziggy I, II, and III

A combined Mira text\-adventure app containing Ziggy I, Ziggy II, and Ziggy III, with the full adventure interpreter and story state maintained on the phone and a glasses\-optimized reading, paging, dictation, and command interface\.

Features:

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

All apps currently listed in this README have been tested on physical Mira glasses and confirmed working with the Mira glasses and companion\-app software current at the time of testing\.

- **Lunar Descent** — confirmed working on physical Mira glasses\.
- **Fleet Grid** — confirmed working on physical Mira glasses\.
- **Minesweeper** — confirmed working on physical Mira glasses\.
- **Sudoku** — confirmed working on physical Mira glasses\.
- **SoliMira** — confirmed working on physical Mira glasses\.
- **Alpine Ziggy 1** — confirmed working on physical Mira glasses\.
- **ZiggyBalance** — confirmed working on physical Mira glasses in November 2026 with a game\-side workaround for the repeatable 180° discontinuity observed in reported roll readings\. The workaround is contained within the app\.
- **Ziggy Calendar** — confirmed working on physical Mira glasses, including live iCloud calendar loading, recurrence handling, NEXT/TODAY/TOMORROW/UPCOMING views, WEEK and MONTH navigation, event details, and multi\-page notes\.
- **Ziggy I, II, and III** — confirmed working on physical Mira glasses\.

Future Mira firmware, app, SDK, or runtime changes may require an app to be updated or rebuilt\.

## Development

These apps are produced by Kevin Tieman, created by ChatGPT, and verified by Grok\. Several earlier apps were subsequently migrated from Mira’s retired JavaScript runtime to Rust/WebAssembly for the current Mira SDK, while ZiggyBalance was developed directly for Rust/WebAssembly\. Ziggy Calendar was developed as a Rust/WebAssembly glasses app with an HTML/CSS/JavaScript phone companion and live read\-only iCloud CalDAV integration\.

ChatGPT assisted with migration planning, specification, debugging, and review; Grok was used for Rust compilation, WASM packaging, validation, and additional review\. The apps were reviewed against the public Mira mini\-app / WASM API and tested on physical Mira glasses\.

They are independent community projects and are not official Mira software\.
