# Mira Mini Apps

Community\-made mini apps, games, utilities, and experiments for Mira smart glasses, built using the public Mira SDK\.

This repository is intended as a simple place to collect and share small Mira applications that can be loaded through the Mira app\-creation interface\.

## Current Apps

### Sudoku

A Sudoku game designed for the Mira glasses display and input system\.

Features include:

- Glasses\-friendly 640×480 interface
- Easy, medium, and hard difficulty levels
- 27 puzzle variations
- Ring, touch\-bar, head\-position, and phone controls
- Conflict highlighting and automatic completion detection
- Check, hint, undo, erase, and new\-puzzle options
- Phone companion with a tappable board and number keypad

Glasses controls:

- Swipe to move among editable cells
- Tap to choose and enter a number
- Long\-press to erase or cancel an entry

### Minesweeper

A classic Minesweeper game adapted for the Mira glasses display and input system\.

Features include:

- Glasses\-friendly 640×480 interface
- 9×9 board with 10 mines
- A guaranteed safe first selection and surrounding area
- Automatic opening of connected empty cells
- Head\-position cell selection with adjustable sensitivity
- Ring or touch\-bar navigation, revealing, and flagging
- Phone controls for starting a new game, recentering, and adjusting head selection

Glasses controls:

- Move your head or swipe to select a cell
- Tap to reveal a cell
- Long\-press to place or remove a flag

### Fleet Grid

A Battleship\-style strategy game designed for the Mira glasses display and input system\.

Features include:

- Glasses\-friendly 640×480 interface
- 10×10 targeting grid
- Automatically placed fleets with standard ship sizes
- A computer\-controlled opposing fleet
- Head\-position aiming with adjustable sensitivity
- Ring or touch\-bar manual aiming
- Shot, hit, and remaining\-fleet status
- Phone controls for starting a new game, recentering, and adjusting head aim

Glasses controls:

- Move your head to aim at a cell
- Tap to fire
- Swipe to switch to manual cell\-by\-cell aiming
- Long\-press to recenter head aiming

## Adding an App to Mira

1. Open the desired HTML file and copy its complete contents\.
2. Select **Build a Mira App** in the Mira app\.
3. Paste the code into the app\-code field\.
4. Select **Check code**, save the app, and run it after connecting the glasses\.

The phone companion may display **Waiting for the glasses…** until the glasses are connected and the app is running\. This is normal\.

## Testing Status

These apps have passed code review and static validation, but they have not yet been tested on physical Mira glasses because I am still waiting for my glasses to arrive\. Hardware\-tested updates will follow when possible\.

## Development

These apps were created with ChatGPT and reviewed against the public Mira mini\-app API\. They are independent community projects and are not official Mira software\.
