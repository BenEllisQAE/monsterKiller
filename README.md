# Monster Killer Game

A simple interactive browser game built with HTML, CSS, and JavaScript where you
can fight a monster, heal, and track battle events. This project demonstrates
use of JavaScript fundamentals like functions, loops, conditional statements,
error handling, and event listeners.

---

## Downloading the Project

If you are seeing this project for the first time, you can download it from
GitHub in two ways:

### 1. Using the "Download ZIP" option

1. Go to the GitHub repository page.
2. Click the green **Code** button.
3. Select **Download ZIP**.
4. Extract the ZIP file to a folder on your computer.

### 2. Using Git (for users familiar with command line)

1. Make sure you have Git installed on your computer.
2. Open a terminal or command prompt.
3. Run the command:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

---

## How to Run

1. Make sure all project files (HTML, JS, CSS if any) are in the same folder.
2. Open the HTML file in any modern web browser (Chrome, Firefox, Edge, etc.).
   - Right-click the HTML file → **Open with** → select your browser.
3. You will see the game interface with:
   - **4 buttons:** Attack, Strong Attack, Heal, Show Log
   - **2 health bars:** Player and Monster
4. Upon starting, you will be prompted to enter the **maximum life** for both
   the player and the monster.
   - If invalid input is entered (not a number or special forbidden numbers like
     `666`), an **error is handled** and a default value of 100 is used.

---

## Things You Can Try

- **Attack** the monster using the normal attack button (reduces monster health
  by 10).
- **Use Strong Attack** to deal more damage (17 points) but with higher risk.
- **Heal Yourself** to restore health (up to the initial maximum life).
- **Check the Battle Log** to see previous game events.
- **Enter invalid input** (like a string or 0) in the prompt to see **TypeError
  handling** in action.
- **Enter forbidden numbers** (like `666`) to see how a **generic Error** is
  thrown and caught.
- Observe **bonus life** in action: if your health drops to 0 once, the bonus
  life saves you automatically.
- Watch the **health bar updates** and how the game alerts you when the game is
  won, lost, or drawn.
- Experiment with the **console logging** features:
  - Battle log entries
  - Loops with `for`, `do...while`, `for...of`, and labeled loops
- Try **healing when near max health** and see the alert for exceeding maximum
  health.
- Observe how the game **resets automatically** after a game over.

---

## Features Demonstrating JavaScript Learning

- **Constants and Variables:** Defined attack/heal values and modes.
- **Functions:** For attacks, healing, logging, and game logic.
- **Error Handling:** `TypeError` for invalid input, generic `Error` for
  forbidden values.
- **Conditional Logic:** `if`, `else if`, `else` for game outcomes.
- **Loops:** `for`, `while`, `do...while`, `for...of` with break/continue
  labels.
- **Event Listeners:** Buttons trigger game actions.
- **Objects:** Battle log entries store structured data.
- **Alerts and Console Logging:** Feedback to the user and debugging output.
- **Game State Management:** Health bars, bonus life, and automatic resets.
