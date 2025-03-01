# Interactive Particle Animation

A beautiful, interactive particle animation system that responds to cursor movements and voice mode activation. This project creates an engaging visual experience with particles that react dynamically to user interaction.

**This is a look-alike of Perplexity's new voice mode interface features**, recreated as a standalone interactive animation.

## Features

- **Interactive Particle System**: Particles respond to cursor movements with a shattering effect
- **Voice Mode**: Toggle a pulsing animation that simulates voice activity
- **Responsive Design**: Automatically adjusts to different screen sizes
- **Performance Optimized**: Frame-limiting and throttling for smooth animations
- **Touch Support**: Works on both desktop and mobile devices

## Demo

Open `index.html` in a web browser to see the animation in action.

## How to Use

1. **Hover Interaction**: Move your cursor over the particles to see them scatter
2. **Voice Mode**: Click the "Start Voice Mode" button to activate a pulsing animation
3. **Reset**: Click the "Reset Animation" button to restore the original particle formation

## Technical Details

The animation uses HTML5 Canvas and vanilla JavaScript with the following key components:

- Particle physics simulation with forces, velocity, and mass
- Spherical coordinate distribution for even particle placement
- Throttled event handling for performance
- Configurable parameters for easy customization

## Customization

You can modify the following parameters in the `config` object to customize the animation:

```javascript
const config = {
  particleCount: 800,            // Number of particles
  circleRadius: ...,             // Base radius of the particle formation
  interactionRadius: 45,         // Radius of cursor interaction
  repelForce: 65,                // Strength of repulsion
  particleMaxSpeed: 30,          // Maximum particle velocity
  friction: 0.94,                // Friction/damping factor
  rotationSpeed: 0.005           // Global rotation speed
  // ... and more
};
```

## Browser Compatibility

This animation works in all modern browsers that support HTML5 Canvas and ES6 JavaScript.

## License

MIT License

## Author

fhdkahn 