Mira Mini Apps

Community-made mini apps, games, utilities, and experiments for Mira smart glasses, built using the public Mira SDK.

This repository is intended as a simple place to collect and share small Mira applications that can be loaded through the Mira app-creation interface.

Current Apps

Lunar Descent

A retro moon-landing game designed for the Mira glasses display and input system.

Features include:

• Glasses-friendly 640×480 interface
• Multiple missions with varied terrain and landing-pad placement
• Fuel, altitude, vertical speed, horizontal speed, and attitude displays
• Landing evaluation based on pad position, descent speed, sideways speed, and lander angle
• Scoring for successful landings and mission progression
• Persistent best score retained between app sessions
• Ring / touch-bar controls
• Phone companion controls for rotation, thrust, starting the next mission, and restarting a run

Glasses controls:

• Swipe one way or the other to rotate the lander
• Tap for a short engine burst
• Hold for sustained thrust
• Release to stop sustained thrust
• Tap to begin, advance after a successful landing, or start a new run after a crash

Fleet Grid

A Battleship-style strategy game designed for Mira glasses, with head aiming, ring / touch-bar controls, and a phone companion.

Features include:

• 10×10 enemy targeting grid
• Standard fleet sizes of 5, 4, 3, 3, and 2
• Automatically placed player and enemy fleets
• Head-position aiming for selecting target cells
• Adjustable horizontal and vertical head-selection range
• Optional X and Y axis inversion
• Swipe-based cell-by-cell backup controls
• Long-press recentering for head aiming
• Tap-to-fire controls
• Hit, miss, sunk-ship, win, and loss tracking
• Computer opponent with hunt/parity targeting behavior
• Phone companion showing your fleet, incoming hits and misses, remaining ships, shot count, and controls

Glasses controls:

• Look around to select a target cell while head aiming is active
• Tap to fire at the selected cell
• Swipe forward or backward to step through cells manually
• Long-press to recenter head aiming
• Tap after the game ends to start a new game

Adding an App to Mira

1. Open the desired HTML file and copy its complete contents.
2. Select Build a Mira App in the Mira app.
3. Paste the code into the app-code field.
4. Select Check code, save the app, and run it after connecting the glasses.

The phone companion may display Waiting for the glasses… until the glasses are connected and the app is running. This is normal.

Testing Status

Lunar Descent and Fleet Grid have both been tested and validated on physical Mira glasses.

• Lunar Descent — confirmed working with the current Mira glasses and companion-app software as of September 29, 2026
• Fleet Grid — confirmed working with the current Mira glasses and companion-app software as of September 30, 2026

Future Mira firmware, app, SDK, or runtime changes may require an app to be updated or rebuilt.

Development

These apps were created with ChatGPT and reviewed against the public Mira mini-app / WASM API. They are independent community projects and are not official Mira software.
