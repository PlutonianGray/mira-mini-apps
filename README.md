mira-mini-apps

Community-made mini apps, games, utilities, and experiments for Mira smart glasses using the public Mira SDK.

Current status

> [!IMPORTANT]
> These apps have passed code review and static validation, but they have not yet been tested on physical Mira glasses because I am still waiting for my glasses to arrive. Hardware-tested updates will follow when possible.

Each app is a self-contained HTML file containing both the glasses app and its optional phone companion.

Games

Minesweeper

Classic Minesweeper adapted for Mira’s 640×480 display.

• 9×9 board with 10 mines
• First revealed cell and its surrounding cells are always mine-free
• Automatic opening of connected empty areas
• Direct head-position cell selection with adjustable horizontal and vertical ranges
• Ring/touch-bar navigation when head selection is unavailable or not desired
• Phone companion controls for starting a new game, recentering, sensitivity, and X/Y inversion

Glasses controls

• Head movement: select a cell
• Swipe/scroll: move one cell at a time
• Tap: reveal the selected cell
• Long-press: place or remove a flag
• Tap after winning or losing: start a new game

Mira Sudoku

A full Sudoku game designed for the Mira display, ring/touch bar, head selection, and phone companion.

• Easy, medium, and hard difficulty levels
• Nine transformations per difficulty, for 27 puzzle variations
• Conflict highlighting and incorrect-entry checking
• Automatic solved-puzzle detection
• Hints, undo, erase, and new-puzzle controls
• Optional direct head-position selection with adjustable horizontal and vertical ranges
• Phone companion with a tappable board and number keypad

Glasses controls

• Swipe/scroll: move among editable cells
• Tap: enter number-selection mode
• Swipe/scroll while editing: choose 0–9 (0 erases)
• Tap while editing: place the chosen number
• Long-press while editing: cancel entry
• Long-press while selecting: erase the selected cell

Fleet Grid

A Battleship-style strategy game in which you compete against a computer-controlled fleet.

• 10×10 targeting grid
• Automatically placed fleets using standard ship sizes: 5, 4, 3, 3, and 2
• Direct head aiming with adjustable horizontal and vertical spans
• Manual ring/touch-bar aiming as a fallback
• Computer opponent that continues searching around successful hits
• On-screen shot, hit, and remaining-fleet status
• Phone companion controls for starting a new game, recentering, sensitivity, and X/Y inversion

Glasses controls

• Head movement: aim at an enemy cell
• Tap: fire at the selected cell
• Swipe/scroll: switch to manual aiming and move one cell at a time
• Long-press: recenter and return to head aiming
• Tap after the game ends: start a new game

Adding an app to Mira

1. Open the desired HTML file and copy its entire contents, beginning with <!doctype html> and ending with </html>.
2. In the Mira app, choose Build a Mira App.
3. Paste the complete source into the app-code field.
4. Select Check code and confirm that the glasses section reports Supported — ready to add.
5. Save the app, connect the glasses, and select Run.

The phone companion may display Waiting for the glasses… until the glasses are connected and the app is running. That is expected.

Development note

These mini apps were created with ChatGPT and reviewed against the public Mira mini-app API. They are independent community projects and are not official Mira software.

Repository

github.com/PlutonianGray/mira-mini-apps
