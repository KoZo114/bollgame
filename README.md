# Neon Breakout (ネオンブロック崩し)

A unique, single-file HTML5 Breakout game where you draw neon lines to bounce the ball instead of using a traditional paddle! Completely self-contained with procedurally generated 8-bit style BGM and sound effects using the Web Audio API.

## Features ✨
* **Single HTML File:** No external dependencies, no image assets, and no audio files to load. Everything runs locally in your browser!
* **Draw-to-Play Mechanics:** Swipe or drag your mouse to create "trampolines" that bounce the ball back towards the bricks.
* **Procedural Audio:** 8-bit style synthesizer BGM and sound effects powered by the Web Audio API (optimized for mobile autoplay restrictions).
* **3 Stages of Increasing Difficulty:**
    * **Stage 1:** Beginner-friendly. No gaps between bricks and you can draw longer lines.
    * **Stage 2:** Increased speed and gaps between bricks. Normal line length.
    * **Stage 3:** High speed, pyramid layout, hard-to-hit "indestructible grey bricks", and shorter line length.
* **Special Trick Lines:**
    * **Golden Line (Acceleration):** Drawn every 10 times. Bouncing the ball off this line will significantly increase its speed with a striking "Gyuiiin!" sound.
    * **Purple Line (Shrink Ball):** Appears every 5 lines only in Stage 3. This trick line shrinks the ball, requiring more precise aiming!
* **3-Life System:** You start with 3 lives (2 visible hearts + your final chance). If the ball drops to the bottom, you lose a life but can quickly respawn.
* **Mobile-First Design:** Fully responsive canvas that resizes to fit your browser window, with robust multi-touch support.

## How to Play 🎮
1. **Open the Game:** Simply open `ブロック崩し.html` in any modern web browser (Chrome, Safari, Firefox, Edge).
2. **Start:** Click or tap the "TAP TO START" button to initialize the audio and begin the game.
3. **Draw Lines:** Click and drag (or drag your finger on a touch screen) to draw a glowing cyan line.
    * The ball will bounce off the line you draw.
    * You can only draw **one line at a time**.
    * After the line disappears, there is a **0.2-second cooldown** before you can draw another.
4. **Clear the Stage:** Destroy all the colorful bricks to proceed to the next stage.
    * Note: In Stage 3, the grey bricks are indestructible and act as obstacles. You do not need to destroy them to clear the stage.

## Tech Stack 🛠
* HTML5 `<canvas>`
* Vanilla JavaScript (ES6)
* Web Audio API
* CSS3 (Animations & Flexbox)

## License
MIT License. Feel free to fork, modify, and create your own amazing stages!
