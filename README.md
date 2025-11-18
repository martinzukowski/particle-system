# Interactive Particle System

A beautiful web-based particle simulation where 300 red particles react dynamically to mouse movement on a navy blue canvas.

## Features

- **300 red particles** that move and interact
- **Navy blue background** with elegant styling
- **Mouse interaction** - particles are attracted to your cursor
- **Smooth 60 FPS animation** using requestAnimationFrame
- **Real-time FPS counter**
- **Modern UI** with glassmorphism effects and gradients
- **Responsive design** that works on different screen sizes

## How to Run

### Option 1: Using Python (Recommended)
1. Make sure you have Python installed
2. Run the server:
   ```bash
   python server.py
   ```
3. Your browser should open automatically to `http://localhost:8000`
4. If it doesn't open automatically, navigate to `http://localhost:8000` in your browser

### Option 2: Direct File Opening
1. Simply double-click `index.html` to open it in your default browser
2. Note: Some browsers may have restrictions on local files, so Option 1 is recommended

### Option 3: Using Node.js (if you have it)
```bash
npx http-server -p 8000
```
Then open `http://localhost:8000` in your browser

## Controls

- **Move your mouse** over the canvas to interact with particles
- Particles are **attracted** to your mouse cursor
- When particles get very close, they'll be **pushed away** slightly
- Particles **bounce** off the edges of the canvas

## Technical Details

- Pure HTML5 Canvas and JavaScript
- No external dependencies
- Optimized for smooth 60 FPS performance
- Responsive design with mobile support

## Project Structure

```
cool_particles/
├── index.html      # Main application file
├── server.py       # Simple Python web server
└── README.md       # This file
```
