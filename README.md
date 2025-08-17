# 🍦 Ice Cream Hustle Game

A fun browser-based game where you catch falling items while avoiding police sirens! Built with HTML5 Canvas, JavaScript, and Web Audio API.

## 🎮 How to Play

- **Controls**: Use mouse/touch or arrow keys (A/D) to move the ice cream cone
- **Objective**: Catch the good items (X, €100 bills, Rolex watches)
- **Avoid**: Police sirens 🚨 (they give you strikes)
- **Time Limit**: 60 seconds to score as many points as possible!
- **Lives**: You have 3 strikes before game over

## 🎵 Features

- **Crimson Aura Visual Theme** - Beautiful red gradient background
- **Looping Background Music** - PERCO.mp3 soundtrack
- **Realistic Sound Effects** - Procedural audio for all game events
- **Responsive Design** - Works on desktop, tablet, and mobile
- **Touch & Keyboard Controls** - Multiple input methods
- **Volume Controls** - Separate sliders for music and SFX
- **Pause Function** - Press P or click pause button

## 🚀 Play Now

[Play the game here](https://wearenextgen.github.io/IceCreamHustle/)

## 🛠️ Technologies Used

- **HTML5 Canvas** - Game rendering
- **JavaScript (ES6+)** - Game logic and mechanics
- **Web Audio API** - Sound effects and music
- **CSS3** - Styling with custom properties
- **PNG Assets** - All game sprites and backgrounds

## 📁 Project Structure

```
IceCreamHustle/
├── ice_cream_hustle_working.html  # Main game file
├── PERCO.mp3                      # Background music
├── background.png                 # Crimson aura background
├── cone.png                       # Ice cream cone sprite
├── x.png                          # X item sprite
├── hundo.png                      # €100 bill sprite
├── rolex.png                      # Rolex watch sprite
├── siren.png                      # Police siren sprite
├── .gitignore                     # Git ignore rules
└── README.md                      # This file
```

## 🎯 Game Mechanics

### Scoring System
- **X Items**: 2 points each
- **€100 Bills**: 5 points each  
- **Rolex Watches**: 10 points each
- **Missed Items**: -5 points penalty

### Difficulty Progression
- Speed increases every 15 seconds
- Spawn rate increases over time
- Multiple items can spawn simultaneously

### Sound Effects
- **tap**: Button click sounds
- **pop**: Ice cream scoop sounds
- **plop**: Dropping sounds
- **squirt**: Ice cream squirting
- **ching**: Money/coin sounds
- **sniff**: Disappointment sounds
- **bling**: Luxury item sparkles
- **buzzer**: Warning sounds
- **siren**: Police siren tones

## 🌐 Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

## 📱 Mobile Support

- Touch controls
- Responsive canvas scaling
- Optimized for portrait orientation
- Touch-friendly UI elements

## 🔧 Development

To run locally:

1. Clone the repository:
```bash
git clone https://github.com/wearenextgen/IceCreamHustle.git
cd IceCreamHustle
```

2. Start a local server:
```bash
python3 -m http.server 8000
# or
npx http-server -p 8000
```

3. Open `http://localhost:8000/ice_cream_hustle_working.html`

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Contact

- **Developer**: Ivan Greko
- **Repository**: [https://github.com/wearenextgen/IceCreamHustle](https://github.com/wearenextgen/IceCreamHustle)

---

**Enjoy the game!** 🍦🎮
