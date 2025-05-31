# Box Dimension Visualizer

A comprehensive 3D tool for visualizing custom protective cases and camera bag dimensions with precise fit analysis and collision detection.

## Live Demo
**[Try it here: boxvisualizer.pages.dev](https://boxvisualizer.pages.dev/)**

## What it does

### Core Features
- **Interactive 3D visualization** with adjustable box dimensions (length, height, width, thickness)
- **Dual measurement modes**: Toggle between outer and inner dimensions
- **Unit conversion**: Switch between metric (cm) and imperial (inches)
- **Real-time collision detection** with visual feedback (red surfaces indicate collisions)
- **Precise clearance measurements** with color-coded indicators (green/yellow/red)

### Camera & Lens System
- **Adjustable camera reference** with customizable dimensions
- **Lens attachment support** with independent length control
- **Total assembly width calculation** (camera + lens)
- **Canon EOS Rebel T7 preset** for quick reference (12.9cm × 10.1cm × 7.8cm)
- **Visual measurement indicators**: Blue lines show which dimensions you're controlling

### Advanced Controls
- **Box thickness control** for material considerations
- **Pause animation** option for detailed inspection
- **Mouse controls** for rotation and zoom
- **Responsive design** that works on mobile devices

## Use Cases
- **Custom camera bag design** - Verify exact fit before ordering
- **Protective case planning** - Ensure proper clearances for equipment
- **Packaging design** - Visualize product fit with material thickness
- **3D printing enclosures** - Plan internal clearances for electronics
- **Storage solutions** - Design custom foam inserts

## Visual Feedback System
- **Blue wireframes**: Indicate which dimensions you're currently measuring
- **Red surfaces**: Show collision areas between camera and box
- **Green clearances**: Safe fit with adequate space
- **Yellow clearances**: Tight fit warning (≤0.3cm/0.3")
- **Red clearances**: Collision detected

## Built With
- Three.js for 3D rendering
- Vanilla HTML/CSS/JavaScript
- No dependencies or build process required

## Controls

### Box Dimensions
- **Length/Height/Width sliders**: 1-15" (2.5-38cm)
- **Thickness slider**: 0-2" (0-5cm) for material thickness
- **Outer/Inner toggle**: Switch measurement reference

### Camera System
- **Camera dimension sliders**: Fully adjustable length/height/width
- **Lens length slider**: 0-8" (0-20cm) for lens attachments
- **Reset button**: Restore Canon T7 dimensions
- **Show/Hide toggles**: Camera reference and lens attachment

### Interface
- **Unit toggle**: Metric (cm) vs Imperial (inches)
- **Pause movement**: Stop auto-rotation for detailed inspection
- **Mouse controls**: Click-drag to rotate, scroll to zoom

## Technical Features
- Real-time 3D collision detection
- Automatic clearance calculations
- Responsive grid layout
- Mobile-optimized interface
- Live dimension updates
- Material thickness visualization

## License
This project is licensed under the terms of the GNU General Public License v3.0.
