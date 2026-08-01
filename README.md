# 🃏 Solitaire (Klondike) - Version 8.1

Welcome to **Solitaire by Emenes Interactive**! This is a modern, feature-rich edition of the classic Klondike Solitaire game. Built entirely using native HTML5, CSS3, and pure JavaScript (no external dependencies), this version is enhanced with a live timer, instant local state preservation, full English localization, undo/reset features, custom sound effects, and vibrant visual styling.

## 🚀 Play Now (Direct Game Link)
Launch the game directly in your web browser here:
👉 **[CLICK HERE TO PLAY SOLITAIRE](https://emenes.github.io/solitaire-byEmenes/)**

---

## ✨ Features (New in Version 8.1)

*   **⏱️ Live Gameplay Timer:** Score points have been replaced with a real-time live timer. Counting starts automatically on your first move and displays your final completion time upon victory.
*   **↩️ Undo & 🔄 Reset Controls:** 
    *   **Undo:** Reverts your latest move back to its previous state.
    *   **Reset:** Resets the board and rearranges all cards back to the exact initial deal, clearing time and move history after a confirmation warning.
*   **💾 Auto-Save (LocalStorage):** Progress is saved automatically to your browser in real time. Closing or refreshing the browser allows you to resume right where you left off.
*   **⭐ Smart Auto-Solve:** Once all face-down cards on the Tableau are revealed and the Stock is empty, a compact Auto-Solve button appears next to the Hint button to quickly finish the game.
*   **📦 Compact Backup Modal:** Unified `Backup` button that opens a clean modal containing options to export or import your `solitaire_game_v8.1.json` backup file.
*   **🌐 Full English Support:** Clean, fully translated interface and system alert dialogs across all features.
*   **🎨 Dynamic Cosmetics Sidebar:** Personalize your playing field seamlessly by changing background gradients or selecting custom card back designs.
*   **🔊 Responsive Synthesized Audio:** Powered by the browser's *Web Audio API*, generating instant audio feedback when drawing or moving cards.

---

## 🎮 How to Play (Game Rules)

1.  **Main Objective:** Move all cards to the four **Foundation** slots in the top right corner. Each pile must be built up by suit, starting sequentially from **Ace (A) to King (K)**.
2.  **Tableau Movement (Bottom Columns):** Cards in the columns can be stacked in descending order, but they must strictly **alternate in color** (e.g., place a Red 6 on top of a Black 7).
3.  **Empty Columns:** If a column on the tableau becomes completely empty, only a **King (K)** (or a valid sequence starting with a King) can be placed into that empty slot.
4.  **Stock & Waste Pile:** Tap the face-down Stock pile in the top left to draw cards into the Waste pile when looking for new moves.

---

## 🛠️ Technology Stack
*   **HTML5** - Clean semantic structural setup and accessible UI layout.
*   **CSS3** - Customized interactive modals, responsive sizing, CSS custom properties for instant styling switches, and keyframe animations.
*   **Vanilla JavaScript (ES6)** - Client-side state history management, local storage synchronization, predictive layout validation logic, JSON import/export, and procedural Web Audio wave generation.

---
Published by **EMENES INTERACTIVE** | Stable Release (2026)
