# Speckle Pattern Simulation for Biomedical Imaging

## 📌 Overview

This project focuses on simulating laser speckle patterns using principles of wave optics and Fourier transforms. Speckle patterns arise due to interference of coherent light scattered from rough surfaces or complex media such as biological tissues.

The goal is to understand the statistical and physical behavior of speckle patterns and explore their relevance in biomedical imaging and non-invasive diagnostics.

---

## 🧠 Physics Background

When coherent light (e.g., laser) interacts with a rough or scattering medium, each point introduces a random phase shift. The superposition of these waves leads to constructive and destructive interference, producing a granular intensity pattern known as *speckle*.

Mathematically:
I(x, y) = |Σ Aᵢ e^{iφᵢ}|²

---

## 💻 Methodology

* Generated a 2D random phase distribution
* Modeled the optical field using complex exponential representation
* Applied Fourier transform to simulate far-field interference
* Computed intensity as the squared magnitude of the field

---

## 📊 Results

* Generated realistic speckle intensity patterns
* Observed granular interference structure
* Analyzed intensity distribution using histogram

---

## 🖼️ Sample Output

(Add your generated speckle image here)

---

## 🛠️ Tools & Technologies

* Python
* NumPy
* Matplotlib

---

## 🔬 Applications

* Biomedical imaging
* Blood flow analysis (dynamic speckle)
* Non-invasive diagnostic techniques
* Optical sensing systems

---

## 🚀 Future Work

* Simulate dynamic speckle for flow measurement
* Apply basic machine learning for pattern analysis
* Extend model to realistic biological tissue scattering

---

## 👨‍🔬 Author

**Biswaranjan Mallick**
M.Sc. Physics, IIT Ropar
Interested in Medical Physics, Optical Systems & Health-Tech

GitHub: https://github.com/BiswaMalik
