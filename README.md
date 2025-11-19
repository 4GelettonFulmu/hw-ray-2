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
  - Feet are too far apart (> 150 pixels)
  - Feet are at different heights (> 30 pixels difference)
  - Feet are too close together (< 10 pixels)

- **Shoe Differences**:
  - **Sneakers**: Balance decays very slowly, can take bigger steps, very forgiving (beginner-friendly!)
  - **High Heels**: Balance decays moderately, smaller steps required, moderate challenge

- **Falling**: You fall if:
  - The person tilts too far (> 1.0 radians)
  - Balance meter exceeds the threshold

- **Winning**: Reach the goal flag on the right side of the screen!

## Features

### Visual Elements
- **Detailed Sky**: Gradient sky with animated sun, rays, fluffy clouds, and flying birds
- **Cityscape**: Varied buildings with shadows, roofs, detailed windows with reflections, and entrance doors
- **Street Lamps**: Illuminated lamps with glowing effects
- **Nature**: Detailed trees with branches, layered foliage, trunk texture, colorful flowers, and bushes
- **Road & Sidewalk**: Textured road with gradients, edge lines, and tiled sidewalk
- **Character Design**: Fully detailed person with hair, facial features (eyes, nose, smile), clothing (shirt with collar and buttons), hands, and realistic shadow
- **Shoe Details**:
  - Sneakers with laces, soles, logos, and shadows
  - High heels with straps, buckles, stiletto heels, and shine effects
  - Barefoot with visible toes
- **Goal Flag**: Checkered flag with shadow, base, wave effect, and "GOAL" text

### Gameplay
- Smooth physics and animations with 50% reduced difficulty for easier gameplay
- Visual feedback with glowing highlights when dragging feet
- Balance meter to track your stability
- Two difficulty modes (both beginner-friendly now!)
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

1. Take smooth, controlled steps
2. Keep both feet at roughly the same height
3. Maintain a comfortable distance between feet (30-120 pixels is now acceptable!)
4. Move one foot at a time for better control
5. Watch the balance meter - it recovers faster now, so don't panic!
6. The game is now much more forgiving - perfect for beginners!
7. Even high heels are manageable now - give them a try!

Enjoy the beautifully detailed game! 🎮
