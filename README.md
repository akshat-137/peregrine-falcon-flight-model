# Peregrine Falcon Flight Model – Simulink

This repository contains a MATLAB Simulink model that simulates the stoop dive of the **Peregrine Falcon**, the fastest bird on Earth. The model calculates the bird’s velocity and altitude during freefall, accounting for aerodynamic drag and gravity.

## 🛠 Features
- Realistic drag modeling with conditional switching (low ↔ high drag)
- Continuous velocity and height tracking
- MATLAB Online + Simulink implementation

## 🧩 Simulink Block Diagram

This is the core model architecture, created in MATLAB Simulink. It simulates the peregrine falcon's dive with dynamic drag switching:

![ Model ](peregrine_falcon_model_diagram.png)


## 📊 Output
![Scope Output](scope_output.png)

*Velocity and height vs. time, from the Simulink Scope block*

## 📁 Files Included
- `Peregrine_Falcon_Model.slx` – Main Simulink model
- `README.md` – Project overview
- `scope_output.png` – Simulation graph

## 📌 Requirements
- MATLAB R2025a
- Simulink toolbox

## 🧠 Author
**Akshat Gupta**  
[LinkedIn Profile](www.linkedin.com/in/akshat-gupta-9b649a378)  
