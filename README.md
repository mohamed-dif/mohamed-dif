<h1 align="center">Hi, I'm Mohamed Dif 👋</h1>

<h3 align="center">
Mechanical Engineer | Green Hydrogen Technology M.Sc. | CFD, CAD & Thermal Systems
</h3>

<p align="center">
  <img src="https://img.shields.io/badge/ANSYS-Fluent-FFB71B?style=for-the-badge">
  <img src="https://img.shields.io/badge/ANSYS-Mechanical-FFB71B?style=for-the-badge">
  <img src="https://img.shields.io/badge/Python-Scientific%20Computing-3776AB?style=for-the-badge">
  <img src="https://img.shields.io/badge/MATLAB-Numerical%20Modeling-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/SolidWorks-CAD-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Hydrogen-Thermal%20Systems-green?style=for-the-badge">
</p>

---

## 👨‍🔬 About Me

I am a Mechanical Engineer and Master's student in **Green Hydrogen Technology** at TH Rosenheim.

I develop engineering solutions by connecting:

- Computational Fluid Dynamics
- Thermodynamics and heat transfer
- Hydrogen-system modelling
- Mechanical design and CAD
- Finite-element analysis
- Python and MATLAB
- Experimental and numerical validation

My work covers the full engineering workflow:

> **Define the physics → design the geometry → build the model → verify the solution → interpret the results**

---

## 🚀 My Projects

### 1. Rotating-Wheel Hydrocyclone CFD

Research project conducted with an industrial partner and TH ROSENHEIM Funded by ZIM to investigate a hydrocyclone equipped with an internal rotating wheel for improving fine-particle separation.

The engineering work included:

- Reverse-engineered the industrial hydrocyclone and reconstructed its internal geometry from the available drawings, dimensions and component information.
- Prepared and simplified the CAD geometry for CFD by repairing surfaces, removing unnecessary features and extracting the internal fluid domain.
- Developed interchangeable geometry configurations for the conventional hydrocyclone and the modified design containing an internal rotating wheel.
- Created parametric wheel variants to investigate wheel diameter, length, position and rotational speed.
- Generated computational meshes with local refinement in the inlet, vortex, wheel, overflow and underflow regions.
- Performed mesh-independence and time-step sensitivity studies to evaluate numerical reliability.
- Implemented multiphase particle tracking using the Discrete Phase Model.
- Applied MRF and transient sliding-mesh methods to represent the rotating-wheel motion.
- Investigated the effects of inlet velocity, particle diameter and wheel RPM on particle trajectories and separation behaviour.
- Evaluated separation efficiency, pressure drop, turbulence, flow structure and particle distribution between the overflow and underflow outlets.
- Developed Python and MATLAB post-processing workflows for comparing simulation cases and calculating particle-separation performance.
- Created an interactive three-dimensional visualization for communicating the hydrocyclone geometry, operating parameters and predicted separation results.

The objective is to understand how the rotating wheel affects particle trajectories, centrifugal forces and the separation of fine particles in viscous multiphase flows.

---

### 2. Hydraulic Draw-Cushion Press Design

Bachelor-thesis engineering project converting a single-action hydraulic press into a double-action deep-drawing press with a hydraulically operated draw cushion.

The project included:

- Mechanical concept development
- Hydraulic-cylinder and draw-cushion design
- Blank-holder and drawing-force calculations
- Complete CAD assembly
- Manufacturing and technical drawings
- Lower-plate sizing under a 50 kN load
- Tie-rod selection and preload evaluation
- Hydraulic-pressure and cylinder-capacity calculations
- Static structural analysis using ANSYS Mechanical
- Equivalent-stress and total-deformation assessment
- Interactive analytical digital-twin development

A 25 mm lower-plate thickness was selected, and M18 tie rods satisfied the combined loading requirements. The structural simulation predicted a maximum frame deformation of approximately **0.162 mm**.

---

### 3. [PEM Electrochemical Cell Post-Processing](https://github.com/mohamed-dif/electrochemical-cell-postprocessing)

<p align="center">
  <a href="https://github.com/mohamed-dif/electrochemical-cell-postprocessing">
    <img
      src="https://raw.githubusercontent.com/mohamed-dif/electrochemical-cell-postprocessing/main/references/electrochemical-postprocessing-demo.gif"
      alt="Animated PEM electrochemical-cell post-processing demonstration"
      width="900">
  </a>
</p>

A reproducible engineering post-processing workflow for a layered PEM electrochemical cell using Python, MATLAB and an interactive HTML workstation.

The project includes:

- Electric-potential field visualization
- Phase-1 volume-fraction analysis
- Volumetric transfer-current integration
- Anode and cathode catalyst-layer balance checks
- Streamwise current-uniformity evaluation
- Through-plane profile extraction
- Zone-by-zone statistical analysis
- Python and MATLAB engineering reports
- Interactive field selection and contour interrogation
- Downloadable zone-audit results
- Automated `PASS` and `REVIEW` quality checks

The demonstration case reproduces a potential range of **0.000–1.730 V**, a phase-fraction range of **0.000–0.998**, and a selected catalyst-layer transfer-current integral of **3.116622 A**.

