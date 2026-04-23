# Emoji Memory Match

A fun, interactive memory card game built with HTML, CSS, JavaScript, and jQuery.

## How to Play

1. Click any card to flip it and reveal its emoji.
2. Click a second card — if both emojis match, they stay face-up!
3. If they don't match, they flip back after a short delay.
4. Find all 8 matching pairs to win.

## Features

- 16-card grid (8 pairs of emojis)
- Flip counter and match tracker
- One-time peek hint button
- Win screen with efficiency score

## Unique Element — Adaptive Difficulty

**The flip-back timer shortens automatically as you match more pairs.**

- Starts at 1.2 seconds (easy — plenty of time to memorize)
- Drops by 0.1s with each successful match
- Reaches a minimum of 0.4 seconds by the final pairs (very fast!)

This means the game gets progressively harder mid-session without any manual difficulty setting — the more you succeed, the less time you get to memorize unmatched cards. A visual difficulty bar reflects this in real time.

## Tech Stack

- HTML5
- CSS3 (custom properties, 3D card flip animations)
- JavaScript (ES6)
- jQuery 3.7.1

## How to Run

Just open `index.html` in any modern browser — no build step or server needed.
