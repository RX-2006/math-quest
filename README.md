# 🎮 Math Quest: The Arithmetic Adventure

> A gamified educational web application that transforms traditional arithmetic learning into an engaging, interactive adventure.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Yes-10b981?style=flat)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat)

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [Getting Started](#-getting-started)
- [Game Mechanics](#-game-mechanics)
- [Assessment Requirements](#-assessment-requirements)
- [Technologies Used](#-technologies-used)
- [Project Structure](#-project-structure)
- [Future Enhancements](#-future-enhancements)
- [Author](#-author)
- [License](#-license)

---
<p align ="center">
<img src="maths quest dashboard.png" height=500px>
</p>

## 🎯 Overview

**Math Quest** is a single-player educational game designed to teach fundamental arithmetic concepts - Addition, Subtraction, Multiplication, and Division - through an immersive, game-based learning experience.

Built entirely with vanilla **HTML5, CSS3, and JavaScript**, the application requires no external dependencies, build tools, or server setup. Simply open the file in any modern web browser and start playing!

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🔐 **Login / Player Name Screen** | Personalized hero name entry with localStorage persistence |
| 🎯 **Mission Selection** | 4 themed arithmetic realms to explore |
| 📊 **Level System** | 3 difficulty tiers per mission (Easy → Medium → Hard) with progressive unlocking |
| ⭐ **Experience (XP) Points** | Earned per correct answer + streak bonuses + time bonuses |
| 🪙 **Coins** | Awarded based on performance; bonus for perfect scores |
| 🏅 **Badges** | 5 unlockable achievement badges |
| 📈 **Progress Bar** | Visual real-time progress indicator during gameplay |
| ⏱️ **Timer** | Countdown per level with visual warnings |
| 🏆 **Scoreboard** | Hall of Fame with global rankings |
| 📜 **Final Certificate** | Printable achievement certificate with player stats |

---

## 📸 Screenshots

### 🏠 Login Screen
Hero name entry with a vibrant, welcoming interface.

### 🗺️ Dashboard
Player stats bar, badge collection, and mission selection grid.

### 🎮 Gameplay
Timed arithmetic questions with multiple-choice answers, streak counter, and progress tracking.

### 🎉 Level Complete
Reward summary with XP, coins, stars, and new badge notifications.

### 📜 Certificate
Printable achievement certificate with personalized stats.

---

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Edge, Safari)
- No server, build tools, or dependencies required!

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/math-quest.git

# 2. Navigate to the project folder
cd math-quest

# 3. Open the file in your browser
# Option A: Double-click index.html
# Option B: Use a live server extension in VS Code
```

### Or simply:
1. Download `index.html`
2. Double-click to open in your browser
3. Enter your hero name and start the adventure!

---

## 🎲 Game Mechanics

### Missions
| Mission | Icon | Description | Operations |
|---------|------|-------------|------------|
| Addition Adventure | ➕ | Master the art of summing numbers | `a + b` |
| Subtraction Safari | ➖ | Navigate through differences | `a - b` |
| Multiplication Mountain | ✖️ | Climb to peak products | `a × b` |
| Division Dungeon | ➗ | Conquer the quotient caves | `a ÷ b` |

### Difficulty Levels
| Level | Questions | Time Limit | Number Range |
|-------|-----------|------------|--------------|
| 🌱 Easy | 5 | 60 seconds | 1 – 10 |
| 🌿 Medium | 7 | 45 seconds | 1 – 20 |
| 🌳 Hard | 10 | 30 seconds | 1 – 50 |

### Scoring System
- **Base XP**: +10 per correct answer
- **Streak Bonus**: +2 XP per consecutive correct answer (max +10)
- **Time Bonus**: +1 XP per 5 seconds remaining
- **Coins**: XP ÷ 5 + 10 bonus for 100% accuracy
- **Stars**: ⭐⭐⭐ (100%) | ⭐⭐ (≥70%) | ⭐ (≥40%)

### Badges
| Badge | Icon | Unlock Condition |
|-------|------|------------------|
| First Steps | 👣 | Complete your first level |
| Speed Demon | ⚡ | Complete a level in under 30 seconds |
| Perfect Score | 💯 | Get 100% accuracy on any level |
| Coin Collector | 🪙 | Collect 50 coins total |
| Math Master | 👑 | Complete all 12 levels |

---

## ✅ Assessment Requirements

This project was developed as part of a **CALTech Assessment** to gamify a traditional learning activity. All required features have been implemented:

- [x] Login / Player Name screen
- [x] Mission selection
- [x] Level system (Easy, Medium, Hard)
- [x] Experience (XP) points
- [x] Coins / Stars
- [x] Badges (5 unlockable achievements)
- [x] Progress bar
- [x] Timer (with visual warnings)
- [x] Scoreboard (Hall of Fame)
- [x] Final certificate (printable)

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic structure and content |
| **CSS3** | Styling, animations, gradients, responsive design |
| **JavaScript (ES6+)** | Game logic, state management, DOM manipulation |
| **localStorage API** | Player progress persistence |
| **CSS Animations** | Bounce, shake, pulse, fade effects |
| **CSS Grid & Flexbox** | Responsive layouts |
| **CSS Variables** | Theming and consistent design tokens |

---

## 📁 Project Structure

```
math-quest/
│
├── index.html          # Single-file application (HTML + CSS + JS)
├── README.md           # Project documentation
└── .gitignore          # Git ignore rules (optional)
```

> **Note:** The entire application is contained in a single `index.html` file for maximum portability and zero dependencies.

---

## 🔮 Future Enhancements

- [ ] Sound effects and background music
- [ ] Additional math topics (fractions, decimals, algebra)
- [ ] Multiplayer leaderboard with backend
- [ ] Dark mode toggle
- [ ] Mobile app version (PWA)
- [ ] Customizable avatar system
- [ ] Daily challenges and streak rewards
- [ ] Teacher dashboard for classroom tracking

---

## 👤 Author

**Your Name**
- 🎓 CALTech Student
- 📧 your.email@example.com
- 🔗 [GitHub](https://github.com/YOUR_USERNAME)

---

## 📄 License

This project is licensed under the **MIT License** - feel free to use, modify, and distribute.

```
MIT License

Copyright (c) 2026 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

<div align="center">

### 🌟 Star this repo if you found it helpful!

**[⬆ Back to Top](#-math-quest-the-arithmetic-adventure)**

</div>
