# kevins-quick-view
Interactive browser-based parameter editor and geometry viewer for TOPAS Monte Carlo simulation
# Kevin's Quick View

**An Interactive Browser-Based Geometry Viewer for TOPAS Monte Carlo Simulations**



## Overview

Kevin's Quick View is a real-time 3D geometry visualization tool for TOPAS Monte Carlo simulations. It allows users to instantly preview and validate geometry parameters without running full simulations, dramatically reducing setup time from hours to minutes.

### The Problem

Traditional TOPAS geometry workflow:
1. Write geometry parameters
2. Run simulation (minutes to hours)
3. View output (VRMLviewer or ParaView)
4. Make changes blindly
5. Repeat...

This iterative process can take 100+ hours for complex geometry setups.

### The Solution

Kevin's Quick View provides instant visual feedback:
- Paste your TOPAS geometry parameters
- The 3D visualization will update immediately
- Edit parameters and see changes in real-time
- Validate geometry before running simulations

## Features

-  Real-time 3D rendering of TOPAS geometry
-  Overlap error detection
-  Parent-daughter error detection
-  Interactive camera controls (rotate, zoom, pan)
-  Support for multiple geometry types (boxes, cylinders, spheres, cones)
-  Color-coded components
-  Runs entirely in browser (no installation required)
-  Works offline after initial load
-  Zero bandwidth usage during interaction

## Usage

### Quick Start

1. **Access the tool:**
   - Download `KEVINSQUICKVIEW.html`
   - Open it in any modern web browser
   - Or visit the hosted version: [URL will be added after deployment]

2. **Paste your TOPAS geometry parameters:**
   - Copy your geometry definitions from your TOPAS input file
   - Paste into the text area
   - Geometry updates instantly

3. **Interact with the visualization:**
   - Left-click + drag: Rotate
   - Right-click + drag: Pan
   - Scroll: Zoom

### Example

Sample TOPAS geometry parameters are pre-loaded in the tool. You can modify values like position, dimensions, or rotation angles and see changes immediately.

## Use Cases

- **Geometry prototyping**: Rapidly iterate on detector or phantom designs
- **Educational demonstrations**: Teach TOPAS geometry concepts interactively
- **Collaboration**: Share geometry designs with colleagues for quick review
- **Quality assurance**: Validate geometry before committing to long simulation runs

## Technical Details

- **Built with:** Three.js for 3D rendering
- **Client-side processing:** All computation happens in your browser
- **No backend required:** Host as a static HTML file anywhere
- **File size:** ~20 KB

## Installation

No installation needed, just download the HTML file and open it in your browser.

### For Developers

```bash
# Clone the repository
git clone https://github.com/kevinwilly1995/kevins-quick-view.git
cd kevins-quick-view

# Open in browser
open KEVINSQUICKVIEW.html
```

## Citation

If you use Kevin's Quick View in your research, please cite:

```bibtex
@software{willy_kevins_quick_view_2025,
  author       = {Willy, Kevin},
  title        = {Kevin's Quick View: Interactive Geometry Viewer for TOPAS},
  year         = 2025,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.XXXXXXX},
  url          = {https://github.com/kevinwilly1995/kevins-quick-view}
}
```

**APA Style:**
```
Willy, K. (2025). Kevin's Quick View: Interactive Geometry Viewer for TOPAS 
(Version 1.0) [Software]. Zenodo. https://doi.org/10.5281/zenodo.XXXXXXX
```

*A methods paper describing this tool is in preparation for submission.*

## Contributing

Feel free to:
- Report bugs or request features via GitHub Issues
- Submit pull requests with improvements
- Share your use cases

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**Kevin Willy**  
Thayer School of Engineering, Dartmouth College  
Email: kevinwilly1995@gmail.com
Email 2: kevin.j.willy.th@dartmouth.edu

## Acknowledgments

Built to support TOPAS Monte Carlo simulation workflows in medical physics research.

Portions of this work have been generated utilizing LLM's, particularly for troublehsooting errors.

---

**Keywords:** TOPAS, Monte Carlo simulation, geometry visualization, medical physics, radiation therapy, Three.js, interactive viewer
