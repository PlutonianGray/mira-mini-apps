Mira Mini Apps

Community-made mini apps, games, utilities, and experiments for Mira smart glasses, built using the public Mira SDK.

This repository is intended as a simple place to collect and share small Mira applications that can be loaded through the Mira app-creation interface.

Current Apps

Sudoku

A Sudoku game designed for the Mira glasses display and input system.

Features include:

• 3,000 built-in Sudoku puzzles
• 1,000 Easy puzzles
• 1,000 Medium puzzles
• 1,000 Hard puzzles
• Glasses-friendly 640×480 interface
• Grid-based navigation
• Mira touch/ring controls
• Head-controlled cell selection
• Phone companion controls and settings
• Hint, check, undo, and erase functions
• Self-contained HTML package

Minesweeper

A classic Minesweeper-style game adapted for Mira glasses.

Features include:

• 9×9 beginner board
• 10 mines
• First-tap safety for the selected cell and its surrounding cells
• Automatic clearing of empty areas
• Flags
• Win and loss detection
• Touch/ring controls
• Swipe navigation
• Head-controlled cell selection
• Phone companion controls and head-pointer settings
• Self-contained HTML package

Fleet Grid

A Battleship-style naval strategy game designed for the Mira glasses display and controls.

Place your fleet automatically, then search the opposing grid and attempt to sink the enemy fleet before yours is destroyed.

Features include:

• 10×10 naval strategy grid
• Standard ship sizes: 5, 4, 3, 3, 2
• Automatic fleet placement
• Player and opponent fleets
• Hit, miss, and sunk tracking
• Hunt/target computer opponent
• Win and loss detection
• Mira touch/ring navigation
• Head-controlled grid selection
• Phone companion controls and head-pointer settings
• Phone view of your fleet and incoming enemy fire
• Glasses-friendly interface
• Self-contained HTML package

Descent to Luna

A retro moon-landing game designed for the Mira glasses display and controls.

Pilot the lander toward the landing pad while managing descent speed, horizontal motion, attitude, and limited fuel. Land safely to score points and advance to the next mission.

Features include:

• Glasses-friendly 640×480 interface
• Simulated lunar gravity and lander physics
• Procedurally varied lunar terrain and landing pad placement
• Mission progression with increasing difficulty
• Fuel management
• Vertical speed, horizontal speed, altitude, and attitude HUD
• Safe-landing and crash detection
• Score and best-score tracking
• Mira ring/touch-bar rotation controls
• Tap for a short engine burst
• Hold for sustained thrust
• Phone companion controls for rotation, thrust, starting, and restarting
• Self-contained HTML package

SoliMira

SoliMira is an unofficial, community-made app for Mira glasses.

A compact Klondike-style solitaire game adapted for the Mira glasses display and controls.

Features include:

• Standard 52-card Klondike gameplay
• Seven tableau columns
• Stock and waste piles
• Four suit foundations
• Alternating-color descending tableau moves
• Automatic exposure of newly uncovered cards
• Stock recycling
• Multi-card tableau moves
• Auto-home function for legal foundation moves
• Undo support
• Win detection
• Mira swipe/ring navigation
• Tap to select, pick, draw, or move cards
• Long-press context actions for auto-home, undo, cancel, and new game
• Phone companion controls and live game status
• Lowercase ranks for red cards (hearts and diamonds)
• Selectable suit display using ♠/♥/♦/♣ glyphs or S/H/D/C letters
• Suit-display preference saved on the phone and re-synchronized when the glasses connect
• Glasses-friendly 640×480 interface
• Self-contained HTML package

Alien Defense

A retro fixed-screen alien-defense arcade game designed for the Mira glasses display and controls.

Defend Earth against descending alien formations while using shields for cover, destroying bonus craft, and surviving increasingly difficult waves.

Features include:

• Glasses-friendly 640×480 interface
• 8×5 descending alien formation
• Multiple alien types with row-based scoring
• Four destructible defensive bunkers
• Enemy projectile fire
• Three-player-life system
• Increasing wave difficulty
• Bonus UFO targets
• Score and persistent best-score tracking
• Mira ring/touch-bar left and right movement
• Tap to fire
• Optional head-controlled horizontal steering
• Long-press head-steering recenter
• Phone companion controls and head-steering settings
• Invert and horizontal head-span options
• Self-contained HTML package

Ziggy I, II, and III

Three complete classic underground text adventures packaged together as one unofficial community-made Mira app.

The app contains the complete original Zork I, Zork II, and Zork III Z-machine stories, presented on Mira as Ziggy I, Ziggy II, and Ziggy III. Ordinary commands are interpreted by the original game parser rather than by AI.

Features include:

