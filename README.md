# The Corn Maze

A relaxing, artistic first-person corn maze simulator game built with HTML5 Canvas and raycasting.

## Play Online

Simply open `corn-maze.html` directly in any modern web browser.

## Local Server

To serve locally:

```bash
node serve-maze.js
# Then visit http://localhost:8080
```

## Game Features

### Gameplay
- **5 Levels**: Progressively larger mazes (5×5 to 22×22 procedural generation)
- **First-Person View**: Raycasting 3D rendering with artistic corn stalk walls
- **Atmosphere**: Warm golden sky, dirt floor, dust motes, swaying corn
- **Navigation**: Arrow keys to move/look, compass and minimap with fog-of-war
- **Ambient Sounds**: Character comments when hitting dead ends or turning around

### Levels
1. **The Gentle Stroll** (5×5) - Easy warmup
2. **Getting Interesting** (8×8) - Moderate challenge
3. **The Corn Thickens** (12×12) - Real navigation required
4. **Labyrinth of Cobs** (16×16) - Complex maze
5. **The Final Harvest** (22×22) - Ultimate challenge

### Celebrations (Get Progressively Absurd!)
1. **Level 1**: Farmer in straw hat clapping - "Not bad for a city slicker!"
2. **Level 2**: Small-town crowd with "NICE JOB!" banner and running dog
3. **Level 3**: Night sky fireworks, champagne popping, gold confetti
4. **Level 4**: Stadium with laser lights, disco ball, elephants in party hats, bald eagle with banner, moonwalking T-Rex in sunglasses
5. **Level 5**: CHAOS - UFO descending, swirling portal to "The Corn Dimension," whale in top hat playing trumpet, cats in sombreros parachuting, sentient dancing corn, everything becomes a kaleidoscope. "The corn always remembers."

## Controls

| Key | Action |
|-----|--------|
| **Arrow Keys** | Move forward/backward, turn left/right |
| **Enter** | Start game, proceed to next level |
| **ESC** | (Would pause, if implemented) |

## Technical Details

- **Engine**: Raycasting (similar to Wolfenstein 3D)
- **Graphics**: HTML5 Canvas 2D
- **Maze Generation**: Recursive backtracker algorithm
- **Size**: Single 46KB HTML file with no dependencies
- **Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)

## Visual Style

Inspired by autumn cornfield aesthetics:
- Near-black background with warm accent colors
- Olive green and golden corn textures
- Warm gradient sky (blue to golden peach)
- Earthy brown dirt floor with distance fog

## Credits

Built with Claude AI | Corn choreography by the wind | Whale trumpet instruction by Professor Barnacles

---

*"The corn maze is not just a game. It's a journey. The corn sees all. The corn remembers."*
