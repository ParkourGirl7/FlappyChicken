# Flappy Chicken Game 🐔

A fun and addictive Flappy Bird-style game featuring a cute chicken character!

## How to Play

### Getting Started

#### Option 1: Direct File Opening (Simplest)
1. Open `flappy-bird.html` in your web browser
2. The game will start automatically
3. Your chicken will begin falling due to gravity

#### Option 2: Local Development Server (Recommended)
1. Open terminal in the project directory
2. Run: `python3 -m http.server 8000`
3. Open your browser and go to: `http://localhost:8000/flappy-bird.html`
4. The game will start automatically
5. Your chicken will begin falling due to gravity

#### Option 3: Using npm (if you have Node.js)
1. Install Node.js if you haven't already
2. Run: `npm start`
3. The game will open in your default browser

### Controls
- **Click** anywhere on the game screen to make the chicken flap
- **Press SPACE bar** to make the chicken flap
- Both methods work the same way - choose what feels most comfortable!

### Objective
- Navigate your chicken through the green pipes
- Avoid hitting the pipes, the ground, or the top of the screen
- Each pipe you successfully pass through gives you 1 point
- Try to achieve the highest score possible!

### Game Features
- **Bright Golden Chicken**: Vibrant, eye-catching chicken character with red comb and wattle
- **Realistic City Skyline**: Beautiful pastel-colored buildings with lit windows
- **Glorious Sun**: Glowing sun with rays in the sky
- **Enhanced Clouds**: Detailed cloud formations
- **Realistic Pipes**: 3D pipes with depth and shadows (no grid lines)
- **Score Tracking**: Real-time score display
- **Game Over Screen**: Shows your final score with a restart button
- **Smooth Physics**: Realistic gravity and flapping mechanics

### Game Over
The game ends when:
- Your chicken hits a green pipe
- Your chicken hits the ground
- Your chicken hits the top of the screen

### Restarting
- When the game ends, click the "Play Again" button
- Your score will reset to 0
- A new set of pipes will be generated

## Tips for High Scores
- **Timing is everything**: Don't flap too early or too late
- **Watch the pipes**: Look ahead to see where the gaps are
- **Stay calm**: Don't panic and spam the controls
- **Practice**: The more you play, the better you'll get!

## Technical Details
- Built with HTML5 Canvas
- Pure JavaScript (no external libraries)
- Responsive design
- Works on desktop and mobile browsers
- No external dependencies required
- Realistic 3D effects with gradients and shadows
- Dynamic lighting system for building windows

## Development

### Running Locally
The game can be run in several ways:

1. **Direct file opening**: Simply open `flappy-bird.html` in any modern browser
2. **Local server**: Use `python3 -m http.server 8000` for development
3. **npm scripts**: Use `npm start` if you have Node.js installed

### File Structure
```
FlappyChicken/
├── flappy-bird.html  # Main game file with realistic graphics
├── README.md         # This instruction file
├── package.json      # Project configuration
├── LICENSE           # MIT license
└── .gitignore        # Git ignore rules
```

### Visual Features
- **Bright Golden Chicken**: Stands out against the city background
- **Pastel City Skyline**: Dull, flat buildings in soft colors
- **Realistic Pipes**: 3D pipes with shadows and depth
- **Glorious Sun**: Beautiful sun with rays
- **Enhanced Clouds**: Multiple detailed cloud formations
- **Brown Earth Ground**: Simple textured ground

## Project Files
```
flappy-bird.html  - The main game file
README.md        - This instruction file
package.json     - Project configuration and scripts
LICENSE          - MIT license
.gitignore       - Git ignore rules
```

Enjoy playing Flappy Chicken! 🐔🎮 