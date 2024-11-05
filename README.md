# Audio Visualizer

An interactive audio visualizer that creates dynamic animations based on microphone input. Built with HTML5 Canvas and Web Audio API.

## Features

- 7 unique animation styles:
  - Circle
  - Wave
  - Spiral
  - DNA
  - Orbit
  - Matrix
  - Vortex
- Real-time audio visualization
- Customizable settings:
  - Audio sensitivity
  - Animation speed
  - Color inversion
  - Animation style selection
  - Auto-rotation of styles
- FPS counter
- Responsive design
- Optimized performance


## Usage

1. Allow microphone access when prompted
2. Click the ⚙️ icon to open settings panel
3. Adjust settings to customize the visualization:
   - Select animation style
   - Adjust audio sensitivity
   - Change animation speed
   - Toggle FPS display
   - Toggle color inversion
   - Enable/disable auto-rotation

## Settings

- **Animation Style**: Choose between 7 different visualization patterns
- **Audio Sensitivity**: Adjust how responsive the visualization is to audio (0.1-2.0)
- **Animation Speed**: Control the movement speed (0.01-0.5)
- **Show FPS**: Toggle FPS counter display
- **Invert Colors**: Switch between dark and light mode
- **Auto Rotate**: Automatically cycle through animation styles every 30 seconds

## Dependencies

- No external libraries required
- Uses native Web APIs:
  - Web Audio API
  - Canvas API
  - requestAnimationFrame
  - MediaDevices API

## Browser Compatibility

Supported in modern browsers:
- Chrome 58+
- Firefox 52+
- Safari 11+
- Edge 79+

