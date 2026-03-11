# Dinosaur Game

A browser-based side-scrolling survival game built with HTML, SVG, CSS animations, and jQuery.

## How to Play

Open `dinosaur_game.html` in any modern browser. Press **Spacebar** to make the character jump over incoming obstacles. Survive as long as possible!

## Features

- **Animated sky and ground** with gradient backgrounds and a sun with rays
- **Three clouds** drifting across the sky, each starting at a different time
- **Agnes** — the main character — jumps on spacebar press
- **Flower obstacle** appears at random intervals and speeds up after each successful dodge
- **Game over** detection when Agnes collides with the flower near ground level, with a bouncing animated "Game Over" message

## Controls

| Key | Action |
|-----|--------|
| `Space` | Jump |

## Technical Details

- Pure HTML/SVG — no canvas, no external game library
- CSS `@keyframes` animations for all movement
- jQuery used for DOM manipulation and event handling
- Obstacle speed increases by 0.1s per pass (minimum 1s duration)
