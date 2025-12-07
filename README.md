**Analog Layout · VLSI Design **
Precision • Symmetry • Performance
A complete guide for analog layout engineers with best practices, examples, checklists, and real-world VLSI design notes.


Status Tech Tools License

🌟 Overview
This repository is designed for Analog Layout / VLSI Design Engineers to understand, practice, and master important concepts such as:

Common-centroid & interdigitation
DRC/LVS clean layouts
Matching & symmetry rules
IR drop, mismatch, offset
Guard rings, shielding, WPE
Capacitor types in analog design
Ground bounce, AGND, end-cap effects
🧩 Contents of the Repository
✔ Practical layout examples
✔ Annotated illustrations
✔ Checklists (DRC/LVS/Matching)
✔ Device placement strategies
✔ Advanced routing patterns
✔ Real-world analog layout notes

🧠 Analog Layout Golden Rules
📐 Common-Centroid Layout Example

A1–B1–B2–A2 pattern for optimal mismatch cancellation

⚡ Key VLSI Terminology
Term	Meaning
IR Drop	Voltage drop due to metal resistance
Offset	Unwanted difference between differential pair outputs
Mismatch	Device variations due to process gradients & random effects
Ground Bounce	Noise caused by fast switching currents
WPE	Well Proximity Effect (changes near well edge)
AGND	Clean ground for analog paths
End-cap effect	Poly/diffusion distortion at edges
🛠️ Tools Used
Cadence Virtuoso
Mentor Calibre
KLayout
Python (scripts)
GitHub for documentation
📘 Layout Checklist
✔ Same orientation
✔ Same diffusion edges
✔ Same contact count
✔ Balanced routing
✔ Guard ring symmetry
✔ Poly end-caps
✔ Density uniformity
✔ Dummy devices added
