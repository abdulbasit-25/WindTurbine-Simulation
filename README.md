# 🌪️ Wind Turbine Applied Physics Project

> **Interactive 3D Engineering Simulators for Small-Scale Renewable Energy Prototyping.**

This project explores the design, aerodynamics, and concept development of a small-scale Horizontal Axis Wind Turbine (HAWT) for renewable energy generation. The repository contains a suite of interactive HTML prototypes that visualize turbine designs in various presentation styles—ranging from a futuristic dark-mode CAD simulator to a modern, realistic environmental ecosystem interface.

This project bridges the gap between theoretical applied physics, renewable energy engineering, and interactive UI/UX design.

Powered By **ARCHER**: [abdulbasit-archer.vercel.app](https://abdulbasit-archer.vercel.app/)

---

## 📋 Table of Contents

1. [Project Overview](#-project-overview)
2. [Core Features](#-core-features)
3. [Design Variants](#-design-variants)
4. [Physics & Simulation Logic](#-physics--simulation-logic)
5. [How to Use](#-how-to-use)
6. [Repository Structure](#-repository-structure)
7. [Educational Value](#-educational-value)
8. [References](#-references)

---

## 🎯 Project Overview

The main objective of this project is to design a compact wind turbine concept suitable for low-energy applications such as residential backup power, research demonstrations, and educational prototypes.

Rather than relying solely on static diagrams, this project brings the physics to life through interactive 3D web technologies. The system emphasizes:

- Efficient rotor and blade aerodynamics.
- Lightweight material considerations (Carbon Fiber vs. Plastic).
- Real-time power generation telemetry.
- Environmental impact visualization (seasons, weather, air density).

---

## ✨ Core Features

The interfaces include several design and analysis elements inspired by realistic turbine engineering workflows:

- **Real-time 3D Visualization:** Dynamic rotation speed mapped directly to wind speed inputs.
- **Environmental Ecosystem:** Scattered low-poly trees that physically sway based on wind velocity.
- **Seasons & Weather System:** Toggle between Spring, Summer, Autumn, and Winter—changing sky lighting, ground colors, and introducing weather particles (falling leaves/snow).
- **Aerodynamic Overlays:** Particle-based airflow streams that visualize wind hitting the rotor.
- **Structural Stress Map:** Visual heatmap on the turbine hub that glows red when mechanical stress increases at high wind speeds.
- **Live Telemetry Dashboard:** Real-time tracking of RPM, Power Output (Watts), and System Efficiency (%).
- **Live Power Graph:** An oscilloscope-style chart showing power generation over time.
- **Blueprint Mode:** Instantly toggle materials to wireframe to view the structural layout of the turbine.
- **Cost Estimator:** A slide-out Bill of Materials (BOM) panel calculating rough prototype costs.

---

## 🎨 Design Variants

This repository contains three HTML design variants demonstrating different visual directions for the same engineering concept:

- `Design1.html` — **Futuristic Dark Mode:** A high-contrast, space-grade charcoal interface with glowing energy-green data readouts.
- `Design2.html` — **Blueprint Dashboard:** An engineering-focused layout featuring heavy grid lines and technical schematic aesthetics.
- `Design3.html` — **Modern Environmental Simulator:** A clean, light-mode, realistic CAD-style interface featuring dynamic seasons, weather, and environmental physics.

---

## ⚙️ Physics & Simulation Logic

While primarily a design study, the simulations are grounded in real wind energy physics principles. The live telemetry calculates power output using a simplified model of the wind power equation:

`P = 0.5 * ρ * A * v³ * Cp`

Where:

- `ρ` (Air Density): Dynamically changes based on the selected season (e.g., Winter air is denser than Summer air, generating slightly more power at the same wind speed).
- `v` (Wind Speed): Controlled by the user via the wind speed slider.
- `Cp` (Power Coefficient): Modeled to peak at ~35% efficiency around 10 m/s, reflecting realistic small-scale turbine limits.

---

## 🚀 How to Use

1. **Clone or Download** this repository to your local machine.
2. Open any of the `.html` files (`Design1.html`, `Design2.html`, or `Design3.html`) directly in a modern web browser (Chrome, Firefox, Edge, Safari).
3. Use the **Wind Speed Slider** to control the environment.
4. Toggle **Seasons** (in Design 3) to see how air density and weather affect the simulation.
5. Toggle **Airflow** and **Stress Map** to view aerodynamic and mechanical visualizations.
6. Click **Blueprint Mode** to switch from a solid 3D view to a structural wireframe.
7. Click **Export Sheet** to trigger a building-up PDF layout animation.

---

## 📁 Repository Structure

```text
Wind-Turbine---Applied-Physics-Project/
│
├── Design1.html          # Futuristic dark mode simulator
├── Design2.html          # Blueprint dashboard variant
├── Design3.html           # Modern environmental simulator (seasons & weather)
├── README.md             # Project documentation (this file)
│
└── docs/                 # Project documentation and design concepts
```

```

---

## 🎓 Educational Value

This project is highly useful for:

- **Renewable Energy Education:** Visualizing how wind speed translates to electrical power.
- **Applied Physics Demonstrations:** Showing the relationship between air density, velocity, and kinetic energy harvesting.
- **Engineering Design Discussions:** Comparing material choices (weight vs. durability) and structural stress factors.
- **Early-Stage Concept Modeling:** Providing a polished, interactive mockup for class projects or investor pitches.

---

## 📚 References

1. Darwish, S. A. S. K., et al. "Review of Small Wind Turbine Designs and Applications." _Renewable and Sustainable Energy Reviews_, 2013.
2. Elliott, J. B. _Wind Energy Explained: Theory, Design, and Application_. John Wiley & Sons, 2004.
3. Khan, S. A. "Designing a Small Wind Turbine for Sustainable Energy Generation." _Journal of Renewable Energy_, 2020.

---

_Feel free to explore the individual HTML designs and adapt the project further for more advanced simulations or academic presentations._
```
