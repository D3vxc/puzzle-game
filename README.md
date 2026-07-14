# Frame Puzzle

A browser-based gesture camera that turns a hand-framed photo into a 3×3 puzzle. Use pinch gestures to capture and arrange the image, then make a fist to save it to a downloadable photo strip.

## About this version

This English-language version refreshes the visual design with an editorial studio layout, a new type hierarchy, and a responsive photo-strip panel.

- **Customized and localized by:** `YOUR NAME`
- **GitHub:** `https://github.com/YOUR-GITHUB-USERNAME`

Replace the two placeholders above with your name and GitHub profile before publishing.

## Original project and attribution

This project is a customized derivative of [PuzzleCam by D3vxc](https://github.com/D3vxc/puzzle-game). The original author created the gesture-controlled puzzle concept and application code. This version changes the interface language and visual presentation; it does not claim ownership of the original work.

## Features

- Uses your webcam and MediaPipe hand tracking in the browser
- Captures a photo inside a frame created with two hands
- Splits the capture into a black-and-white 3×3 puzzle
- Lets you drag pieces with a pinch gesture
- Saves up to three completed puzzles in a downloadable photo strip

## Run locally

Camera permissions and JavaScript modules require a local HTTP server; opening `index.html` directly will not work.

1. Clone this repository.
2. Open the folder in VS Code.
3. Start it with the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer), or another local web server.
4. Visit the local address shown by the server, typically `http://localhost:5500`.
5. Allow browser access to your camera.

## Gesture controls

| Gesture                   | Action                                                |
| ------------------------- | ----------------------------------------------------- |
| Pinch with both hands     | Hold to set the capture frame and start the countdown |
| Pinch over a puzzle piece | Drag the selected piece                               |
| Hold a closed fist        | Save a completed puzzle, or reset the active board    |

## Technology

- [MediaPipe Tasks Vision](https://developers.google.com/mediapipe) for hand landmarks
- Canvas 2D API for camera rendering and puzzle effects
- Vanilla JavaScript modules and CSS

## Publishing and licence note

The upstream README states that the original project is MIT licensed, but this checkout does not include a licence file. Before publishing a public copy, confirm the licence with the original author or upstream repository and retain any required copyright and licence notices. A GitHub fork is the clearest way to preserve the project's history and attribution.
