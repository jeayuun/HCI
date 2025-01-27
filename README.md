[![LICENSE](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

<h1 align="center">Building Sinta 🍃</h1>
<h2 align="center">Group 2: HCI Final Project</h2>

> A tower-building game based on ES6 and Canvas. (Guess which building in PUP, char!)

<p align="center">
  <img src="sneakpeek.png" alt="Sneak Peek of Building Sinta"/>
</p>

---

## 🎮 Game Rules

Here are the default game rules for **Building Sinta**:

- **Starting Health Points (HP)**: Every player begins the game with **3 HP**. 
  - If a tower block is dropped and doesn't stack, **1 HP is deducted**. 
  - The game ends when all HP are depleted.

- **Scoring System**:
  - **Success**: When a block is successfully stacked on top of another, the player is rewarded with **25 points**.
  - **Perfect**: If a block is stacked perfectly aligned with the block below, the player is rewarded with **50 points**.
  - **Combo Bonus**: Consecutive **Perfect** stacks reward an **additional 25 points per combo**. 
    - For example:
      - The first Perfect stack awards **50 points**.
      - The second consecutive Perfect awards **75 points**.
      - The third consecutive Perfect awards **100 points**, and so on.

**Note**: Each Success or Perfect stack is equivalent to building a floor for your tower.

---

## 🚀 How to Play Locally

To run the game locally on your machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/jeayuun/HCI.git
   cd HCI
   npm install
   npm start
   ```
Open `http://localhost:8082` in a web browser.

## License

MIT license.
