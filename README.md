
# Neural Network Function Learning

A visualization of a neural network learning to fit mathematical functions using Three.js.

## Overview

This application uses a feedforward neural network to approximate mathematical functions, with real-time visualization using Three.js to show the learning process.

## Live Demo

Visit [loehx.github.io/curve-fitting-neural-network](https://loehx.github.io/curve-fitting-neural-network/) to see it in action.

## Features

- Interactive 3D visualization 
- Real-time training visualization
- Configurable network architecture
- Supports arbitrary functions
- Smooth animation

## Technical Details

- Multiple configurable hidden layers
- ReLU activation functions
- Gradient descent optimization
- Weight/bias initialization

## Usage

1. Open `index.html` in a browser
2. Watch the visualization automatically start
3. Blue points show the target function
4. Red surface shows the network's approximation

## Dependencies

- Three.js (r134+)
- WebGL-capable browser

## Implementation

Core components:
- Neural network implementation
- Three.js visualization
- Training loop
- Dynamic mesh generation

## License

MIT License
