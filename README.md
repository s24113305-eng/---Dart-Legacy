# 🎯 Dart Legacy - Ultimate Edition

A fun, carnival-themed balloon dart game built with HTML5, CSS3, and vanilla JavaScript. No external dependencies required!

![Dart Legacy Banner](https://img.shields.io/badge/Version-Ultimate%20Edition-gold?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 🎮 Game Modes

### 🎪 Classic Mode
- **25 Darts** to pop as many balloons as possible
- **72 Balloons** on a rotating dartboard
- All power-ups available
- Price: NT$ 25

### ⏱️ Time Attack Mode
- **60 Seconds** race against the clock
- **3 Lives** - don't hit bombs!
- Many bombs to avoid
- Price: NT$ 35

### ⚔️ VS Mode (2 Players)
- **10 Darts** per player
- **1 Minute** match duration
- **Static dartboard** (no rotation)
- **Color-based scoring:**
  - 🔴 Player 1 scores on RED balloons (Spacebar to throw)
  - 🔵 Player 2 scores on BLUE balloons (Mouse click to throw)
  - Hit opponent's color = lose 1 dart!
- Special balloons:
  - 💣 Bomb = Lose 1 dart
  - ❄️ Freeze = Freeze opponent for 5 seconds
- Price: NT$ 50

## 🎈 Balloon Types

| Balloon | Effect |
|---------|--------|
| 🎈 Normal (Colored) | +5, +10, or +15 points |
| 🌟 Gold (20) | +20 points |
| ⭐ Star | Chain bonus! |
| ❄️ Freeze | Freezes dartboard rotation |
| 2️⃣ Multiplier | Score multiplier |
| 💣 Bomb | -30 points / Lose 1 life |

## 🏆 Prize Tiers

| Tier | Points | Prize |
|------|--------|-------|
| 🥇 Grand Champion | 1000+ | Giant Teddy Bear + VIP Pass |
| 🥈 Gold Winner | 500+ | Large Stuffed Animal |
| 🥉 Silver Star | 250+ | Medium Plush Toy |
| 🎖️ Bronze Player | 100+ | Small Prize + Candy |
| 🎫 Participant | 0+ | Consolation Candy |

## 🎯 Controls

### Classic & Time Attack Mode
- **Move mouse** - Aim at balloons
- **Hold mouse button** - Charge throw power
- **Release mouse button** - Throw dart

### VS Mode
- **Player 1:** Press and hold **Spacebar** to charge, release to throw
- **Player 2:** Press and hold **Mouse button** to charge, release to throw

## 🌐 Languages

The game supports two languages:
- 🇺🇸 **English**
- 🇹🇼 **中文 (Traditional Chinese)**

Click the language buttons at the top of the main menu to switch.

## 🚀 Getting Started

### Option 1: Play Directly
Simply open `index.html` in any modern web browser!

### Option 2: Host on GitHub Pages
1. Fork this repository
2. Go to Settings > Pages
3. Select "main" branch and save
4. Your game will be live at `https://[username].github.io/dart-legacy-ultimate/`

### Option 3: Local Development
```bash
# Clone the repository
git clone https://github.com/[username]/dart-legacy-ultimate.git

# Navigate to the directory
cd dart-legacy-ultimate

# Open in browser (macOS)
open index.html

# Or use a local server
python -m http.server 8000
# Then visit http://localhost:8000
```

## 📁 Project Structure

```
dart-legacy-ultimate/
├── index.html          # Main game file (all-in-one HTML/CSS/JS)
├── capybara-balloon.png # Capybara mascot image
├── README.md           # This file
└── LICENSE             # MIT License
```

## ✨ Features

- 🎨 Beautiful carnival-themed UI with animations
- 🎵 Sound effects (Web Audio API)
- 📱 Responsive design
- 🎯 Realistic dart throwing physics
- 🔄 Rotating dartboard mechanics
- 💥 Particle effects and confetti
- 🎪 Animated tutorial with capybara mascot
- 🌙 Smooth transitions and hover effects

## 🛠️ Technical Details

- **Pure HTML5/CSS3/JavaScript** - No frameworks or build tools needed
- **Web Audio API** for sound effects
- **CSS Animations** for smooth visual effects
- **Responsive Design** works on desktop and mobile
- **Single File Architecture** - Everything in one HTML file for easy deployment

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Credits

- Game Design & Development: J.M.O 2025
- Capybara Mascot Art: Custom designed
- Inspired by classic carnival dart games

## 🐛 Known Issues

- Sound may not play on mobile until user interacts with the page (browser security)
- Best experienced on desktop browsers

## 🔮 Future Ideas

- [ ] Online multiplayer mode
- [ ] Leaderboard system
- [ ] More game modes
- [ ] Custom themes
- [ ] Achievement system

---

Made with ❤️ and 🎯

**Enjoy popping balloons!** 🎈🎉
