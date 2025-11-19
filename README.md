# Interactive Walking Game

A fun interactive game where you help a barefoot person walk across the street by choosing their shoes and controlling their steps!

## Game Description

In this game, a person appears barefoot on the left side of a main street. You must:

1. **Choose Shoes**: Select between sneakers (easy mode) or high heels (hard mode)
2. **Walk**: Drag the person's feet with your mouse to make them walk to the right side of the screen
3. **Balance**: Keep your balance! If you lean too far or lose balance, you'll fall and have to restart

## How to Play

1. Open `index.html` in your web browser
2. Choose your shoes:
   - **Sneakers**: Easier to balance, larger steps allowed
   - **High Heels**: Harder to balance, smaller steps, more challenging!
3. Drag the feet to walk:
   - Click and hold on a foot
   - Drag it forward to take a step
   - Don't spread the feet too far apart
   - Keep them at roughly the same height
4. Watch the balance bar in the top right
5. Reach the goal flag on the right side to win!

## Game Mechanics

- **Balance System**: Your balance deteriorates when:
  - Feet are too far apart (> 100 pixels)
  - Feet are at different heights
  - Feet are too close together (< 20 pixels)

- **Shoe Differences**:
  - **Sneakers**: Balance decays slowly, can take bigger steps, more forgiving
  - **High Heels**: Balance decays quickly, smaller steps required, challenging!

- **Falling**: You fall if:
  - The person tilts too far (> 0.5 radians)
  - Balance meter exceeds the threshold

- **Winning**: Reach the goal flag on the right side of the screen!

## Features

- Beautiful street background with buildings, trees, and road
- Smooth physics and animations
- Visual feedback when dragging feet
- Balance meter to track your stability
- Different difficulty modes
- Touch support for mobile devices
- Responsive design

## Technical Details

- Built with HTML5 Canvas
- Pure JavaScript (no frameworks)
- Responsive and mobile-friendly
- Runs entirely in the browser

## Browser Compatibility

Works in all modern browsers that support HTML5 Canvas:
- Chrome
- Firefox
- Safari
- Edge

## Running the Game

Simply open `index.html` in your web browser. No server or installation required!

## Tips for Success

1. Take small, controlled steps
2. Keep both feet at the same height
3. Maintain a comfortable distance between feet (30-80 pixels)
4. Move one foot at a time
5. Watch the balance meter and adjust your stance if it gets too high
6. Sneakers are recommended for first-time players!

Enjoy the game! 🎮
