# Kid Game Studio 🎮

Educational games for kids ages 4-6, built with HTML, JavaScript, Bootstrap, and Font Awesome.

## 🌟 Reading Adventure

A complete learning journey for young readers with 3 progressive levels:

### Level 1: Learn Your ABCs
- Letter recognition with fun visuals and audio
- Find letters A-Z among distractors
- Progress tracking through 26 letters

### Level 2: Count with Me
- Count colorful objects (1-10)
- Build number recognition
- Fun floating objects and animations

### Level 3: Build Simple Words
- Spell 3-letter words from scrambled letters
- 10 progressive words with hints
- Audio feedback for each letter

## ✨ Features

- **Confetti Celebrations** - 100 colorful pieces fall on completion
- **Sticker Collection** - Earn 10 unique stickers (one per star)
- **Reward Badges** - 5 rotating badges based on total stars
- **Text-to-Speech** - Every interaction spoken aloud
- **Progress Tracking** - Stars and levels auto-save to localStorage
- **Child-Friendly Design** - Large buttons, colorful gradients, fun animations
- **No Dependencies** - Pure HTML/CSS/JavaScript, works offline

## 🚀 Deployment

### Automatic CI/CD

This repository uses GitHub Actions for automatic deployment to GitHub Pages:

```yaml
# .github/workflows/deploy.yml
- Triggers on push to main
- Automatically deploys to GitHub Pages
- Zero configuration needed
```

### Live Site

The game is automatically deployed to GitHub Pages at:

**URL:** https://[username].github.io/kid-game-studio/

## 🎯 Tech Stack

- HTML5
- Vanilla JavaScript
- Bootstrap 5.3
- Font Awesome 6.4
- Web Speech API (for audio)

## 📁 Project Structure

```
kid-game-studio/
├── index.html                    # Landing page (NEW)
├── reading-adventure/
│   └── index.html             # Main game (self-contained)
├── counting-carnival/           # Archived (legacy)
├── letter-safari/               # Archived (legacy)
├── pizza-fractions/            # Archived (legacy)
├── word-builder/                # Archived (legacy)
├── .github/
│   └── workflows/
│       └── deploy.yml        # CI/CD pipeline
└── [documentation files]
```

## 🧩 Documentation

- `READING-ADVENTURE.md` - Complete game guide and mechanics
- `REWARDS-UPDATE.md` - Rewards system documentation
- `IN-GAME-TEST.md` - In-game testing report
- `DEPLOYMENT-CHECKLIST.md` - Deployment verification checklist

## 🎮 How to Play

1. Open `reading-adventure/index.html`
2. Choose a level (ABCs, Counting, or Words)
3. Follow the on-screen instructions
4. Earn stars and collect stickers!

## 👨 Perfect for Ages 4-6

Designed specifically for children who:
- Know the alphabet
- Are starting to put letters together
- Can count to 10
- Benefit from visual and audio feedback

---

**Built with ❤️ for young learners**

*Educational · Fun · Engaging*
