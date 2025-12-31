# Battle Arena Simulation Engine

A turn-based combat simulation engine built in Python using Object-Oriented Programming (OOP) principles. Developed as part of a deep dive into game state management and data persistence.

## 🚀 Technical Highlights
- **OOP Architecture:** Utilizes class-based structures for `Soldier` and `Unit` management, ensuring modularity and scalability.
- **Algorithmic Progression:** Implemented a custom leveling system using an exponential growth factor (`XP_REQUIRED_INCREASE = 1.4`) to manage character scaling.
- **Data Persistence:** Integrated `JSON` handling to track, save, and retrieve cumulative battle statistics across separate execution sessions.
- **Logic Handling:** Engineered a turn-based loop with randomized damage calculations and win/loss state detection.

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Environment:** Developed on Fedora Linux using Neovim.
- **Libraries:** `json`, `time`, `random`.

## 📈 Future ML Roadmap
Planning to replace the `random` damage module with a **Probability Distribution** model to simulate "Expected Value" (EV) outcomes before combat initiation.
