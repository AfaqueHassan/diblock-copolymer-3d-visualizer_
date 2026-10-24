# diblock-copolymer-3d-visualizer_
# 🧪 Interactive 3D Diblock Copolymer Microphase Visualizer (Cell Dynamics Simulation - CDS)

A high-performance WebGL-based 3D interactive visualizer for Cell Dynamics Simulation (CDS) of Diblock Copolymer systems under polar and cylindrical mesh confinement. This application simulates and renders complex self-assembled microphase morphologies predicted by the Finite Difference Method (FTCS 9-point polar stencils) across various boundary confinement conditions.

Developed for academic research verification, paper figure inspection, and interactive phase-diagram exploration in collaboration with research work from **Shah Abdul Latif University (SALU), Khairpur**.

---

## 🌟 Key Features

- **All-in-One Multi-Model Dashboard:** Switch seamlessly between 6 key thesis figure experiments (Fig 14, 16, 18, 22, 23, and 24).
- **Real-Time Interactive CDS Sliders:** Adjust order parameter ($\tau$), block fraction ratio ($f$), diffusivity ($D$), interior pore radius ($r_a$), and surface boundary mode ($\alpha = 0$ / $\alpha = 0.2$) dynamically in real-time.
- **12 Standard Angular Projection Presets ($a$ to $l$):** One-click camera alignment for Front, Back, Top, Bottom, Left, Right, Diagonal, Off-Diagonal, Off-Front, Off-Back, Top-Bottom, and Off-Bottom views.
- **Laptop-Safe GPU Optimization:** Built using WebGL custom fragment shaders and Three.js `InstancedMesh` rendering to guarantee 60 FPS performance without heating or straining system hardware.

---

## 🔬 Scientific & Numerical Parameters Supported

The interactive suite reflects Cell Dynamics Simulation (CDS) parameters across multiple research sections:
- **Phase Order Parameter ($\psi$) & Free Energy Functionals**
- **Cylindrical Mesh & Interfacial/Neutral Wall Confinements ($\alpha = 0, \alpha = 0.2$)**
- **Equilibrium Time Steps ($t = 1,000,000$)**
- **Spatial Step Intervals:** $\Delta r = 0.1$, $\Delta \theta = 2\pi / 360$

---

## 🖼️ Included Research Morphological Figures

1. **Figure 14 (Section 4.2):** Lamellae Forming System confined in Neutral Surfaces ($\alpha = 0$).
2. **Figure 16 (Section 4.4):** Cylindrical Forming System confined in Cylindrical Pores.
3. **Figure 18 (Section 4.6):** Spherical Forming System confined in Spherical Pores.
4. **Figure 22 (Section 4.8):** Cylindrical Forming System in Interfacial Perforated Walls.
5. **Figure 23 (Section 4.10):** Cylindrical Helical Rings on Attractive Wall Confinement ($\alpha = 0.2$).
6. **Figure 24 (Section 4.12):** Spherical Microdomains / Bead Confinement on Attractive Wall.

---

## 🛠️ Tech Stack & Dependencies

- **Frontend & Styling:** HTML5, CSS3, Tailwind CSS
- **3D Engine:** Three.js (WebGL, Custom GLSL Shaders, Instanced Mesh)
- **Camera & UI Controls:** OrbitControls.js, Lucide Icons
- **Supported Editors/Platforms:** Sublime Text, VS Code, Web Browsers (Chrome, Firefox, Edge, Safari)

---

## 🚀 How to Run Locally
1. Click on link provided:https://afaquehassan.github.io/diblock-copolymer-3d-visualizer_/
2. if you are using in Mobile you should Mode on desktop in site then it will be abte to good working, otherwise you are in laptop then  it will be able to working good
---

## 👨‍💻 Developer & Contributor Profile

- **Lead Developer:** Afaque Ahmed
- **Role:** Web & AI Developer
- **Department:** Department of Artificial Intelligence
- **Institution:** Aror University of Art, Architecture, Design and Heritage, Sukkur, Sindh, Pakistan
- **Contact:** +92 309 1351482
- **Services:** Available for Thesis 3D Visualizations, Scientific Web Apps, and AI/Web Projects.

---

## 📄 Research Context & Citation

Mathematical formulation, partial differential equations (PDEs), and CDS FTCS discretization based on published research by:
*Muhammad Javed Iqbal, Inayatullah Soomro, Maryam Bibi, and Rab Nawaz Mallah* (*VFAST Transactions on Mathematics*).
