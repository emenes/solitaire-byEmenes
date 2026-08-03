# 🃏 Solitaire (Klondike) - Version 8.3

Welcome to **Solitaire by Emenes Interactive**! This is a modern, feature-rich edition of the classic Klondike Solitaire game. Built entirely using native HTML5, CSS3, and pure JavaScript (no external dependencies), this version is optimized across desktop and mobile browsers, equipped with full cross-platform drag-and-drop support, dynamic difficulty selection algorithms, unlimited stock pile rerolls, and comprehensive progress management.

## 🚀 Play Now (Direct Game Link)
Launch the game directly in your web browser here:
👉 **[CLICK HERE TO PLAY SOLITAIRE](https://emenes.github.io/solitaire-byEmenes/)**

---

## ✨ Features (Updated in Version 8.3)

*   **🎯 Dynamic Difficulty Engine (Easy, Medium, Hard, Master, Expert):** 
    *   Players select their preferred difficulty mode upon launching or starting a new game.
    *   The shuffling algorithm dynamically adjusts card arrangement based on chosen difficulty:
        *   **Easy:** Draws 1 card; Aces are prioritized near the top of the deck for an accessible start.
        *   **Medium & Hard:** Draws 2 and 3 cards respectively; fully randomized standard deck distribution.
        *   **Master & Expert:** Draws 3 cards; Aces are strategically buried deeper toward the bottom of the stock pile to increase challenge.
*   **♾️ Unlimited Stock Rerolls (No Limit Restriction):** The Stock pile permits infinite rerolls across all difficulty levels without restrictions or pass limits, keeping gameplay smooth and continuous.
*   **🎛️ Bottom Navigation Difficulty Control:** A dedicated **Difficulty** button located alongside *Reset*, *Undo*, and *How to Play* allows quick difficulty adjustments with instant modal warnings before resetting to a new deal.
*   **🌐 Cross-Browser & Mobile Touch Optimization:** Full drag-and-drop compatibility across Firefox, Google Chrome, Edge, Opera, as well as native Touch Event support for tablets and mobile devices.
*   **⏱️ Live Gameplay Timer:** Score points are replaced with a real-time live timer that triggers on your first move and records final completion time.
*   **↩️ Undo & 🔄 Reset Controls:** 
    *   **Undo:** Reverts your latest move back to its previous state.
    *   **Reset:** Resets the board and rearranges all cards back to the exact initial deal, clearing time and move history after confirmation.
*   **💾 LocalStorage Auto-Save:** Automatically preserves game state, timer, and difficulty settings in real time, allowing players to resume previous sessions seamlessly.
*   **⭐ Smart Auto-Solve:** Automatically displays an Auto-Solve button once all face-down cards on the Tableau are revealed and the Stock is cleared.
*   **📦 Backup Modal (v8.3 Support):** Unified `Backup` button allowing users to save or load game progress via `solitaire_game_v8.3.json` files.
*   **🎨 Cosmetics Customization:** Change background themes and custom card back patterns via the responsive sidebar menu.
*   **🔊 Synthesized Web Audio API:** Generates real-time audio feedback when drawing or placing cards.

---

## 🎮 How to Play (Game Rules)

1.  **Main Objective:** Move all cards to the four **Foundation** slots in the top right corner. Each pile must be built up by suit, starting sequentially from **Ace (A) to King (K)**.
2.  **Tableau Movement (Bottom Columns):** Cards in the columns can be stacked in descending order, strictly **alternating in color** (e.g., place a Red 6 on top of a Black 7).
3.  **Empty Columns:** If a column on the tableau becomes completely empty, only a **King (K)** (or a valid sequence starting with a King) can be placed into that empty slot.
4.  **Stock & Waste Pile:** Tap or click the face-down Stock pile in the top left to draw cards into the Waste pile based on your selected difficulty draw count. Infinite recycling of the stock pile is enabled.

---

## 🛠️ Technology Stack
*   **HTML5** - Clean semantic structural setup and accessible UI layout.
*   **CSS3** - Customized interactive modals, responsive grid sizing, custom CSS variables, keyframe animations, and mobile layout breakpoints.
*   **Vanilla JavaScript (ES6)** - Difficulty deck distribution algorithms, touch event listener implementations, client-side state history tracking, local storage synchronization, JSON backup handlers, and Web Audio API synthesis.

---
Published by **EMENES INTERACTIVE** | Stable Release Version (2026)
