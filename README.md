# Thermodynamic Fluid & Lava Lamp Simulation

This project is an interactive, real-time simulation of a lava lamp, built with HTML, CSS, and JavaScript. It models the thermodynamic principles of a real lava lamp, creating a mesmerizing, fluid visual experience that runs in any modern web browser. The simulation has evolved from a constrained lamp to a full-screen fluid dynamic environment.

## Features

This simulation includes a wide range of features and customizable settings:

**Full-Screen Fluid Dynamics:** The simulation takes over the entire browser window, creating an immersive, abstract visual experience.

**Realistic "Warm-Up" Sequence:** The simulation starts with the wax settled as a single mass at the bottom, which then heats up and breaks apart, mimicking a real lava lamp.

**Thermodynamic Model:** The core of the simulation is a physics engine that models:
    **Heating & Cooling:** Wax heats at the bottom and cools at the top.
    **Buoyancy:** Temperature changes affect the density and buoyancy of the wax, causing it to rise and fall.
    **Convection:** A fluid convection model influences the movement of both the wax and glitter, creating a natural circulatory flow.

**Advanced Wax Dynamics:**
    **Splitting & Merging:** Hot, fast-moving wax blobs can split into smaller, varied spheres. Cooler blobs that touch at the bottom will merge back into a larger mass.
    **Inter-Blob Repulsion:** Blobs push away from each other, creating more complex internal motion.

**High-Performance Rendering:** Uses an efficient metaball rendering technique with adaptive resolution to ensure smooth performance on both desktop and mobile devices.

**Interactive Settings Menu:** A slide-out panel allows for real-time control over the simulation's parameters:
    **Color Theme:** Choose from several curated color palettes.
    **Speed:** Control the overall speed of the simulation.
    **Glitter Volume:** Add and adjust the number of suspended glitter particles.
    **Initial Wax Volume:** Change the amount of wax in the lamp.
    **Heat:** Adjust the intensity of the heat source, affecting wax activity.
    * **Wax Viscosity:** Control how "melty" and fluid the wax appears.
    **Volatility:** Influence how easily the wax blobs split apart.

**Mobile-Friendly:** Designed to be fully responsive and stable on desktop and mobile browsers.

## How to Run

This simulation is self-contained in a single `index.html` file. No server or build process is required.

1. Save the code as `index.html`.

2. Open the file in any modern web browser (e.g., Chrome, Firefox, Safari, Edge).

## Technology Stack

**HTML:** The structure of the page.
**CSS:** Styling for the UI elements, including the settings panel and sliders.
**JavaScript (ES6):** All logic for the physics, rendering, and user interaction is handled in client-side JavaScript.

## Customization

For developers looking to tweak the base parameters, the `config` object at the top of the `<script>` tag contains all the default settings for the simulation, which can be easily modified.
