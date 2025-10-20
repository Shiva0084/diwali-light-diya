# diwali-light-diya
# Diwali Fireworks

A simple, elegant webpage that plays a festive fireworks video with audio to celebrate Diwali. The user is prompted to tap/click to start the animation and sound due to browser autoplay restrictions. After the video or a timeout, the page redirects to a wish page.

---

## Features

- Responsive full-screen fireworks video with audio.
- Overlay text with smooth fade-in animation.
- Skip button to jump directly to the wish page.
- Start overlay to enable user interaction for autoplay compliance.
- Festive diya emojis at the top for extra decoration.

---

## How to Use

1. Place your video file (`fireworks.mp4`) in the `assets` folder.
2. Place your sound file (`fireworks.mp3`) in the `assets/sounds` folder.
3. Open `index.html` in a modern web browser.
4. Tap or click anywhere on the start overlay to begin the fireworks with sound.
5. Enjoy the fireworks! After it ends or after 7 seconds, the page will automatically redirect to `wish.html`.
6. Optionally, click the **Skip to Wish** button to skip directly.

---

## Files Structure

/
├── assets/
│ ├── fireworks.mp4
│ └── sounds/
│ └── fireworks.mp3
├── index.html
└── wish.html

---

## Notes

- The video contains its own audio track; the separate audio element is optional or can be used for additional sound effects.
- Browsers require user interaction to play audio/video with sound; hence the start overlay.
- The `wish.html` page should contain your Diwali greeting or wishes.

---

## License

This project is open source and free to use for personal and festive projects.

---

Enjoy the Diwali celebrations! 🪔✨
