# 🔥 Advanced Tokamak Fusion Reactor Simulation

A comprehensive, interactive 3D simulation of a tokamak fusion reactor with 62+ advanced physics features, real-time rendering, and diagnostic systems.

![Tokamak Simulation](screenshot.png)
*Interactive 3D visualization of plasma confinement with magnetic field lines*

## 🌟 Features

### Core Physics (9000+ lines)
- **Magnetic Confinement**: Toroidal & poloidal fields, flux surfaces, magnetic coils
- **Plasma Dynamics**: Bootstrap current, neoclassical transport, rotation profiles
- **Instabilities**: ELMs, NTMs (3/2, 2/1), sawteeth, disruptions, fishbones
- **MHD Modes**: Alfven waves, ballooning modes, external kinks, RWM with feedback
- **Turbulence**: Blob transport, SOL flows, detachment physics

### Heating & Current Drive (4 Systems)
- 📡 **ICRH** - Ion Cyclotron Resonance Heating
- 🔵 **ECRH** - Electron Cyclotron Resonance Heating
- 🎯 **NBI** - Neutral Beam Injection
- ⚡ **LHCD** - Lower Hybrid Current Drive

### Advanced Scenarios
- 🔷 Hybrid Scenario (q_min > 1)
- ⚡ Advanced Tokamak Mode
- ♾️ Steady-State Operation
- 🌟 L-H Transition with H-Mode Pedestal
- 🔥 QH-Mode (Quiescent H-Mode)
- 🌈 Internal Transport Barrier (ITB)

### Control Systems
- 📍 Vertical Position Control (PID)
- 🔷 Plasma Shape Control
- 📊 Density Feedback Control
- ⚡ Fusion Power Control
- 🔄 Rotation Control (NBI torque)

### Diagnostics
- 🔬 Thomson Scattering
- 📡 ECE Imaging
- ☢️ Soft X-ray Tomography
- ⚛️ Neutron Camera
- 📏 Interferometry

### Plasma-Wall Interactions
- 🔻 Divertor with detachment
- 🔨 Material sputtering
- 🔥 Heat flux monitoring
- ☢️ Impurity transport
- ⚛️ Charge exchange
- 🧊 Pellet injection

### Energetic Particles
- 🔥 Alpha particle heating
- 💨 Fast ion losses (ripple, collisions)
- 🍌 Banana orbit visualization
- ⚡ Runaway electron generation

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome, Firefox, Edge)
- Internet connection (for Three.js CDN)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/tokamak-simulation.git
cd tokamak-simulation
```

2. **Open in browser**
```bash
# Simply open index_complete.html in your browser
# Or use a local server:
python -m http.server 8000
# Then navigate to http://localhost:8000
```

3. **Start simulating!**
- Click tools menu to enable features
- Use mouse to rotate/zoom camera
- Toggle physics features in real-time

## 🎮 Controls

### Camera
- **Left Mouse** - Rotate view
- **Right Mouse** - Pan
- **Scroll Wheel** - Zoom in/out

### Physics Features
- **Tools Menu** (right side) - Toggle 62 physics features
- Features activate in real-time
- Visual indicators for active systems

## 📊 Performance

- **Code**: 9000+ lines of JavaScript
- **Features**: 62 interactive physics modules
- **Rendering**: WebGL with Three.js (r128)
- **Frame Rate**: 60 FPS on modern hardware

## 🔬 Physics Accuracy

This simulation includes:
- Real tokamak geometry (aspect ratio, elongation, triangularity)
- Grad-Shafranov equilibrium solver
- MHD stability calculations
- Neoclassical transport theory
- Empirical scaling laws (ITER H98, etc.)

**Note**: Simplified for educational purposes. Not suitable for reactor design.

## 🛠️ Technical Stack

- **Graphics**: Three.js (WebGL)
- **Physics**: Custom JavaScript solvers
- **UI**: Pure HTML/CSS/JS (no frameworks)
- **Data Viz**: Real-time 2D charts (Q-profile, pedestal)

## 📁 Project Structure
```
tokamak-simulation/
├── index_complete.html    # Main simulation (9000+ lines)
├── README.md             # This file
└── screenshots/          # Demo images
```

## 🎯 Use Cases

- **Education**: Learn tokamak physics interactively
- **Research**: Visualize complex plasma phenomena
- **Demonstrations**: Show fusion reactor concepts
- **Development**: Base for advanced simulations

## 🐛 Known Issues

- Some visual features don't render (banana orbits, intrinsic rotation)
- Disruptions button non-functional
- Performance degrades with 20+ features active simultaneously

## 🔮 Future Improvements

- [ ] Add data export (CSV, JSON)
- [ ] Implement more control algorithms
- [ ] Real-time parameter adjustment sliders
- [ ] Multiple tokamak geometries (ITER, JET, SPARC)
- [ ] WebGPU rendering for better performance

## 📝 License

MIT License - See LICENSE file for details

## 🙏 Acknowledgments

Inspired by real tokamak fusion research at:
- ITER Organization
- JET (Joint European Torus)
- MIT PSFC (Plasma Science & Fusion Center)