🔗 **[View Repository](https://github.com/mohamed-dif/electrochemical-cell-postprocessing)**  
🌐 **[Open Interactive Website](https://mohamed-dif.github.io/electrochemical-cell-postprocessing/)**

---

### 4. [Hydrogen Thermal Digital Twin](https://github.com/mohamed-dif/hydrogen-thermal-digital-twin)

<p align="center">
  <a href="https://github.com/mohamed-dif/hydrogen-thermal-digital-twin">
    <img
      src="https://raw.githubusercontent.com/mohamed-dif/hydrogen-thermal-digital-twin/main/assets/piston_compression.gif"
      alt="Animated hydrogen piston-compression digital twin"
      width="900">
  </a>
</p>

A multi-fidelity investigation of transient hydrogen compression and tank filling, connecting first-principles thermodynamics with scientific programming and CFD.

The workflow combines:

- Analytical thermodynamic equations
- Constant-property ideal-gas modelling
- Variable-heat-capacity models
- CoolProp real-gas properties
- Python reduced-order models
- MATLAB numerical models
- ANSYS Fluent transient CFD
- Moving piston and dynamic mesh motion
- Pressure and temperature history comparison
- Compression-work calculations
- Mesh and time-step verification
- Endpoint consistency auditing
- Fast hydrogen-tank filling analysis

The project compares pressure, temperature, compression work and real-gas effects across several modelling fidelities. It also demonstrates how automated consistency checks can identify disagreements between reported CFD endpoints, compression ratio and conservation equations.

🔗 **[View Repository](https://github.com/mohamed-dif/hydrogen-thermal-digital-twin)**

---

### 5. [Methane–Air Combustion CFD](https://github.com/mohamed-dif/Methane-Air-Combustion-CFD)

<p align="center">
  <a href="https://github.com/mohamed-dif/Methane-Air-Combustion-CFD">
    <img
      src="https://raw.githubusercontent.com/mohamed-dif/Methane-Air-Combustion-CFD/main/assets/preview.png"
      alt="Methane-air combustion temperature-field preview"
      width="900">
  </a>
</p>

A two-dimensional methane–air reacting-flow study presented through Python, MATLAB and a standalone interactive HTML dashboard.

The project covers:

- Static-temperature contours
- Velocity-magnitude analysis
- Methane mass-fraction distribution
- Oxygen-consumption analysis
- Carbon-dioxide formation
- Nitric-oxide pollutant prediction
- Fuel and air velocity effects
- Equivalence-ratio sensitivity
- Mixing-intensity evaluation
- Cross-section averaged axial profiles
- Python, MATLAB and browser-based visualization
- Comparison with ANSYS Fluent reference contours

The workflow connects combustion CFD with scientific programming, emissions interpretation and engineering visualization. The current interactive model reconstructs the supplied Fluent field topology for post-processing demonstrations and qualitative parameter studies.

🔗 **[View Repository](https://github.com/mohamed-dif/Methane-Air-Combustion-CFD)**
🌐 **[Open Interactive Website](ttps://mohamed-dif.github.io/Methane-Air-Combustion-CFD//)** h
---

### 6. Reverse-Osmosis Membrane Test Bench

Experimental and analytical investigation of two reverse-osmosis membranes for water-treatment applications related to green-hydrogen production.

The work included:

- Experimental test-bench operation
- Salt-rejection measurements
- Permeate-flux evaluation
- Feed-pressure sensitivity
- Concentration-effect analysis
- Conductivity-data processing
- Membrane-performance comparison
- Water-treatment system sizing
- Electrolyser water-demand calculations
- Experimental uncertainty and result interpretation

The study connected laboratory membrane measurements with the water-quality and flow-rate requirements of a full-scale electrolysis system.

---

### 7. Thermoelectric Generator for Liquid-Hydrogen Propulsion

Master's-thesis project focused on recovering thermal energy from the large temperature difference available in liquid-hydrogen propulsion and cryogenic fuel systems.

The planned engineering workflow includes:

- Thermodynamic feasibility analysis
- CAD concept development
- Thermal-path and heat-exchanger design
- CFD simulation
- Thermoelectric-material selection
- Thermal-contact resistance analysis
- Electrical-power prediction
- Test-bench development
- Instrumentation and data acquisition
- Experimental validation
- Comparison between numerical and experimental results

The objective is to investigate whether cryogenic hydrogen can provide useful thermoelectric power while supporting thermal management within a hydrogen-propulsion system.

## 🛠️ Engineering Toolkit

### CFD and Simulation

`ANSYS Fluent` `ANSYS Mechanical` `SolidWorks Flow Simulation`  
`Dynamic Mesh` `MRF` `Sliding Mesh` `DPM` `VOF`  
`Species Transport` `Electrolysis` `Multiphase Flow`

### Scientific Programming

`Python` `MATLAB` `NumPy` `SciPy` `Pandas`  
`Matplotlib` `CoolProp` `ParaView` `LaTeX`

### CAD and Mechanical Design

`SolidWorks` `CATIA` `AutoCAD`  
`Technical Drawings` `Hydraulic Systems` `Machine Design`

### Engineering Analysis

`Thermodynamics` `Heat Transfer` `Fluid Mechanics`  
`Real-Gas Modelling` `FEA` `Verification & Validation`

---

## 🔬 Research Interests

- Hydrogen compression and storage
- Liquid-hydrogen thermal management
- Electrolysers and fuel-cell systems
- Thermoelectric energy recovery
- Turbulent and multiphase CFD
- Particle-separation equipment
- Membrane water treatment
- Digital twins and reduced-order modelling
- Scientific programming for engineering

---

## 📈 Current Development

- Advancing Python and MATLAB for CFD post-processing
- Developing reproducible engineering workflows
- Improving real-gas hydrogen models
- Building publication-quality technical reports
- Extending CFD projects with automated validation

---

## 📫 Contact

- **Email:** mohameddiff.md@gmail.com
- **GitHub:** [mohamed-dif](https://github.com/mohamed-dif)
- **Main portfolio:** [Hydrogen Thermal Digital Twin](https://github.com/mohameddiffmd-dotcom/hydrogen-thermal-digital-twin)

---

<p align="center">
  <b>Mesh. Solve. Verify. Validate. Improve. Repeat.</b>
</p>

<p align="center">
  <i>Residuals are dropping. Confidence is rising.</i>
</p>
