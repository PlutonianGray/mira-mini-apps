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

## Testing Status

**Lunar Descent and Fleet Grid have been tested and validated on physical Mira glasses\.**

- **Lunar Descent** — confirmed working with the Mira glasses and companion\-app software current at the time of testing in **September 2026**
- **Fleet Grid** — confirmed working with the Mira glasses and companion\-app software current at the time of testing in **September 2026**
- **Minesweeper** — current WASM version included; physical\-glasses validation status has not yet been recorded in this README

Future Mira firmware, app, SDK, or runtime changes may require an app to be updated or rebuilt\.

## Development

These apps were created with ChatGPT and reviewed against the public Mira mini\-app / WASM API\. They are independent community projects and are not official Mira software\.
