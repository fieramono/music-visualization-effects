# Premium Music Visualization Effects

A high-performance, immersive music visualization platform built with **Three.js** and **Modern Web Technologies**. This project offers a variety of premium visual experiences that react in real-time to environmental audio or music.

![Preview Placeholder](https://via.placeholder.com/800x450?text=Premium+Visualizer+Demo)

## ✨ Features

- **11 Immersive Visual Patterns**:
  - `Energy Waves`: Flowing 3D lines reacting to frequencies.
  - `Neural Network`: Dynamic nodes and connections with reactive pulses.
  - `Retro Equalizer`: Classic logarithmic bar visualization.
  - `Oscilloscope`: Real-time spectrum wave.
  - `Floating Orbs`: Particle-based movement and dispersion.
  - `Spinning Galaxy`: Spiral formation of star points.
  - `DNA Helixes`: Moving double helix structures.
  - `Starfield Warp`: Traveling through space with audio-driven speed.
  - `Infinite Tunnel`: Pulsating 3D ring tunnel.
  - `Nebula Clouds`: Soft, atmospheric particle fields.
  - `Connected Particles`: Network-style particle interaction.

- **Real-time Audio Reactivity**: Uses Web Audio API to sync visuals with the environment or music via microphone.
- **Premium UI/UX**:
  - **Glassmorphism Design**: Sleek, blurred interface.
  - **Color Customization**: Dual-tone color mapping with presets and LocalStorage persistence.
  - **Dynamic Controls**: Fine-tune specific parameters for every individual effect.
  - **Idle Mode**: Auto-hiding UI and cursor for an unobstructed viewing experience.
- **High Performance**: Optimized rendering with `three.js` and post-processing bloom effects.

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Edge, Firefox, or Safari).
- Microphone access (for audio synchronization).

### Installation

1. Clone or download this repository.
2. Open `index.html` directly in your browser.
   - *Note: For best performance, it is recommended to run a local server (e.g., Live Server or python -m http.server).*

## 🛠️ Technology Stack

- **Graphics**: [Three.js](https://threejs.org/) (R128)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Audio Processing**: Web Audio API
- **Interactions**: Three.js OrbitControls
- **Post-Processing**: UnrealBloomPass (Post-processing glow effect)

## 📁 Repository Structure

- `index.html`: The main entry point containing the HTML structure, styles, and the entire JavaScript logic.

## 🎨 Presets & Customization

The visualizer includes several built-in color palettes like **Aurora**, **Matrix**, **Ocean**, and **Sunset**. Users can also define their own color pairs and save them locally to their browser settings.

## 📄 License

This project is open-source. Feel free to use and modify it for your own creative projects.
