# 🧠 Neural Canvas

An interactive neural network visualization — draw patterns and watch a real neural network learn from your input in real-time.

## Features

- **Real-time training** — Watch the network learn as you draw
- **Interactive drawing** — Draw positive (green) and negative (red) regions
- **Live visualization** — See weights, activations, and the network's output update in real-time
- **Configurable architecture** — Choose from multiple network architectures
- **Touch support** — Works on mobile and tablet

## How to Use

1. Draw on the left canvas (green = positive, right-click = negative)
2. Click **Train** to start training
3. Watch the right canvas show the network's learned output
4. The left panel shows the live neural network weights and activations

## Tech

- Pure HTML + CSS + JavaScript — no dependencies
- Custom neural network implementation with backpropagation
- Canvas-based rendering for all visualizations
- ReLU activation (output layer is linear)

## Run

Just open `index.html` in any modern browser.
