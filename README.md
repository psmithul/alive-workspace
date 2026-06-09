# Alive Workspace

An animated, living home/office environment built with p5.js. This sketch creates a lively workspace featuring:

- A cozy animated house with lighting effects and smoke from the chimney
- A detailed office setup with monitor, keyboard, chair, and desk lamp
- Floating particles and natural elements that bring the scene to life
- Subtle animations throughout that make the environment feel alive

## Features

- **Animated House**: Windows with pulsing lights, chimney with drifting smoke
- **Interactive Office**: Monitor with animated display, keyboard with key presses, comfortable chair
- **Natural Elements**: Floating leaves, petals, and ambient particles
- **Living Atmosphere**: Continuous subtle animations that make the space feel inhabited
- **Responsive Design**: Works on different screen sizes

## Controls

- Press `S` to save a screenshot
- Press `G` to save a 5-second GIF animation
- Press `R` to reset with a new random seed
- Press `Space` to pause/resume animation (in extended versions)

## Built With

- [p5.js](https://p5js.org/) - JavaScript library for creative coding
- HTML5 Canvas

## Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/psmithul/alive-workspace.git
   cd alive-workspace
   ```

2. Open `index.html` in your web browser:
   ```bash
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   
   # On Windows
   start index.html
   ```

## Customization

You can modify the `CONFIG` object at the top of the script to adjust:
- `seed`: Change the random seed for different variations
- `houseSize` / `officeSize`: Adjust the scale of elements
- `animationSpeed`: Control the overall animation pace
- `particleCount`: Increase or decrease floating particles

## License

This project is open source and available under the MIT License.

## Acknowledgments

Inspired by the concept of creating living, breathing digital environments that blend workspace functionality with organic, animated elements.