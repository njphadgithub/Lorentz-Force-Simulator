# Lorentz Force 3D Interactive Simulation & Lab Guide

A self-contained, browser-based 3D educational simulation designed for undergraduate electromagnetics and vector calculus instruction. Built with **Three.js** and **Tailwind CSS**, this interactive application visualizes the **Lorentz Force Law** ($\mathbf{F} = q(\mathbf{E} + \mathbf{v} \times \mathbf{B})$) in real time with color-coded vector annotations and live numerical validation.

Developed for academic use at the **Government College of Engineering, Chh. Sambhajinagar**.

## Creator
* **Dr. Nitin Phadkule**
* **Department:** Electronics and Telecommunication Engineering
* **Institution:** Government College of Engineering, Chh. Sambhajinagar
* **Email:** phadkule@geca.ac.in

---

## Key Features

1. **Real-Time Lorentz Force Calculation:** Computes and displays scalar magnitudes and vector components for:
   * Magnetic Force ($\mathbf{F}_m = q(\mathbf{v} \times \mathbf{B})$)
   * Electric Force ($\mathbf{F}_e = q\mathbf{E}$)
   * Total Lorentz Force ($\mathbf{F}$)
2. **Interactive 3D Viewport (WebGL):** 
   * Fully rotatable, zoomable, and pannable 3D coordinate frame.
   * Color-coded vector arrows for instantaneous visual distinction:
     * 🔴 **Velocity ($\mathbf{v}$)** (Red)
     * 🔵 **Magnetic Field ($\mathbf{B}$)** (Blue)
     * 🟡 **Electric Field ($\mathbf{E}$)** (Yellow)
     * 🔵 **Resultant Lorentz Force ($\mathbf{F}$)** (Cyan)
   * Explicit on-plot text sprites labeling each vector and the central point charge ($\mathbf{Q}$).
   * Dynamic animated motion trail streaming along the particle's velocity trajectory.
3. **Interactive Lab Guide:** Built-in guidance panel explaining what physical phenomena to change and observe (e.g., verifying orthogonal cross-product rules, observing zero magnetic force when $\mathbf{v} = 0$, or isolating electric deflection when $\mathbf{B} = 0$).

---

## Technical Stack

* **HTML5 / CSS3** (Single-file self-contained architecture)
* **Tailwind CSS v4** (Modern styling and responsive layout)
* **Three.js (r128)** (High-performance 3D WebGL rendering engine)

---

## How to Run Locally

1. Clone or download this repository.
2. Ensure your main file is named `index.html`.
3. Double-click `index.html` to open it directly in any modern web browser (Chrome, Edge, Firefox, Safari)—no local server installation required!

---

## License

This educational tool is open-source and intended for academic instruction, laboratory demonstrations, and student self-study in engineering electromagnetics.