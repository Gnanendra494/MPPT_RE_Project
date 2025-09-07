# MPPT RE Project

## 📌 Overview
This project focuses on the design and simulation of a **Maximum Power Point Tracking (MPPT)** algorithm for solar energy systems. The main objective is to enhance the efficiency of photovoltaic (PV) systems by ensuring that they operate at their maximum power point under varying environmental conditions.

The project explores and compares different MPPT techniques including **Incremental Conductance** and **Perturb & Observe (P&O)** methods.

---

## 🎯 Objectives
- Implement MPPT algorithms for PV systems in MATLAB/Simulink.
- Compare the performance of **Incremental Conductance** vs **P&O**.
- Analyze the effect of varying solar irradiance and temperature.
- Demonstrate improvements in tracking efficiency and response time.

---

## 🛠️ Methodology
1. **Simulation Environment:** MATLAB/Simulink
2. **MPPT Techniques Implemented:**
   - Perturb & Observe (P&O)
   - Incremental Conductance (IncCond)
3. **System Modeled:**
   - Solar PV Module
   - DC-DC Converter (Buck/Boost)
   - MPPT Controller

---

## 📊 Results
- **P&O Method:**  
  Simple implementation, but oscillates around the maximum power point.  

- **Incremental Conductance Method:**  
  More accurate and stable under rapidly changing irradiance, at the cost of increased complexity.  

Simulation screenshots and result plots are included in the repository:
- `P&O Sim Result.JPG`
- `MPPT Incremental conductance results.JPG`

---

## 📂 Files in this Repository
- `MPPTIncrementalConductance.slx` → Simulink model for Incremental Conductance  
- `mpptbuclboostPandO.mdl` → Simulink model for P&O method  
- `MPPT_Report-2(main).pdf` → Detailed project report (Incremental Conductance)  
- `Solar charge controller with Maximum Power Point Tracking (MPPT)(Report-1).pdf` → Report on P&O method  
- Simulation result images  

---

## 🚀 How to Run
1. Open MATLAB/Simulink.  
2. Load the required model file (`.slx` or `.mdl`).  
3. Run the simulation.  
4. Compare the outputs under varying irradiance and temperature conditions.  

---

## 📖 References
- H. Patel and V. Agarwal, *"Maximum Power Point Tracking Scheme for PV Systems Operating Under Partially Shaded Conditions"*, IEEE Transactions on Industrial Electronics.  
- MATLAB/Simulink Documentation.  

---

## 👤 Author
**K.Gnanendra Reddy**  
BTech CSE  
IIIT Bhubaneswar  

---
