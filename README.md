# Mira Mini Apps

Community\-made mini apps, games, utilities, and experiments for Mira smart glasses, built using the public Mira SDK\.

This repository is intended as a simple place to collect and share small Mira applications that can be loaded through the Mira app\-creation interface\.

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

## Adding an App to Mira

1. Open the desired HTML file and copy its complete contents\.
2. Select **Build a Mira App** in the Mira app\.
3. Paste the code into the app\-code field\.
4. Select **Check code**, save the app, and run it after connecting the glasses\.

The phone companion may display **Waiting for the glasses…** until the glasses are connected and the app is running\. This is normal\.

## Testing Status

**Lunar Descent has been tested and validated on physical Mira glasses\.**

It is confirmed working with the current Mira glasses and companion\-app software as of **September 29, 2026**\.

Future Mira firmware, app, SDK, or runtime changes may require the app to be updated or rebuilt\.

## Development

These apps were created with ChatGPT and reviewed against the public Mira mini\-app / WASM API\. They are independent community projects and are not official Mira software\.
