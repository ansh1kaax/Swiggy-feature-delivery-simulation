#  Game Feature Requirement – Swiggy Feature Delivery Simulation

##  Feature Goal
The mini-games are designed to:
- Increase user engagement during order wait time
- Encourage users to return to the app (retention)
- Reward users with Swag Coins and coupons
- Reduce perceived delivery wait time by adding fun interaction

---

##  Placement

| Location | Description |
|----------|-------------|
| **Home Screen** | A clearly visible **Fun Zone** button at the top of the home page |
| **Post-Order Page** | Users are prompted with a playful invite to "join 10,000+ people playing while waiting" |

---

##  Game Types

| Game Name     | Description                |
|--------------|----------------------------|
| **Hangman**   | Classic word guessing game |
| **Spin-the-Wheel** | Rewards-based spinner |
| **Tic-Tac-Toe** | Multiplayer or bot-based  |
| **Dot and Line** | Simple connect-the-dots logic game |

---

##  Play Rules & Frequency

- ✅ Games can be played anytime.
- ✅ Games appear once per order placement but are replayable for fun.
- ❗ Cooldown is only applied to **Spin-the-Wheel** (to avoid reward farming).
- ❗ Limit of **5,000 Swag Coins/day** per user.

---

##  Reward System

| Action/Trigger | Reward Logic |
|----------------|--------------|
| Winning a game | Earn Swag Coins (points) |
| Daily Limit    | Max 5,000 coins per day |
| Redemption     | 
- 25,000 coins → ₹25 OFF  
- 50,000 coins → Free Delivery  

Internal logic ensures rewards are not too easy to farm.

---

##  UI/UX Integration

- Matches Swiggy color palette, typography, and branding.
- Fun, clean visuals with animations and light sound effects.
- Encouraging, playful tone (e.g., “Feeling lucky?” or “Let’s outplay your hunger!”).
- Game count and player stats (e.g., “10,000 users playing now”).

---

##  Technology Stack

| Tech Area     | Choice                   |
|---------------|--------------------------|
| Game Engine   | **HTML5 (Phaser.js)** for lightweight web-based games |
| Embedding     | Games embedded inside iOS app using WebView |
| Compatibility | iOS-only (for now), simulated with prototypes |
| Simulation    | Static/animated Figma or HTML mockups |

---

##  Privacy & Tracking

| Aspect         | Implementation |
|----------------|----------------|
| Data Logging   | Track only **game engagement** (played, won, time spent) |
| User Data      | No personal user data collected |
| Toggle Option  | Game experience is optional (user can opt out or close the screen) |

---

##  Summary

-  Games are strategic tools for retention and fun
-  Engaging design with familiar gameplay
-  Replayable, not reward-abusive
-  Non-intrusive and privacy-aware

