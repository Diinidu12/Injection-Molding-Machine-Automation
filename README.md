# 🏭 Injection Molding Machine Automation (PLC)

This project automates the **injection molding process** using a **Programmable Logic Controller (PLC)** programmed with **WinProLadder**.  
The goal is to develop a reliable and safe control system that sequences the operations of an injection molding machine — including mold closing, injection, cooling, and ejection — using sensors and actuators for precise control.

---

## 📘 Project Overview

Injection molding is a manufacturing process used to produce parts by injecting molten material into a mold.  
This project focuses on **automating** the entire process using PLC logic to eliminate manual intervention and ensure consistent quality and safety.

### Objectives
- Design a ladder logic program to fully automate the injection molding cycle.
- Integrate appropriate sensors (input devices) and actuators (output devices).
- Simulate and test the automation process using **WinProLadder** software.
- Ensure safety interlocks and sequential operation control.

---

## 🧩 Ladder Logic Overview

The ladder program defines the automated sequence through **timers**, **interlocks**, and **sequential control logic**.  
Each stage depends on input sensor feedback to ensure the process advances only when conditions are met.  

- **Step 1:** Mold closes and interlock is verified.  
- **Step 2:** Injection cycle begins.  
- **Step 3:** Cooling timer activates.  
- **Step 4:** Mold opens.  
- **Step 5:** Ejector activates to release the product.

---

## 📂 Repository Structure

```
Injection-Molding-Automation/
│
├── Injection_molding_MC.pptx     # Project presentation & requirements
├── Injection_Molding_Ladder.pdx  # PLC ladder program (WIBProLadder file)
├── README.md                     # Project documentation
```

---

## 🧠 How to Use

1. **Open WIBProLadder.**  
2. Load the `.pdx` ladder program file.  
3. Run the simulation or upload it to a compatible PLC.  
4. Follow the sequence diagram from the PowerPoint to verify correct automation steps.

---
