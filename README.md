# Wind Turbine Applied Physics Project

Interactive 3D engineering prototypes for exploring the design and physics of a small-scale horizontal-axis wind turbine (HAWT).

The project combines renewable-energy concepts, browser-based visualization, and interface design. Each standalone HTML prototype presents the same general turbine concept through a different visual and simulation direction.

Powered by [ARCHER](https://abdulbasit-archer.vercel.app/).

## Contents

- [What is included](#what-is-included)
- [Run the prototypes](#run-the-prototypes)
- [Prototype variants](#prototype-variants)
- [Simulation model](#simulation-model)
- [Learning goals](#learning-goals)
- [Repository structure](#repository-structure)
- [References](#references)

## What is included

- Interactive 3D turbine visualization in the browser.
- Wind-speed controls connected to rotor motion and telemetry.
- Live readings for RPM, generated power, and efficiency.
- Airflow and structural-stress visualizations.
- Blueprint or wireframe views for inspecting the turbine structure.
- Environmental simulation elements such as seasons, air density, lighting, terrain, trees, and weather particles.
- Prototype cost estimation and export-sheet interactions where supported by the selected variant.
- A presentation deck and written report for the wider project context.

## Run the prototypes

No build tools or installation are required.

1. Download or clone this repository.
2. Open one of the HTML files in a current browser such as Chrome, Edge, Firefox, or Safari.
3. Adjust the wind-speed control and explore the available visualization toggles.

The prototypes load Tailwind CSS and fonts from CDNs, so an internet connection may be needed for their complete visual styling. The core HTML files can still be opened directly from the filesystem.

## Prototype variants

The filenames currently use the existing `Desgin` spelling:

| File                           | Focus                                                  |
| ------------------------------ | ------------------------------------------------------ |
| [`Desgin1.html`](Desgin1.html) | Futuristic dark-mode turbine simulator and designer.   |
| [`Desgin2.html`](Desgin2.html) | AEROSIM 3D dashboard with a technical dark interface.  |
| [`Desgin3.html`](Desgin3.html) | AEROSIM 3D environmental wind-physics simulator.       |
| [`Desgin4.html`](Desgin4.html) | Additional AEROSIM 3D environmental simulator variant. |

## Simulation model

The telemetry uses a simplified wind-power relationship:

$$P = \frac{1}{2} \rho A v^3 C_p$$

Where:

- `P` is estimated power output in watts.
- `rho` is air density in kilograms per cubic metre.
- `A` is the rotor swept area in square metres.
- `v` is wind speed in metres per second.
- `Cp` is the power coefficient, representing the fraction of wind energy captured by the turbine.

Because power scales with the cube of wind speed, small changes in wind speed can produce large changes in the estimated output. Environmental variants also use seasonal conditions to vary air density and the surrounding scene.

These prototypes are educational visualizations rather than calibrated engineering or safety-analysis tools. Their results should not be used for construction, procurement, or performance certification.

## Learning goals

This project is intended to help demonstrate:

- How wind speed and air density affect available energy.
- Why turbine efficiency is limited by the power coefficient.
- The relationship between rotor motion, telemetry, and environmental inputs.
- Early-stage tradeoffs between materials, structure, cost, and presentation.

## Repository structure

```text
Wind-Turbine---Applied-Physics-Project/
├── Desgin1.html       # Futuristic turbine simulator
├── Desgin2.html       # Technical AEROSIM dashboard
├── Desgin3.html       # Environmental simulator
├── Desgin4.html       # Additional environmental variant
├── Presentation.pptx  # Project presentation
├── Report.docx        # Project report
└── README.md          # Project documentation
```

## References

1. Darwish, S. A. S. K., et al. "Review of Small Wind Turbine Designs and Applications." _Renewable and Sustainable Energy Reviews_, 2013.
2. Elliott, J. B. _Wind Energy Explained: Theory, Design, and Application_. John Wiley & Sons, 2004.
3. Khan, S. A. "Designing a Small Wind Turbine for Sustainable Energy Generation." _Journal of Renewable Energy_, 2020.

```

```