• Three complete adventures in one app
• Ziggy I — The Great Underground Empire
• Ziggy II — The Wizard of Frobozz
• Ziggy III — The Dungeon Master
• Original rooms, objects, puzzles, parser behavior, scoring, and endings
• Glasses-side command terminal and lightweight status display
• Tap-to-dictate command entry with confirmation before sending
• Swipe navigation through game output
• Long-press access to quick commands
• Phone companion with game selection, transcript, status, and text command entry
• Quick commands for common actions
• Three manual save slots for each adventure
• Save, restore, one-turn undo, and restart/new-game support
• Autosave after completed turns
• Automatic continuation of the most recently active adventure
• Local phone persistence
• Embedded Z-machine interpreter and story files
• No network connection, external scripts, conversion, or AI required during play
• Included attribution and license notices for the original stories and interpreter
• Self-contained HTML package

Ziggy PDF Reader

A feature-rich PDF reader designed to keep a small document library on the phone and make PDF text practical to read on Mira glasses.

This is the PDF-specific reader in the repository. It emphasizes document navigation, persistent reading state, search, glasses-side reading caches, and limited handling of PDF visuals.

Features include:

• Direct PDF import on the phone
• Local PDF text extraction without uploading the document
• Persistent on-phone PDF library
• Saved reading position
• Document rename and delete controls
• Search within a PDF with jump-to-result navigation
• Direct PDF page jumping
• Normal and large glasses text modes
• Phone preview and navigation controls
• Mira swipe/ring navigation through reading screens
• Cached reading screens on the glasses for faster local navigation
• Full-document caching when practical and rolling nearby-screen caching for larger documents
• Simple PDF image detection and conversion to compact Mira-friendly bitmap previews when supported
• Visual-note fallback for complex, vector-only, or unsupported PDF graphics
• Self-contained HTML package

Phosphor

An alternative document reader for Mira glasses, developed independently from Ziggy PDF Reader with a simpler reading-library approach.

Phosphor focuses on extracting readable text on the phone and sending that text to the glasses. In addition to PDFs, it can also accept plain-text and Markdown files.

Features include:

• PDF, .txt, and .md import
• Local extraction of selectable PDF text on the phone
• No external PDF-processing download or service required
• On-phone document library
• Search across documents with jump-to-match navigation
• Line-by-line glasses scrolling
• Page navigation from the glasses or phone companion
• Library selection directly on the glasses
• Support for simple built-in line drawings
• Placeholder treatment for photographs that cannot be rendered on the Mira display
• Detection of locked PDFs and PDFs without selectable text
• Up to 40 imported lens pages per document
• Self-contained HTML package

Why Two PDF Readers?

Ziggy PDF Reader and Phosphor are separate implementations rather than different versions of the same app.

Ziggy PDF Reader is the more PDF-focused implementation, with persistent reading state, two text sizes, page jumping, cached glasses-side reading screens, and limited extraction of supported PDF visuals.

Phosphor uses a lighter document-library model, supports PDF/TXT/Markdown input, emphasizes line-by-line text reading, and uses simpler drawing and photograph-placeholder handling.

Both perform PDF text extraction locally on the phone and are included so Mira users can try the approach that works best for their documents and reading style.

Installation

Each Mira app is provided as a single .html file.

To use an app:

1. Download or copy the desired .html file.
2. Open the Mira app-creation interface on your iPhone.
3. Create a new mini app.
4. Paste or import the HTML source.
5. Save the app.
6. Connect your Mira glasses.
7. Run the app from the Mira app.

No additional JavaScript libraries, packages, or external files are required unless specifically noted.

Controls

Controls may vary by app, but Mira mini apps can use standard glasses inputs such as:

• Tap / click
• Long press
• Swipe up
• Swipe down
• Mira ring controls
• Head movement using the glasses’ IMU sensors

Individual apps include their own control instructions.

Hardware Testing

These apps are being developed using Mira’s public SDK.

Some apps may initially be created and tested in the Mira iPhone app before being tested on physical Mira glasses.

Because the Mira SDK and hardware ecosystem are still relatively new, behavior may change as Mira updates its firmware, SDK, or iPhone app.

If you try one of these apps on actual Mira glasses and find a problem, feedback is welcome.

About the Code

The apps in this repository are intentionally designed to be:

• Small
• Self-contained
• Easy to inspect
• Easy to modify
• Easy to share
• Suitable for learning the Mira SDK

Most apps consist of one combined HTML file containing both the Mira glasses code and, when needed, an optional iPhone companion interface.

Community

If you own Mira glasses and would like to try one of these apps, feel free to download the source and experiment with it.

Suggestions, bug reports, improvements, and ideas for new Mira mini apps are welcome.

Disclaimer

These are unofficial community-created applications.

They are not produced, endorsed, or supported by Mira.

Use them at your own discretion, particularly while the Mira SDK and hardware platform are still evolving.

License

Unless otherwise noted, the code in this repository is intended for personal experimentation and community sharing.

A formal open-source license may be added later.
