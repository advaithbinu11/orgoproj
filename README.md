# orgoproj
Here is a comprehensive `README.md` file designed for your project. It covers the technical stack, the chemical principles visualized, and instructions on how to maintain or expand the lab.

---

# 🌀 MS-Explorer: Interactive Mass Spectrometry Lab

**MS-Explorer** is a high-fidelity, interactive educational dashboard designed to visualize the complex dynamics of Organic Mass Spectrometry. By combining modern web aesthetics (Glassmorphism) with accurate chemical fragmentation logic, it allows students and researchers to "see" how molecules break apart inside a mass spectrometer.

---

## 🚀 Features

### 1. Interactive Fragmentation Lab
Visualize four major fragmentation pathways with real-time animations:
* **Alpha-Cleavage:** Watch carbonyl compounds and ethers break one bond away from the radical site to form resonance-stabilized **Acylium ions** ($R-C\equiv O^+$).
* **McLafferty Rearrangement:** A sophisticated simulation of the 6-membered transition state in ketones, showing the ejection of a neutral alkene and the formation of an **Enol Radical Cation**.
* **Sigma-Bond Cleavage:** Visualization of alkane fragmentation favoring the most stable secondary or tertiary carbocations.
* **Inductive Cleavage:** Demonstrates heterolytic cleavage in halogenated compounds driven by electronegativity ("Inductive Pull").

### 2. Isotopic Fingerprint Dashboard
A "cheat sheet" for identifying elements based on their isotopic distributions:
* **Nitrogen Rule:** Logic for odd/even molecular ions.
* **Halogen M+2 Patterns:** Visual ratios for Chlorine (3:1) and Bromine (1:1).
* **Carbon-13 Estimation:** Integrated formula for calculating carbon count: 
    * `#C = Intensity(M+1) / (Intensity(M) * 0.011)`

### 3. High-Fidelity Spectrum Viewer
A custom-built coordinate-based graph that mimics real laboratory data output:
* Accurate $m/z$ spacing (not just even bars).
* Identification of **Base Peaks** and **Molecular Ions**.
* Relative abundance axes and grid lines.

### 4. Atmospheric Design
* **Animated Background:** Floating, twirling alkane chains and aromatic rings provide a professional "lab" feel.
* **State-Aware UI:** Buttons toggle between modes with distinct color-coding (Indigo for primary actions, Pink for rearrangements).

---

## 🛠️ Technical Stack

* **HTML5/CSS3:** Utilizes CSS Grid and Flexbox for a responsive dashboard layout.
* **JavaScript (ES6):** Custom DOM manipulation for fragmentation logic and state management.
* **SVG Animation:** Mathematical pathing for molecular zig-zags and twirling background effects.
* **Glassmorphism:** High-end UI design using `backdrop-filter: blur()` and semi-transparent layers.

---

## 🧪 Chemical Logic References

The simulations within this project are based on standard fragmentation rules used in structure elucidation:

* **Stevenson's Rule:** The positive charge remains on the fragment with the lowest ionization potential.
* **Hybridization Shift:** The Acylium simulation correctly visualizes the shift from $sp^2$ to $sp$ (linear) hybridization during cleavage.
* **Even-Electron Rule:** Explains why McLafferty rearrangements (radical cations) create even-numbered mass peaks.

---

## 📂 Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/ms-explorer.git
    ```
2.  **Open the file:**
    Simply open `index.html` in any modern web browser (Chrome, Firefox, or Edge recommended).

No external dependencies (like jQuery or MathJax) are required, making this an extremely lightweight and fast-loading educational tool.

---

## 📈 Future Roadmap

- [ ] **Interactive Isotope Calculator:** A tool where users input M and M+1 intensities to solve for Carbon count.
- [ ] **Aromatic Pathway:** Visualization of the Trolylium Ion ($m/z$ 91) formation.
- [ ] **Library Mode:** A searchable index of common fragment losses (e.g., $M-15$, $M-18$, $M-29$).

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

**Created with ❤️ for the Organic Chemistry Community.**
