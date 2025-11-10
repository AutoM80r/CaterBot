# 🚜 Project CATERBOT: Modular Agricultural Robot Simulation in Unity 3D

## ✨ Overview

This repository documents my **Final Year Minor Project** focusing on the redesign, structural validation, and simulation of the caterpillar-tracked agricultural robot, **CATERBOT**. The core achievement is the conversion of the original transport-only vehicle into a multi-functional platform capable of **soil cultivation**, demonstrated through a professional **Unity 3D simulation**.

---

## ⚙️ Engineering & Design Highlights

### 1. **Modularity Implementation**
The original CATERBOT was structurally modified to introduce versatility:
* **Original Challenge:** The robot was limited to coconut transportation.
* **Solution:** The bulky cargo bin was removed, and a custom **Universal Mounting Plate** was designed and integrated into the aluminium chassis. This standardized interface allows for quick attachment of various agricultural implements, fulfilling the goal of a customizable robot.

### 2. **Cultivator Attachment: Design and Robustness**
A fixed-depth, rigid-tine cultivator was designed as the proof-of-concept implement.

| Feature | Detail | Engineering Rationale |
| :--- | :--- | :--- |
| **Type** | Fixed-Depth Cultivator | Simplifies control and ensures consistent tillage depth for simulation and validation. |
| **Frame Reinforcement** | **Heavy Cross-Tubing & Diagonal Bracing** | **Crucial for Static Strength.** Added to resist high **torsional and bending stresses** (Traction force) from soil drag, ensuring the frame remains rigid. |
| **Material (Conceptual)** | Structural Steel for frame, High-Strength Steel for tines | Selected for high **yield strength** and wear resistance against soil impact. |
| **Working Width**| ~0.65 meters | Optimized to fit efficiently between the robot's existing tracks. |

### 3. **Structural Validation (ANSYS)**
The design integrity was validated to ensure structural safety under real-world operating loads.
* **Existing Validation:** The base chassis (aluminium) is proven to safely carry a static payload of **$80\text{ kg}$** (Max Stress: $11.54\text{ MPa}$).
* **New Validation (Tilling Load Case):** The reinforced cultivator and its connection points are validated against the maximum **Drawbar Pull Force** required for tilling, confirming that the entire assembly maintains an appropriate **Factor of Safety (FOS)**.

---

## 🎬 Unity 3D Simulation & Demonstration

The core demonstration uses a physics-based simulation in Unity 3D to visualize the robot's performance.

### 1. **Simulation Platform**
* **Engine:** Unity 3D (Used for visualization, environment physics, and dynamic movement).
* **Models:** Final SolidWorks CAD assemblies were exported and imported.

### 2. **Simulation Video**

The video demonstrates the CATERBOT autonomously moving across a field while the reinforced cultivator effectively tills the virtual ground, showcasing the successful implementation of the modular design.

**[(https://youtu.be/G9RHZ5Birs4)]**

```markdown
<p align="center">
  <a href="[(https://youtu.be/G9RHZ5Birs4)]">
    <img src="[PASTE YOUR VIDEO THUMBNAIL IMAGE URL HERE]" alt="Caterbot Cultivation Simulation" width="70%">
  </a>
  <br>
  **Click the image above to watch the full SIMULATION VIDEO on YouTube.**
</p>
