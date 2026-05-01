# MoleculeMotion AR

MoleculeMotion AR is an immersive, browser-based Augmented Reality application that allows users to visualize and interact with 3D molecular structures using hand gestures. Built with Three.js and MediaPipe, it transforms a standard webcam into a spatial controller for chemistry education.


# Features

•	Hand-Gesture Control: Complete "Touchless" interface—no mouse or keyboard required.
•	Scientific Accuracy: Visualizes atomic radii, standard CPK coloring, and molecular geometries.
•	Detailed Chemistry Data: Hover over atoms to see Atomic Number, Mass, and Hybridization states.
•	Interactive AR HUD: A futuristic Head-Up Display (HUD) provides real-time feedback on detected gestures and molecular info.
•	Spatial Audio: Procedurally generated "space-ambient" soundscapes and UI sound effects that respond to your movements.


# Control Scheme

The application uses advanced skeleton tracking to map your hand movements to 3D actions:
Gesture	Action


🖐  Open Palm	Rotate & Zoom: Move your hand to spin the molecule. Twist your hand (like a dial) to zoom in/out.
🤏  Pinch	Axis Lock: Pinch an atom to set it as the center of rotation (Pivot).
✌️  Peace Sign	Atom Selector: A crosshair appears. Hover over spheres to view chemical properties.
🖖  2-Fingers Joined	Bond Selector: Hover over connectors to see bond lengths and types (e.g., Sigma bonds).
✊  Fist	System Reset: Resets the camera, rotation, and scale to the default view.


# Included Molecules

Explore a variety of molecular geometries, including:
•	Simple: Water , Methane , Carbon Dioxide
•	Organic: Ethanol , Benzene with visualized ‭pi‬-electron clouds.
•	Complex/Hypervalent: Xenon Tetrafluoride , Xenon Hexafluoride .


# Technical Stack

•	Rendering: Three.js (WebGL)
•	Hand Tracking: Google MediaPipe Hands
•	UI Layers: CSS2DRenderer (for labels and popups)
•	Audio Engine: Web Audio API (Procedural Oscillators)


# Requirements & Setup

Browser Compatibility (Crucial)
•	macOS/iOS: Requires Safari.
•	Why? Most Chromium-based browsers (Chrome, Edge) block camera access for "Local Files" due to strict Cross-Origin (CORS) security policies. Safari allows local camera stream access, making it ideal for running this .html file directly from your desktop.
Getting Started
	1.	Download the index.html file.
	2.	Right-click the file and select Open With > Safari.
	3.	Allow Camera permissions when prompted.
	4.	Stand roughly 2–3 feet back from the camera for best tracking results.


# Educational Concepts Visualized

The application demonstrates several core chemical principles:
•	VSEPR Theory: Observe how electron repulsion shapes the 3D geometry (e.g., the Tetrahedral shape of Methane).
•	Atomic Properties: Real-time data on mass and atomic radii based on the periodic table.
•	Bonding: Visualizes the spatial relationship and distances between bonded nuclei.

