# 🃏 Solitaire (Klondike) - Version 7.0

Welcome to **Solitaire by Emenes Interactive**! This is a simple modern, feature-rich edition of the classic Klondike Solitaire game. Built entirely using native HTML5, CSS3, and pure JavaScript (no external dependencies), this version is enhanced with custom sound effects, vibrant visual styling, state backup management, and a smart assistance engine.

## 🚀 Play Now (Direct Game Link)
Launch the game directly in your web browser here:
👉 **[CLICK HERE TO PLAY SOLITAIRE](https://emenes.github.io/solitaire-byEmenes/)**

---

## ✨ Features

*   **💡 Smart AI Hint Engine:** Stuck on a board state? Use the Hint system! It consumes 5 score points to automatically identify and execute the most optimal move, highlighting the newly moved card with a prominent 3-second golden glow animation.
*   **🧩 Instant Auto-Solve:** Want to see the victory state immediately? The Solve feature programmatically completes the entire board with a single click (sets final score to 0).
*   **🎨 Dynamic Cosmetics Sidebar:** Personalize your playing field seamlessly. Change the board's ambient backdrop (Forest, Ocean, Midnight, Crimson, etc.) and swap card back graphics background.
*   **💾 Secure Save & Load Backup:** Download your exact live game state as a clean JSON file (`solitaire_game.json`) and import it back later to pick up right where you left off without losing your progress.
*   **🔊 Responsive Synthesized Audio:** Powered by the browser's *Web Audio API*, the game generates real-time, click-less sound effects whenever cards are drawn, revealed, or successfully repositioned.

---

## 🎮 How to Play (Game Rules)

1.  **Main Objective:** Move all cards to the four **Foundation** slots in the top right corner. Each pile must be built up by suit, starting sequentially from **Ace (A) to King (K)**.
2.  **Tableau Movement (Bottom Columns):** Cards in the columns can be stacked in descending order, but they must strictly **alternate in color** (e.g., you can only place a Red 6 on top of a Black 7).
3.  **Empty Columns:** If a column on the tableau becomes completely empty, only a **King (K)** (or a valid sequence starting with a King) can be placed into that empty slot.
4.  **Stock & Waste Pile:** When you run out of playable moves on the board, tap the face-down Stock pile in the top left to draw cards into the Waste pile.

### 📊 Scoring System Breakdown
*   Moving a card to the Foundation: `+10 Points`
*   Pulling a card back OUT of the Foundation into the Tableau: `-10 Points`
*   Requesting a Smart Hint: `-5 Points`

---

## 🛠️ Technology Stack
*   **HTML5** - Clean semantic structural setup and accessible UI layout.
*   **CSS3** - Customized interactive modals, responsive sizing, CSS custom properties for instant styling switches, and linear keyframe glow animations.
*   **Vanilla JavaScript (ES6)** - Predictive layout validation logic, board state calculation algorithms, local client-side JSON I/O, and mathematical procedural wave generation for Web Audio.

---
Published by **EMENES INTERACTIVE** | Stable Release (2026)
