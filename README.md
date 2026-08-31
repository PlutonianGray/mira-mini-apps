# Mira Mini Apps

Community\-made mini apps, games, utilities, and experiments for **Mira smart glasses**, built using the public Mira SDK\.

This repository is intended as a simple place to collect and share small Mira applications that can be loaded through the Mira app\-creation interface\.

## Current Apps

### Sudoku

A Sudoku game designed for the Mira glasses display and input system\.

Features include:

- 3,000 built\-in Sudoku puzzles
- 1,000 Easy puzzles
- 1,000 Medium puzzles
- 1,000 Hard puzzles
- Glasses\-friendly 640×480 interface
- Grid\-based navigation
- Mira touch/ring controls
- Head\-controlled cell selection
- Phone companion controls and settings
- Hint, check, undo, and erase functions
- Self\-contained HTML package

### Minesweeper

A classic Minesweeper\-style game adapted for Mira glasses\.

Features include:

- 9×9 beginner board
- 10 mines
- First\-tap safety for the selected cell and its surrounding cells
- Automatic clearing of empty areas
- Flags
- Win and loss detection
- Touch/ring controls
- Swipe navigation
- Head\-controlled cell selection
- Phone companion controls and head\-pointer settings
- Self\-contained HTML package

### Fleet Grid

A Battleship\-style naval strategy game designed for the Mira glasses display and controls\.

Place your fleet automatically, then search the opposing grid and attempt to sink the enemy fleet before yours is destroyed\.

Features include:

- 10×10 naval strategy grid
- Standard ship sizes: 5, 4, 3, 3, 2
- Automatic fleet placement
- Player and opponent fleets
- Hit, miss, and sunk tracking
- Hunt/target computer opponent
- Win and loss detection
- Mira touch/ring navigation
- Head\-controlled grid selection
- Phone companion controls and head\-pointer settings
- Phone view of your fleet and incoming enemy fire
- Glasses\-friendly interface
- Self\-contained HTML package

## Installation

Each Mira app is provided as a single `.html` file\.

To use an app:

1. Download or copy the desired `.html` file\.
2. Open the Mira app\-creation interface on your iPhone\.
3. Create a new mini app\.
4. Paste or import the HTML source\.
5. Save the app\.
6. Connect your Mira glasses\.
7. Run the app from the Mira app\.

No additional JavaScript libraries, packages, or external files are required unless specifically noted\.

## Controls

Controls may vary by app, but Mira mini apps can use standard glasses inputs such as:

- Tap / click
- Long press
- Swipe up
- Swipe down
- Mira ring controls
- Head movement using the glasses’ IMU sensors

Individual apps include their own control instructions\.

## Hardware Testing

These apps are being developed using Mira’s public SDK\.

Some apps may initially be created and tested in the Mira iPhone app before being tested on physical Mira glasses\.

Because the Mira SDK and hardware ecosystem are still relatively new, behavior may change as Mira updates its firmware, SDK, or iPhone app\.

If you try one of these apps on actual Mira glasses and find a problem, feedback is welcome\.

## About the Code

The apps in this repository are intentionally designed to be:

- Small
- Self\-contained
- Easy to inspect
- Easy to modify
- Easy to share
- Suitable for learning the Mira SDK

Most apps consist of one combined HTML file containing both the Mira glasses code and, when needed, an optional iPhone companion interface\.

## Community

If you own Mira glasses and would like to try one of these apps, feel free to download the source and experiment with it\.

Suggestions, bug reports, improvements, and ideas for new Mira mini apps are welcome\.

## Disclaimer

These are unofficial community\-created applications\.

They are not produced, endorsed, or supported by Mira\.

Use them at your own discretion, particularly while the Mira SDK and hardware platform are still evolving\.

## License

Unless otherwise noted, the code in this repository is intended for personal experimentation and community sharing\.

A formal open\-source license may be added later\.
