⚡ Digital Integrated Circuits: Schematic to Layout ⚡ 

Welcome to the repository for ENCS3330: Digital Integrated Circuits. This project showcases the complete design cycle of CMOS logic gates — from ideal transistor schematics to physical silicon layouts.

🎯 task Goals 

The mission was to bridge the gap between theory and reality. We designed three fundamental gates and analysed how real-world parasitics (like resistance and capacitance) slow down digital signals.

🏗️ Logic Gates Designed 

1️⃣ CMOS Inverter

•	Basics: The foundation of all digital logic.
•	Performance: Verified perfect logic inversion (0 ↔ VDD).
•	Discovery: Layout version is slightly slower than schematic due to interconnect and routing capacitance.

2️⃣ 2-Input NAND Gate

•	Design: NMOS transistors in series, PMOS in parallel.
•	Weak Path: Series NMOS makes the pull-down weaker → slower fall time (t_f) compared to inverter.
•	Truth Table: Fully verified; output goes LOW only when both inputs are HIGH.

3️⃣ 3-Input NOR Gate

•	Design: PMOS transistors in series, NMOS in parallel.
•	Challenge: With 3 PMOS in series, rise time (t_r) is significantly slower due to resistive pull-up path.
•	Realism: Layout simulation gives a more accurate real-world timing response than the ideal schematic.
