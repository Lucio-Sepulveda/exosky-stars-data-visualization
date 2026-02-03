# ExoSky - Stars Data Visualization

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Godot Engine](https://img.shields.io/badge/Godot-4.3+-blue.svg)](https://godotengine.org/)
[![NASA Space Apps 2024](https://img.shields.io/badge/NASA%20Space%20Apps-2024-red.svg)](https://www.spaceappschallenge.org/)

An interactive 3D visualization application that displays star positions and temperatures as seen from different exoplanets, using NASA's star database.

**🏆 First Place Winner** - NASA International Space Apps Challenge 2024 (Local Site)

![ExoSky Visualization](screenshots/photo_mode.png.png)
*Replace with actual screenshot path*

## 📖 About

ExoSky was developed during the **NASA International Space Apps Challenge 2024**, a 48-hour global hackathon. This project tackles the [ExoSky Challenge](https://www.spaceappschallenge.org/nasa-space-apps-2024/challenges/exosky/?tab=details), which asked participants to visualize NASA's database of star positions and temperatures from the perspective of exoplanets.

The application provides an immersive 3D space environment where users can explore the night sky as it would appear from different exoplanetary systems, with stars color-coded based on their actual temperatures.

## ✨ Features

- **3D Space Exploration**: Navigate freely through a 3D star field using WASD controls and mouse camera movement
- **Temperature-Based Visualization**: Stars are rendered with colors corresponding to their actual temperatures
- **Multiple Exoplanets**: Switch between different exoplanetary perspectives (data for multiple exoplanets included)
- **Photo Mode**: Capture your view and create custom constellations by connecting stars
- **High Performance**: Efficient rendering of thousands of stars using the Godot Starlight addon
- **Cross-Platform**: Available for Windows and Web (web version currently unavailable due to server requirements)

## 🎮 Controls

- **WASD**: Move camera
- **Mouse**: Look around
- **Shift**: Accelerate movement
- **Photo Mode**: Toggle constellation drawing mode

## 🚀 Getting Started

### Prerequisites

- Godot Engine 4.3 or higher (tested up to 4.6)

### Running from Executable

1. Navigate to the `export/` folder
2. Run the `.exe` file

### Running from Godot Editor

1. Open the project with Godot Engine 4.3+
2. Open the `main` scene located in the `scenes/` folder
3. Press F5 or click the "Run" button (scene is already set as main scene)

## 📊 Data Source

The application uses publicly available star data from NASA's exoplanet database. The raw data underwent significant processing to be suitable for 3D visualization:

- **Original Format**: CSV files with star distances to exoplanets in radial-like coordinate systems
- **Processed Format**: TXT files with converted 3D coordinates and temperature data
- **Data includes**: Star positions (3D coordinates), star temperatures, multiple exoplanet reference frames

The data processing and coordinate transformation was a crucial part of the project, converting complex astronomical data into a format compatible with Godot's 3D engine.

## 🛠️ Technology Stack

- **Engine**: Godot Engine 4.3+
- **Language**: GDScript
- **Platform**: Windows (primary), Web (experimental)

### Key Dependencies

This project uses the [Godot Starlight](https://github.com/tiffany352/godot-starlight) addon by Tiffany Bennett, which enables efficient rendering of thousands of stars without significant performance impact.

- [Starlight GitHub Repository](https://github.com/tiffany352/godot-starlight)
- [Starlight on Godot Asset Library](https://godotengine.org/asset-library/asset/2221)

## 🖼️ Screenshots

![Normal View](screenshots/app.png.png)
*3D star field visualization*

![Photo Mode](screenshots/photo_mode.png.png)
*Photo mode with custom constellation*

## ⚠️ Known Issues

- Web version is currently unavailable (requires active server)
- Exoplanet switching functionality needs maintenance
- Constellation drawing feature in Photo Mode requires fixes

## 🎯 Future Improvements

- Fix constellation drawing functionality
- Restore exoplanet switching feature
- Implement web version with proper backend
- Add more interactive features (star information, filtering, etc.)

## 👥 Team

- **[Lucio Sepúlveda](https://github.com/Lucio-Sepulveda)** - Lead Godot Developer & Main Programmer
- **[Joaquín Aguirre](https://www.linkedin.com/in/jmaguirre99/)** - Team Leader & Godot Development Support
- **[Daiana Piccard](https://www.linkedin.com/in/daiana-piccard/)** - Data Processing & Conversion
- **[Bruno Breggia](https://www.linkedin.com/in/bruno-maximiliano-breggia-07b773a3/)** - Data Processing & Coordinate Transformation

## 🏆 Recognition

**First Place** - NASA International Space Apps Challenge 2024 (Local Site Winner)

## 📄 License

This project is licensed under the MIT License - see below for details.

### Starlight Addon License

Copyright 2023 Tiffany Bennett

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## 🔗 Links

- [NASA Space Apps Challenge 2024](https://www.spaceappschallenge.org/nasa-space-apps-2024/)
- [ExoSky Challenge Details](https://www.spaceappschallenge.org/nasa-space-apps-2024/challenges/exosky/?tab=details)
- [Godot Engine](https://godotengine.org/)

---

*Developed for NASA International Space Apps Challenge 2024*

