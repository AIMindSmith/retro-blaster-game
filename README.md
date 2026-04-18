# RETRO BLASTER

A retro arcade-style shooter game built with HTML5 Canvas and vanilla JavaScript.

![Game Screenshot](screenshot.png)

## Features

- **Procedural Pixel Art Sprites** - All graphics generated programmatically
- **4 Enemy Types** - Basic, Fast, Tank, and Boss enemies with unique stats
- **Power-ups** - Health, Speed Boost, Multishot, and Shield
- **Level Progression** - Increasing difficulty with waves and levels
- **Combo System** - Chain kills for score multipliers
- **Retro Visual Effects** - CRT scanlines, vignette, particle effects

## Controls

| Key | Action |
|-----|--------|
| **WASD / Arrow Keys** | Move |
| **Mouse** | Aim |
| **Left Click** | Shoot |
| **ESC** | Pause |
| **SPACE** | Start (from menu) |
| **R** | Restart (after game over) |

## How to Play

1. Open `retro-shooter.html` in any modern browser
2. Press **SPACE** to start
3. Survive waves of enemies from all directions
4. Collect power-ups to gain advantages
5. Chain kills for combo multipliers
6. Clear 3 waves to advance to the next level

## Game Mechanics

### Enemy Types

| Type | Health | Speed | Damage | Score |
|------|--------|-------|--------|-------|
| Basic | 50 | Medium | 10 | 100 |
| Fast | 30 | Fast | 8 | 150 |
| Tank | 150 | Slow | 20 | 300 |
| Boss | 500 | Very Slow | 30 | 1000 |

### Power-ups

- **Health** (Green) - Restore 30 HP
- **Speed** (Blue) - Increase movement speed
- **Multishot** (Orange) - Fire 3 bullets at once
- **Shield** (Purple) - Temporary invincibility

## Technical Details

- Pure JavaScript (no external libraries)
- HTML5 Canvas rendering
- 60 FPS game loop
- Procedural sprite generation
- Collision detection with spatial optimization

## Browser Compatibility

Works in all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## License

MIT License - feel free to use and modify!
