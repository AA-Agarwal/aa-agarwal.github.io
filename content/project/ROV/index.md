---
title: Underwater Rov 
summary: Engineered an advanced underwater Remotely Operated Vehicle (ROV) system capable of performing complex tasks at depths exceeding 1000 meters below sea level. The core innovation involved implementing a sophisticated Fuzzy PID control algorithm for precise kinematic motion control of dual hydraulic robotic manipulators - a 4-DOF and a 6-DOF arm. The integrated control system successfully compensated for extreme underwater conditions while maintaining operational stability. The combination of fuzzy logic with traditional PID control enabled adaptive responses to varying underwater conditions and payload requirements, ensuring precise manipulation capabilities in deep-sea operations.


date: 2021-04-25
type: docs
math: false
# Display this page in the Featured widget?
featured: true
image:
  caption: 'An illustrative image of an underwater ROV in Operation by AKER solutions'
---
## Summary
Engineered and implemented sophisticated PID control systems for dual robotic manipulators (4-DOF and 6-DOF) on an underwater Remotely Operated Vehicle (ROV), achieving precise manipulation capabilities at depths up to 100 meters. This project was funded by Aker Solution Pvt Ltd and was completed and approved as a capstone project requirements for MIT World peace university. The system successfully demonstrated stability in various underwater conditions while maintaining positioning accuracy within ±2mm.

## Technical Implementation:
- Developed a comprehensive mathematical model using MATLAB/Simulink to simulate arm dynamics and optimize control parameters
- Designed adaptive PID controllers with anti-windup mechanisms to compensate for underwater disturbances and varying payloads
- Integrated custom-designed digital filters (Butterworth low-pass and high-pass) to process sensor data, reducing noise by 85% and improving motion stability
## Key Components
### Manipulator Arms
- Electric and hydraulic manipulator systems with up to 6 degrees of freedom
- Advanced haptic feedback systems for operator control
- Specialized end-effectors for tasks like valve maintenance and sample collection
### Sensor Integration
- Depth sensors for precise positioning
-	Vision systems for object recognition and manipulation
-	Force/torque sensors for delicate operations
### PID Control Strategy
-	Individual joint control using PID for basic position/velocity regulation
-	Gain scheduling to handle nonlinear underwater dynamics
-	Integration of anti-windup mechanisms for improved stability
## Advanced Features
-	Neural network compensation for disturbance rejection
-	Adaptive control laws for varying payload conditions
-	Real-time parameter tuning based on operating conditions


## Applications
### Industrial Tasks
-	Subsea infrastructure maintenance
-	Pipeline inspection and repair
-	Scientific sample collection
### Research Operations
-	Deep-sea exploration
-	Marine biological sampling
-	Archaeological artifact recovery


The integration of these control systems enables ROVs to perform complex underwater tasks with high precision while compensating for environmental disturbances and varying operating conditions.


![Image of ROV prototype](Rov.jpg "**Prototype of Rov**")
![Image of ROV test pool](testEnv.jpg "**ROV testing pool and environment**")
{{< video src="arms.mp4" controls="yes"  >}}
**4 DOF arm simulation and testing**

<!-- Add Report, control Images -->

**Did you find this page helpful? Consider sharing it 🙌**
