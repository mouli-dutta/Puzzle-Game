# 🚀 Space Puzzle - Astronaut's Journey to Earth

A premium 3D web-based puzzle game built with vanilla JavaScript and Three.js where you guide an astronaut through space to reach Earth.

## ⚡ Quick Start (No Installation Required!)

1. **Double-click** `index.html`
2. **Play!** The game opens in your browser immediately

That's it! No Node.js, no npm, no installation needed.

## 🎮 Game Mechanics

### Objective
Move the orange Astronaut tile to the Earth tile (🌍) to complete each level.

### Rules
- **Movement**: Use Arrow Keys or WASD to move in four directions (Up, Down, Left, Right)
- **Stopping**: Tiles can only stop when they collide with another Astronaut or Alien tile
- **Danger**: If a tile moves without hitting another tile, it falls off the board and is lost forever!
- **Strategy**: Use Alien tiles strategically as stoppers to navigate safely

### Controls
- **Arrow Keys / WASD** - Move the astronaut
- **U / Z** - Undo last move
- **R** - Reset current level
- **ESC** - Pause game

## 🌟 Features

- **20 Challenging Levels** - Progressive difficulty from 4x4 to 8x8 boards
- **Premium 3D Graphics** - Built with Three.js (via CDN)
- **Visual Effects** - Bloom, glowing tiles, and smooth animations
- **Sound Effects** - Web Audio API beeps (no files needed)
- **Star Rating System** - Earn up to 3 stars based on move efficiency
- **Progress Saving** - Your progress is automatically saved to browser
- **Responsive Design** - Works on desktop and mobile devices
- **Single File** - Everything in one HTML file, easy to share

## 🌐 Browser Requirements

Works in all modern browsers:
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Edge 90+
- ✅ Safari 14+

**Requirements:**
- WebGL support (for 3D graphics)
- JavaScript enabled
- Internet connection (first load only, for CDN libraries)

## 📦 Tech Stack

- **Vanilla JavaScript** - No frameworks needed
- **Three.js** - 3D graphics engine (via CDN)
- **TailwindCSS** - Styling (via CDN)
- **Web Audio API** - Sound effects (built-in browser API)

## 📁 File Structure

```
Puzzle Game/
├── index.html              # The complete game - just open this!
├── README.md              # This file
└── VANILLA-QUICKSTART.txt # Quick reference guide
```

That's it! The entire game is in `index.html`.

## 🎯 Level Design

- **Levels 1-5**: 4x4 boards, simple paths (Tutorial)
- **Levels 6-10**: 5x5 boards, moderate complexity
- **Levels 11-15**: 6x6 boards, complex puzzles
- **Levels 16-20**: 7x7-8x8 boards, expert challenges

## 🏆 Star Rating

- ⭐⭐⭐ 3 Stars: Complete in ≤5 moves
- ⭐⭐ 2 Stars: Complete in ≤10 moves
- ⭐ 1 Star: Complete in >10 moves

## � Customization

Want to modify the game? Just edit `index.html`:

### Add More Levels
Find the `LEVELS` array (around line 250) and add new level objects.

### Change Colors
Find the `ALIEN_COLORS` array (around line 280) and modify hex colors.

### Adjust Difficulty
Modify the `calculateStars()` function to change star requirements.

All the code is in one file, making it easy to customize!

## 🐛 Troubleshooting

### Game doesn't load
- Check internet connection (needed for CDN libraries on first load)
- Try a different browser
- Clear browser cache (Ctrl+Shift+Delete)

### 3D graphics not working
- Update your browser to the latest version
- Check if WebGL is enabled (visit: https://get.webgl.org/)
- Try disabling browser extensions

### Performance issues
- Close other browser tabs
- Disable browser extensions
- Try a different browser (Chrome/Firefox recommended)

### Progress not saving
- Check if cookies/localStorage are enabled
- Don't use private/incognito mode

## 📝 License

This project is open source and available for personal and educational use.

## 🤝 Contributing

Feel free to fork this project and add your own levels or features!

## 🎮 Enjoy the Game!

Guide the astronaut safely through space and bring them home to Earth! 🌍👨‍🚀
