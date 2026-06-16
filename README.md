# 🚀 Space Puzzle - Astronaut's Journey to Earth

A premium 3D web-based puzzle game built with vanilla JavaScript and Three.js where you guide an astronaut through space to reach Earth. Features stunning 3D graphics, 12 challenging levels, a coin & hint system, and full mobile/tablet support!

## ⚡ Quick Start (No Installation Required!)

1. **Double-click** `index.html`
2. **Play!** The game opens in your browser immediately

That's it! No Node.js, no npm, no installation needed.

## 🎮 Game Description

**Space Puzzle** is a strategic sliding puzzle game set in the depths of space. You control an astronaut who must navigate across floating platforms to reach Earth. The catch? Once you move in a direction, you keep sliding until you hit another tile or fall off the edge into the void!

Use colorful alien tiles as stoppers to create safe paths. Plan your moves carefully, collect coins, and use hints when you're stuck. With 12 hand-crafted levels ranging from simple 4x4 grids to complex 8x8 boards, each puzzle requires strategic thinking and spatial awareness.

## 🎯 Game Mechanics

### Objective
Move the 👨‍🚀 **Astronaut** (orange tile) to the 🌍 **Earth** tile to complete each level.

### Core Rules
1. **Sliding Movement**: When you move, tiles slide continuously until they hit an obstacle
2. **Stoppers**: Tiles stop when they collide with another tile (astronaut or alien) or the board edge
3. **Danger Zone**: If a tile slides off the edge without hitting anything, it falls into space forever!
4. **Multiple Characters**: Click to select the astronaut or any alien, then move the selected tile
5. **Strategic Planning**: Use alien tiles as stoppers to create safe paths for the astronaut

### Controls

#### 🖥️ Desktop Controls
- **Arrow Keys / WASD** - Move selected tile (camera-relative)
- **Mouse Click** - Select astronaut or alien tiles
- **U / Z** - Undo last move
- **R** - Reset current level
- **ESC** - Deselect tile
- **+ / -** - Zoom in/out (or scroll wheel)
- **Mouse Drag** - Rotate camera view

#### 📱 Mobile/Tablet Controls
- **Tap Tile** - Select astronaut or alien
- **Arrow Buttons (↑↓←→)** - Move selected tile
- **💡 Button** - Get hint (costs 1 coin)
- **↶ Button** - Undo last move
- **⟳ Button** - Reset level
- **📋 Button** - Level select menu
- **Pinch Gesture** - Zoom in/out
- **Drag** - Rotate camera view

#### 🎮 Advanced Controls
- **Click/Tap Level Info** - Collapse/expand level details (mobile)
- **Scroll/Pinch** - Zoom camera for better view
- **Rotate Camera** - Drag to view board from different angles

## 📖 How to Play

### Getting Started
1. **Launch the Game** - Open `index.html` in your browser
2. **Read Instructions** - Click the "📖 INSTRUCTIONS" button on the main menu
3. **Start Playing** - Click "START GAME" to begin

### Step-by-Step Gameplay

#### Level Start
1. Observe the board layout - identify the astronaut (orange), aliens (colorful), and Earth (blue)
2. Plan your route - figure out which aliens to use as stoppers
3. Click/tap to select the astronaut (yellow ring appears)

#### Making Moves
1. **Desktop**: Press arrow keys or WASD to move
2. **Mobile**: Tap the on-screen arrow buttons (↑↓←→)
3. The selected tile slides until it hits another tile or the board edge
4. If it slides off the edge, it's lost forever - level failed!

#### Using Aliens as Stoppers
1. Click/tap an alien to select it
2. Move the alien to create a "stopper" position
3. Now move the astronaut - it will stop when it hits the alien
4. Repeat strategically to create a safe path to Earth

#### Winning
1. Navigate the astronaut to the Earth tile
2. Earn stars based on move efficiency (fewer moves = more stars)
3. Collect 1 coin for completing the level (first time only)
4. Proceed to the next level or replay for better stars

### 🪙 Coin & Hint System

#### Earning Coins
- Complete any level for the first time: **+1 coin**
- Coins are saved permanently in your browser
- Maximum coins: Unlimited!

#### Using Hints
- Cost: **1 coin per hint**
- Limit: **3 hints per level**
- How it works:
  1. Click the 💡 button (top-left on mobile, top-right on desktop)
  2. The game uses AI (BFS solver) to find the optimal solution
  3. You'll see a hint like: "Move the purple alien left"
  4. Follow the hint to progress toward the solution

#### Hint Strategy
- Save coins for harder levels (6x6, 7x7, 8x8 boards)
- Use hints when completely stuck
- Try to solve without hints for the challenge!

## 🌟 Features

- **12 Challenging Levels** - Progressive difficulty from 4x4 to 8x8 boards
- **Premium 3D Graphics** - Built with Three.js (via CDN)
- **Coin & Hint System** - Earn coins, get intelligent hints when stuck
- **Visual Effects** - Bloom, glowing tiles, smooth animations, shooting stars
- **Sound Effects** - Web Audio API beeps (no files needed)
- **Star Rating System** - Earn up to 3 stars based on move efficiency
- **Progress Saving** - Your progress is automatically saved to browser
- **Fully Responsive** - Optimized for desktop, tablet, and mobile
- **Touch Controls** - On-screen arrow buttons for mobile/tablet
- **Camera Controls** - Rotate, zoom, and view from any angle
- **Collapsible UI** - Clean interface with collapsible level info
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

- **Levels 1-2**: 4x4 boards - Tutorial levels, learn the basics
- **Levels 3-4**: 5x5 boards - Intermediate difficulty
- **Levels 5-6**: 6x6 boards - Moderate complexity
- **Levels 7-11**: 7x7-8x8 boards - Advanced challenges
- **Level 12**: 6x6 board - Final challenge (Gravity Well)

### Difficulty Progression
- **Easy (1-3)**: Learn sliding mechanics and basic strategy
- **Medium (4-6)**: Multiple aliens, complex paths
- **Hard (7-9)**: Large boards, precise planning required
- **Expert (10-12)**: Maximum complexity, all skills tested

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
