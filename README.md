# A-Frame VR/AR Development Tutorial

This repository contains a series of A-Frame tutorials demonstrating various concepts in WebVR/WebAR development using the A-Frame framework.

## 📁 Project Structure

```
a-frame/
├── lecture-1/              # Basic 3D Shapes
├── lecture-2/              # Sky and Environment
├── lecture-3/              # Parent-Child Relationships
├── lecture-4/              # Links and Interactions
├── lecture-5/              # Scaling and Transformations
├── lecture- (3d model)/    # 3D Model Loading
└── README.md
```

## 🎯 Tutorial Contents

### Lecture 1: Basic 3D Shapes
**File:** `lecture-1/index.html`

Introduction to fundamental A-Frame primitives:
- **Box**: Green box with custom dimensions
- **Cylinder**: Red cylinder with 5 segments
- **Sphere**: Blue sphere
- **Torus Knot**: Yellow torus knot
- **Dodecahedron**: Orange dodecahedron

Demonstrates basic positioning and color properties.

### Lecture 2: Sky and Environment
**File:** `lecture-2/index.html`
**Assets:** `lecture-2/m-sky.jpg`

Builds on Lecture 1 with:
- Same basic shapes (box and cylinder)
- **Sky component**: Custom sky texture using `m-sky.jpg`
- Shows how to create immersive environments

### Lecture 3: Parent-Child Relationships
**File:** `lecture-3/index.html`

Demonstrates hierarchical object relationships:
- **Parent Box**: Contains a child circle element
- **Independent Circle**: Positioned separately
- **Cylinder**: Advanced positioning
- **Sky**: Teal-colored sky background

### Lecture 4: Links and Interactions
**File:** `lecture-4/index.html`

Introduces interactive elements:
- **Linked Text**: Clickable text that opens Google in new tab
- **Advanced Positioning**: Objects with rotations and transformations
- **Open-ended Cylinder**: Hollow cylinder geometry

### Lecture 5: Scaling and Transformations
**File:** `lecture-5/index.html`

Focuses on scaling and advanced transformations:
- **Scaled Circle**: Orange circle with 2:1 scale ratio
- **Advanced Rotations**: Complex rotation values
- **Reflection**: Demonstrates scale properties

### Lecture (3D Model): External 3D Models
**File:** `lecture- (3d model)/index.html`
**Assets:** `lecture- (3d model)/couch/`

Shows how to load external 3D models:
- **OBJ/MTL Loading**: Couch model with materials
- **Asset Management**: Using A-Frame's asset system
- **Inline Loading**: Alternative loading method

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/code-abdulrehman/a-frame
   cd a-frame
   ```

2. **Open any lecture folder:**
   ```bash
   cd lecture-1
   ```

3. **Serve the files:**
   - Use a local server (required for A-Frame)
   - Python: `python -m http.server 8000`
   - Node.js: `npx serve .`
   - VS Code: Live Server extension

4. **View in browser:**
   - Open `http://localhost:8000`
   - Use VR headset or mobile device for immersive experience

## 🛠️ Technology Stack

- **A-Frame**: WebVR framework (v1.7.0)
- **HTML5**: Standard web technologies
- **WebVR**: Virtual reality web standards
- **3D Models**: OBJ/MTL format support

## 📱 VR/AR Compatibility

- **VR Headsets**: Oculus Quest, HTC Vive, etc.
- **Mobile VR**: Google Cardboard, Daydream
- **Desktop**: Mouse and keyboard navigation
- **AR**: WebXR AR features (modern browsers)

## 🎓 Learning Path

1. Start with **Lecture 1** for basic concepts
2. Progress through lectures sequentially
3. Experiment with modifying properties
4. Combine concepts from multiple lectures
5. Try the 3D model loading in the final lecture

## 🔧 Customization

Each lecture can be modified to experiment with:
- Colors and materials
- Positions and rotations
- Sizes and scales
- Adding new primitives
- Custom 3D models

## 📚 Resources

- [A-Frame Documentation](https://aframe.io/docs/)
- [A-Frame Examples](https://aframe.io/examples/)
- [WebVR Standards](https://webvr.info/)
- [WebXR Device API](https://immersive-web.github.io/webxr/)

## 🤝 Contributing

Feel free to:
- Add new lecture examples
- Improve existing code
- Add more 3D models
- Enhance documentation
