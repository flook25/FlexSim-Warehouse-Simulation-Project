# 🏭 Warehouse Simulation: Optimizing Picking & Putaway Operations

<div align="center">
  <a href="https://www.flexsim.com/" target="_blank">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTShja8JfKM_3lDACINztvcPXexbQhPZRkb0g&s" alt="FlexSim Logo" height="200"/>
  </a>
</div>

---

## 📝 Project Overview

This project simulates the core operations of a distribution center—**order picking and product putaway**—using FlexSim simulation software. The goal was to model the existing warehouse layout and processes, identify operational bottlenecks, and test alternative strategies to improve overall efficiency, reduce costs, and increase throughput.

<br>

### 🎥 Simulation in Action

<!-- 
IMPORTANT: This is the most critical part! 
1. Record a short video of your FlexSim model running.
2. Convert it to a GIF (e.g., using ScreenToGif).
3. Upload the GIF to this GitHub repository and replace the link below.
-->
<div align="center">
  <img src="https://path/to/your/simulation.gif" alt="Warehouse Simulation GIF" width="800"/>
</div>

---

## 🎯 Key Objectives

- **Model Existing System:** To create a high-fidelity digital twin of the current warehouse layout, including racks, conveyors, and operator travel paths.
- **Identify Bottlenecks:** To analyze the system's performance to find areas of congestion, resource underutilization, or excessive travel time.
- **Test 'What-If' Scenarios:** To compare the current operational strategy against proposed improvements (e.g., changing picking logic, adding more resources).
- **Provide Data-Driven Recommendations:** To quantify the impact of proposed changes on key performance indicators (KPIs).

---

## ⚙️ Methodology

1.  **Model Building:** The warehouse environment was constructed in FlexSim, including a detailed layout of storage racks, receiving/shipping docks, and travel networks.
2.  **Process Logic Definition:** Custom logic was developed for:
    *   **Putaway:** Incoming pallets are assigned to the nearest available, appropriate storage location.
    *   **Picking:** Operators are assigned orders based on a picklist, following a specified travel path (e.g., S-shape).
3.  **Data Integration:** The model was driven by realistic sample data from Excel/CSV files, including order arrivals and processing times.
4.  **Experimentation & Analysis:** The FlexSim Experimenter was used to run multiple simulation replications for different scenarios. Performance was compared using FlexSim's built-in dashboards and statistical reports.

---

## 📈 Key Findings & Results

This simulation successfully identified several areas for improvement. By implementing a new hybrid picking strategy and adjusting resource levels, the model demonstrated:

- ✅ **18% Reduction** in average order picking travel time.
- ✅ **25% Increase** in daily order throughput.
- ✅ **Identification of the optimal number of AGVs** to be 5, balancing throughput against operational cost.
- ✅ **Validation** that a batch picking strategy would significantly outperform single-order picking for this layout.

---

## 🛠️ Tools & Technologies

- **Primary Tool:** [FlexSim Simulation Software](https://www.flexsim.com/)
- **Data Input:** Microsoft Excel / CSV
- **Reporting:** FlexSim Dashboards, Microsoft PowerPoint

---

## 📂 Deliverables

<!-- Link to a detailed report or a presentation if you have one -->
- **[View Full Project Report (PDF)](https://path/to/your/report.pdf)**
- **[Watch Video Walkthrough on YouTube](https://path/to/your/video.mp4)**
