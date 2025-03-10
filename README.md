# 3D Mini Cafe 🍰

A beautiful 3D cafe experience built with React Three Fiber featuring shader transitions, interactive models, and stunning visual effects.

## Features

- 🎨 Custom shader transitions between screens and models
- 🍮 Interactive 3D models with fade effects
- 🌟 Beautiful spiral screen transitions
- 🎭 Model dissolve effects with noise patterns
- 📱 Responsive design for mobile and desktop
- ⚡ Optimized performance with proper model loading
- 🎬 Smooth animations using Framer Motion

## 3D Models

The project uses the following 3D models by Ergoni (Licensed under Creative Commons Attribution):
- Juice Carton Shop
- Cake Roll
- Choco Bunny
- ❤️ Flan - Quesillo ❤️

## Tech Stack

- React Three Fiber - 3D rendering
- Tailwind CSS - Styling
- Framer Motion - Animations
- Jotai - State management
- Three.js - 3D graphics
- Custom Shaders - Transition effects

## Getting Started

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) and [Bun](https://bun.sh) installed on your system.

### Installation

1. Clone the repository:
```bash
git clone https://github.com/pakagronglb/3d-mini-cafe.git
cd 3d-mini-cafe
```

2. Install dependencies:
```bash
bun install
```

3. Run the development server:
```bash
bun run dev
```

## Project Structure

```
3d-mini-cafe/
├── src/
│   ├── components/
│   │   ├── Experience.jsx
│   │   ├── ScreenTransition.jsx
│   │   ├── TransitionModel.jsx
│   │   └── UI.jsx
│   ├── shaders/
│   └── App.jsx
├── public/
│   └── models/
└── package.json
```

## Features in Detail

### Screen Transitions
- Custom shader-based spiral transition effect
- Smooth fade in/out with color transformations
- Configurable timing and animation parameters

### Model Transitions
- Top-to-bottom dissolve effect
- Noise-based pattern dissolution
- Color wash effects during transitions
- Smooth shadow transitions

### Interactive UI
- Beautiful typography with Kanit and Rubik Doodle Shadow fonts
- Responsive design for all screen sizes
- Smooth animations and transitions
- Color customization through Leva controls

## Customization

You can adjust the colors and other visual parameters using the Leva controls panel. To hide the controls in production:

```jsx
<Leva hidden />
```

## Performance Optimization

The project includes several optimizations:
- Proper model loading and disposal
- Efficient shader implementations
- Optimized transition effects
- Proper use of React Three Fiber's built-in optimizations

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


## Acknowledgments

- 3D Models by Ergoni (Creative Commons Attribution)
- Shader inspiration from ShaderToy
- React Three Fiber community
- Wawa Sensei tutorials and guidance

## Support

If you have any questions or run into issues, please open an issue in the repository or join our Discord community for help.
