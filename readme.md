# 🚀 Rocket Multiplier Web Game

A web-based Rocket game inspired by DraftKings Casino’s **Rocket**.  
Watch the rocket soar, the multiplier rise, and cash out before it explodes!  

Built with **HTML**, **CSS**, and **JavaScript** — no frameworks required.

---

## 🎮 Gameplay Overview

1. **Set Your Bet:**  
   Enter your desired bet amount in the input field.

2. **Launch:**  
   Click **Launch** to start the round. The rocket begins to ascend, and the multiplier increases from **1.00x** upward.

3. **Cash Out:**  
   Click **Cash Out** before the rocket explodes to secure your winnings.  
   - If you cash out at 3.42x, and your bet was $10 → You win **$34.20!**
   - If the rocket explodes before you cash out → You lose the bet.

4. **Random Explosion:**  
   The rocket explodes at a random multiplier between **1.00x and 100.00x**.  
   Each round’s outcome is unique and unpredictable.

5. **Reset:**  
   After the explosion or cash-out, the game resets automatically and lets you play again.

---

## ⚙️ Features

- 🎯 Real-time multiplier growth (smooth JS animation)  
- 💸 Cash-out system with live balance updates  
- 💥 Random explosion logic with fair randomness  
- 🌈 Animated background gradient as multiplier rises  
- 🔊 Optional sound effects for launch, cash-out, and explosion  
- 🏆 Optional leaderboard for highest multipliers  
- 🧠 Optional auto-cash-out feature (e.g., auto at 2.00x)

---

## 🧩 Tech Stack

- **HTML5** – structure and layout  
- **CSS3** – visual design, gradients, transitions  
- **JavaScript (ES6)** – game logic, multiplier engine, UI interactivity  

---

## 🛠️ How to Run

1. Clone or download this repository.  
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge).  
3. Play immediately — no setup required!

---

## 🧮 Game Logic Summary

- A random explosion multiplier is generated when the player clicks **Launch**.  
- The displayed multiplier increases by small increments (e.g., 0.01x) at short time intervals.  
- If the current multiplier reaches or exceeds the random explosion multiplier → the rocket explodes.  
- If the player cashes out before that happens → winnings are calculated and displayed.

---

## 🧠 Future Improvements

- Add backend tracking for high scores and balances  
- Implement multiplayer rounds with shared rocket timing  
- Integrate WebSocket or Firebase for real-time play  
- Create a mobile-friendly UI layout  
- Add authentication and user stats

---

## 🧑‍💻 Author

Developed by **Jonathan**  
Creative coder & tech enthusiast 💻✨

---

## ⚠️ Disclaimer

This project is for **educational and entertainment purposes only**.  
It is **not** a gambling application and **does not handle real money**.

---
