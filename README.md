# 🔩 Torque Calculation Project

# First Part of The Task:
This project demonstrates how to calculate torque based on given forces and distances.
---
Each motor is connected to a segment of known length, and the same weight (1 kg) is applied at the end of each segment.



## ⚙️ Torque Values

| Motor   | Distance (m)               | Torque (N·m) |
|---------|----------------------------|--------------|
| Motor 1 | 4                    | 0.04*1Kg = 4 Kg·cm         |
| Motor 2 | 4 + 10 = 14         | 0.14*1Kg = 14 Kg·cm         |
| Motor 3 | 4 + 10 + 15 = 29    | 0.29*1Kg = 29 Kg·cm         |


Based on the torque requirements above, appropriate **servo motors** options are recommended. 
Selection was based on ensuring that each servo’s stall torque is **greater than the required torque** (with safety margin).

| Motor   | Required (Kg·cm) | Recommended Servo Model |
|---------|-----------------:|--------------------------------------|
| Motor 1 | 4                |  Servo Motor SM S4303R (≈5.1 Kg·cm)      |
| Motor 2 | 14               | Dynamixel XL430 (18–21 Kg·cm) | 
| Motor 3 | 29               | Dynamixel MX-series (MX-28 ~25 Kg·cm) |



---

# Second Part of The Task:


## 1️⃣ Can the selected motors lift the weight if gears are added?
Yes ✅, adding gears will multiply the torque output of the motors, making them capable of lifting the required weight even if it exceeds the motor’s direct capacity.



## 2️⃣ Possible Drawbacks
1. **Reduced speed** ⏳ — Increasing torque with gears will lower movement speed.  
2. **Increased weight and size** ⚖️ — Gears add extra mass to the robotic arm.  
3. **Energy loss** 🔋 — Due to friction between gear teeth.  
4. **More complex design** 🛠️ — Requires additional installation and maintenance.



## 3️⃣ Solutions to the Drawbacks
1. Use **lightweight materials** for gears (e.g., carbon fiber or reinforced plastic).  
2. Optimize the **gear ratio** to balance speed and torque.  
3. Apply **lubrication** to reduce friction losses.  
4. Design for **easy access** to gears for quick maintenance.

