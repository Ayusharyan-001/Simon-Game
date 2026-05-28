# Simon Game

A classic browser-based Simon memory game built with HTML, CSS, and JavaScript. Players must repeat an increasingly long sequence of colored lights and sounds. The game resets when the player makes a mistake.

---

## ?? Overview

This Simon game recreates the classic electronic memory challenge using a simple and responsive UI. The computer generates a sequence of four colors, and the player must repeat the sequence by clicking the colored pads in the correct order.

## ?? Features

- Four-color Simon pad with sound and animation
- Start button and power toggle
- Strict mode option
- Progressive sequence generation up to 20 steps
- Visual feedback for correct and incorrect input

## ??? Screenshots

> Replace these image paths with your own screenshots if you add files to the project.

![Simon Game Start Screen](./assets/simon-start.png)

![Simon Game In Action](./assets/simon-play.png)

## ?? How to Play

1. Click the **Power** toggle to turn the game on.
2. Press the **Start** button to begin.
3. Watch the computer play a sequence of lights.
4. Repeat the sequence by clicking the colored pads.
5. If your input is correct, the game advances to the next round.
6. If you make a mistake, the game shows **NO!** and replays the sequence.

## ?? Installation

1. Clone or download the repository.
2. Open `index.html` in your web browser.

```bash
# Example using Windows PowerShell
Start-Process "index.html"
```

## ?? Project Structure

```
Simon game/
  +- index.html          # Main game page
  +- style.css           # Game styling
  +- index.js            # Game logic
  +- README.md           # Project documentation
```

## ?? File Summary

- `index.html` — game interface and audio assets
- `style.css` — layout and color styles
- `index.js` — sequence generation, user input handling, and game flow

## ?? Notes

- The game is designed to work in modern browsers.
- Audio playback may require user interaction before first sound is heard.

## ?? Future Improvements

- Add a high score counter and persistent score storage
- Add mobile touch support for better device compatibility
- Add sound toggle and difficulty settings
- Add a smoother animation sequence and transition effects

## ?? Contribution Templates

### Bug Report Template

```md
## Bug Report

**Describe the bug**
A clear and concise description of what the bug is.

**Steps to reproduce**
1. Go to `index.html`
2. Turn the game on
3. Press start
4. Enter the wrong sequence

**Expected behavior**
What you expected to happen.

**Screenshots**
If applicable, add screenshots to help explain your problem.

**Environment**
- Browser: Chrome / Edge / Firefox
- OS: Windows / macOS / Linux
```

### Feature Request Template

```md
## Feature Request

**Describe the solution you'd like**
A clear and concise description of what you want to happen.

**Why is this feature important?**
Explain the benefit or use case.

**Additional context**
Add any other context or screenshots about the feature request here.
```

## ?? License

Feel free to use and modify this project for learning and personal use.

---

Happy coding! ??
