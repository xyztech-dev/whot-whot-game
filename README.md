# 🃏 Whot! Cyber Arcade Edition

An interactive, single-file implementation of the classic Nigerian **Whot** card game, engineered with a modern cyberpunk aesthetic and a smart player-vs-bot game engine. 

🔗 **Live Demo:** [https://xyztech-dev.github.io/whot-card-game/](https://xyztech-dev.github.io/whot-card-game/)

---

## 🚀 Key Features

* **Full Deck Mechanics:** Includes all standard suits—Circle ⭕, Triangle 🔺, Cross ✖️, Square ⬛, Star ⭐️—along with standard numbered cards and the powerful **Whot 20** wild cards.
* **Interactive Action Card Rules:**
  * **Hold On (1):** Play again immediately.
  * **Pick Two (2) & Pick Three (5):** Forces your opponent to draw cards and skip their turn.
  * **Suspension (8):** Skips the opponent's turn.
  * **General Market (14):** Forces the opponent to draw a card and skip their turn.
  * **Whot (20):** Dynamic suite selector modal allowing you to declare your desired suit (the Bot AI handles this automatically based on its hand distribution).
* **Smart Bot AI:** An autonomous opponent that scans its hand for valid plays, strategically prioritizes non-action cards, automatically declares suits when playing Whot 20 cards, and draws from the deck when no valid options exist.
* **Cyberpunk Aesthetic:** Designed with custom neon color variables, glassmorphism UI containers, responsive touch handling for mobile devices, and real-time game logs.

---

## 🛠️ Built With

* **HTML5** – Semantic layout, modals, and interface structure.
* **CSS3** – Custom flexbox layouts, neon glow variables, suit styling, and smooth card transition effects.
* **Vanilla JavaScript (ES6+)** – Deck generation, shuffling algorithms, turn-based state management, action-card logic loops, and bot decision-making routines.
* **GitHub Pages** – Zero-cost, instantaneous static web hosting.

---

## 📂 Project Structure

```text
whot-card-game/
│
├── index.html       # Complete application (Markup, Styling, and Game Engine Logic)
└── README.md        # Project documentation and details
