# Ship of Theseus RPG – Interactive Philosophical Adventure

An interactive, browser-based role-playing game built entirely with **HTML, CSS, and JavaScript** that explores the classic **Ship of Theseus paradox** — a thought experiment about identity, change, and continuity.  
Players manage and maintain a virtual ship, deciding whether to repair or replace its parts as they degrade over time, all while facing philosophical and practical consequences.

---

## Features

- **Interactive Gameplay:** Replace or repair ship parts as they wear down.  
- **Philosophical Choices:** Encounter random events that challenge your beliefs about identity and existence.  
- **Resource Management:** Balance funds, crew morale, and reputation.  
- **Animated Interface:** Smooth ship-floating, water-wave, and glowing effects purely in CSS.  
- **Dynamic Philosophy Meter:** Tracks your philosophical stance — *Ship of Tradition*, *Ship of Change*, or *Ship in Balance*.  
- **Captain’s Log:** Records your decisions and their outcomes.  
- **Multiple Endings:** Achieve victory by surviving 30 days or face ruin if funds or ship condition fail.

---

## Gameplay Overview

1. **Start the Game:**  
   Open the `theseus2.html` file in any modern web browser (no setup required).

2. **Maintain Your Ship:**  
   - Each ship part (Hull, Mast, Sails, Deck, Bow, Cabin) has a condition percentage.  
   - You can **repair** (costs 100 coins) or **replace** (costs 200 coins) parts.  
   - Replacing parts raises philosophical points but lowers originality.

3. **Progress Through Days:**  
   - Click **“Next Day”** to advance time.  
   - Each day costs funds and may trigger random events such as storms, merchants, or philosophers.  

4. **Philosophical Events:**  
   - Respond to moral dilemmas that influence your ship’s identity and crew reputation.

5. **Winning or Losing:**  
   - Survive **30 days** with your ship in good condition to win.  
   - Lose if funds reach zero or ship condition drops too low.

---

## Technical Details

- **Language:** HTML5, CSS3, JavaScript (Vanilla)  
- **Dependencies:** None (no frameworks required)  
- **Responsive:** Fully playable on desktop and mobile browsers  
- **Animation:** Implemented via CSS keyframes and transitions  
- **Architecture:**  
  - The `ShipOfTheseusRPG` class handles all game logic.  
  - Dynamic rendering with DOM manipulation (no external libraries).  
  - Data stored in JavaScript objects for simplicity.

---

## Key UI Elements

| Component | Description |
|------------|-------------|
| **Ship Visualization** | Clickable ship parts that reflect condition and identity |
| **Identity Meter** | Shows percentage of original ship remaining |
| **Stats Panel** | Displays day, funds, reputation, and philosophy |
| **Captain’s Log** | Chronicles major events and decisions |
| **Philosophy Panel** | Explains the paradox and viewpoints (Materialist, Functionalist, Experientialist) |

---

## Philosophical Background

The **Ship of Theseus** paradox questions whether an object that has all its components replaced remains fundamentally the same object.  
This game brings that thought experiment to life — will your ship remain the same, or become something new entirely?

---

## How to Run

1. Download or clone the project folder.  
2. Open the file `theseus2.html` in your browser.  
3. No installation or server required.

---

## Author

**Project Title:** Ship of Theseus RPG  
**Created with:** HTML, CSS, and Vanilla JavaScript  
**Concept Focus:** Philosophical thought experiment through interactive simulation.

---

## Future Improvements

- Add background music and sound effects.  
- Implement save/load functionality using localStorage.  
- Add more random events and ship upgrades.  
- Include difficulty levels (Easy/Hard).  
- Support multiple endings based on philosophical alignment.
