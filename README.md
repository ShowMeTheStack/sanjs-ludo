# SANJS LUDO 🎲

A feature-rich, browser-based Ludo game with multiple game modes, AI opponents, and TV remote support. Play the classic Indian board game right in your browser!

![SANJS LUDO](https://img.shields.io/badge/Game-SANJS%20LUDO-gold)
![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red)

## 🎮 Play Now

Visit: **[ludo.jyotiprakash.org](https://ludo.jyotiprakash.org)**

## ✨ Features

### Game Modes

| Mode | Description |
|------|-------------|
| **4 Players** | Local multiplayer for 4 human players |
| **vs AI** | 1 human player vs 3 AI opponents |
| **Team Mode** | Red+Yellow vs Green+Blue (all human) |
| **Team vs AI** | You + AI teammate vs 2 AI opponents |
| **2P Diagonal** | Red vs Yellow - 2 player mode (human vs human) |
| **Diagonal vs AI** | Red (you) vs Yellow (AI) - quick 1v1 game |

### Game Options

| Option | Default | Description |
|--------|---------|-------------|
| **Release on 1 or 6** | ✅ On | Pieces can exit home base on rolling 1 or 6. Disable for classic rules (6 only) |
| **Show Capture Indicator** | ✅ On | Red blinking indicator shows cells where opponent pieces can be captured |
| **Lucky Dice** | ❌ Off | Weighted dice with higher chance of rolling numbers that lead to captures |

### Gameplay Features

- **Animated Token Movement** - Step-by-step animation as pieces move along the path
- **Capture Mechanics** - Land on opponent pieces to send them back to their home base
- **Safe Zones** - Star-marked cells where pieces cannot be captured
- **Bonus Rolls** - Roll again on getting a 6 or capturing an opponent
- **Three Sixes Rule** - Three consecutive 6s forfeit your turn (prevents infinite loops)
- **Auto-Move** - When only one valid move exists, it executes automatically
- **Smart AI** - AI opponents make strategic decisions based on capture opportunities, safety, and progress

### Visual Features

- **Royal Theme** - Elegant design with gold gradients and glowing effects
- **Color-Coded Dice** - Each player has their own dice in their corner with unique glow effects
- **Stacked Tokens** - Multiple pieces on the same cell stack neatly with count display
- **Finish Pile-Up** - Completed pieces pile up at each color's finish cell

### TV Remote / Keyboard Support

Perfect for playing on your TV! Full navigation support:

| Control | Action |
|---------|--------|
| **Arrow Keys** | Navigate between options, tokens, and buttons |
| **Enter / OK** | Roll dice, select token, confirm action |
| **Space** | Toggle checkboxes |

### Responsive Design

- Works on desktop, tablet, mobile, and TV browsers
- Board automatically scales to fit available screen space
- Side panel moves below the board on narrow screens

## 🎯 How to Play

1. **Choose a game mode** from the home screen
2. **Configure options** (release rules, capture indicator, lucky dice)
3. **Roll the dice** by clicking/tapping your dice or pressing Enter
4. **Move a piece** by clicking on a highlighted token
5. **Capture opponents** by landing on their pieces (except on safe zones)
6. **Get all 4 pieces home** to win!

### Rules

- Roll a **1 or 6** to release a piece from home (or just 6 in classic mode)
- Rolling **6** grants a bonus roll
- **Capturing** an opponent grants a bonus roll
- Three consecutive **6s** skip your turn
- Pieces are **safe** on star-marked cells and colored start positions
- First player to get all 4 pieces to the finish wins!

## 🎨 Board Layout

```
┌─────────────────────────────────────┐
│  RED HOME    │ PATH │  GREEN HOME   │
│              │      │               │
│   (spawn)    │  ↓   │    (spawn)    │
├──────────────┼──────┼───────────────┤
│    PATH  →   │CENTER│   ← PATH      │
├──────────────┼──────┼───────────────┤
│  BLUE HOME   │ PATH │  YELLOW HOME  │
│              │  ↑   │               │
│   (spawn)    │      │    (spawn)    │
└─────────────────────────────────────┘
```

## 🔧 Technical Details

- **Pure HTML/CSS/JavaScript** - No frameworks or dependencies
- **Single File** - Everything in one `index.html` file
- **No Backend** - Runs entirely in the browser
- **No Data Collection** - Your game stays on your device

## 📜 License

**© 2025 Jyotiprakash Mishra. All Rights Reserved.**

This code is provided for **observation purposes only**. 

See [LICENSE](LICENSE) for full terms.

### You MAY NOT:
- Use this code in any project
- Modify or create derivative works
- Distribute or sell this code
- Use this code for commercial purposes
- Copy substantial portions of this code
- Fork or clone this repository

### You MAY:
- View and read the source code
- Learn from the implementation techniques
- Play the game at [ludo.jyotiprakash.org](https://ludo.jyotiprakash.org)

## 👤 Author

**Jyotiprakash Mishra**

---

*Made with ❤️ for family game nights*
