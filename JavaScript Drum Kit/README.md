# JavaScript Drum Kit

A fun keyboard-powered drum machine built with vanilla JavaScript, HTML, and CSS.

Press keys on your keyboard to trigger drum sounds with visual key animations.

## Preview

This project includes:
- Instant sound playback on key press
- Key highlight animation while sound is playing
- Smooth transition reset after animation ends
- Support for 9 drum sounds mapped to keyboard keys

## Key Mappings

| Key | Sound |
|-----|-------|
| A   | Clap  |
| S   | Hihat |
| D   | Kick  |
| F   | Openhat |
| G   | Boom  |
| H   | Ride  |
| J   | Snare |
| K   | Tom   |
| L   | Tink  |

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript (no frameworks)

## Project Structure

```text
JavaScript Drum Kit/
├── index-START.html
├── index-FINISHED.html
├── style.css
├── background.jpg
└── sounds/
	├── clap.wav
	├── hihat.wav
	├── kick.wav
	├── openhat.wav
	├── boom.wav
	├── ride.wav
	├── snare.wav
	├── tom.wav
	└── tink.wav
```

## How to Run

### Option 1: Open directly
1. Open `index-FINISHED.html` in your browser.
2. Click the page once (some browsers require focus for keyboard events).
3. Press `A S D F G H J K L` to play sounds.

### Option 2: Use VS Code Live Server
1. Open the project folder in VS Code.
2. Right-click `index-FINISHED.html`.
3. Choose **Open with Live Server**.

## Learning Notes

This project demonstrates:
- Listening for keyboard events with `keydown`
- Selecting elements with data attributes
- Restarting audio quickly using `audio.currentTime = 0`
- Handling CSS transition end events for clean animation reset

## License

This project is for learning and practice.
