Super Maths Challenge 3.7 🐼🦁

**Super Maths Challenge** is a polished, gamified, single-file web application designed to help users practice various mathematics skills ranging from basic arithmetic to simple algebra. It features a responsive design, sound effects, visual feedback, and a persistent high-score system.

## 🌟 Key Features

* **Zero Dependencies:** The entire game runs from a single HTML file. No external libraries, images, or audio files are required (Audio is synthesized via the Web Audio API).
* **10 Unique Game Modes:** Covers skills from Junior level (sums to 10) to Algebra and Roots.
* **Progressive System:**
    * **XP & Ranks:** Level up from "Novice" to "GODLIKE."
    * **Streaks & Multipliers:** Build streaks to earn 2x and 3x score multipliers.
* **High Score Saving:** Best scores for every mode are saved automatically to your browser's Local Storage.
* **Visual Polish:** Includes particle backgrounds, confetti effects, mascot animations, and smooth transitions.
* **Theme Support:** Toggle between Dark (default) and Light modes.
* **Input Support:** Play using mouse click, touch (mobile), or keyboard number keys (1-4).

## 🚀 How to Run

1.  **Download:** Save the file `maths_challenge_core_progressbar (3).html` to your computer.
2.  **Open:** Double-click the file to open it in any modern web browser (Chrome, Firefox, Safari, Edge).
3.  **Play:** No internet connection is required (except to load the Google Font, though it falls back gracefully if offline).

## 🎮 Game Modes

1.  **🐣 Junior:** Simple addition sums totaling 10.
2.  **🔢 Placement:** Identify the value of a specific digit (Place Value).
3.  **➕ Addition:** Standard addition problems.
4.  **➖ Subtraction:** Standard subtraction problems.
5.  **✖ Multiplication:** Times tables practice (2-9).
6.  **➗ Division:** Basic division facts.
7.  **🍕 Fractions:** Calculate fractions of amounts.
8.  **💪 Powers:** Squares ($x^2$) and Cubes ($x^3$).
9.  **🌱 Roots:** Square roots of perfect squares.
10. **🧠 Algebra:** Solve for $x$ in simple equations (e.g., $x + 5 = 12$).

## 🕹 Controls

* **Mouse/Touch:** Click the answer buttons on the screen.
* **Keyboard:** Press keys `1`, `2`, `3`, or `4` to select the corresponding answer (Top-Left is 1, Top-Right is 2, Bottom-Left is 3, Bottom-Right is 4).
* **Menu:**
    * Select an **Avatar** to play as.
    * Choose a **Mission** (Game Mode).
    * Select a **Time Limit** (1, 2, or 5 minutes).

## 🛠 Technical Details

* **Tech Stack:** HTML5, CSS3, Vanilla JavaScript (ES6+).
* **Audio:** Custom-built `AudioSys` object uses the Web Audio API to generate oscillators for sound effects (correct, wrong, level up, tick) without needing `.mp3` or `.wav` assets.
* **Storage:** Uses `localStorage` key `'superMathsScoresV2'` to store high scores.
* **Responsiveness:** CSS Grid and Flexbox are used to ensure the layout adapts to mobile phones, tablets, and desktops.
* **Design System:** Uses CSS Variables (`:root`) for easy theming and color management.

## 🎨 Customization

To modify the game, open the file in a text editor (like VS Code or Notepad++).

* **Change Colors:** Edit the `:root` variables in the `<style>` section (e.g., `--primary`, `--bg-dark`).
* **Adjust Difficulty:** Look for the `generateQ()` function in the `<script>` tag. You can change the number ranges (e.g., change `r(2, 10)` to `r(2, 100)` for harder math).
* **Edit Ranks:** Modify the `RANKS` array in the JavaScript section to change titles or score thresholds.

***
