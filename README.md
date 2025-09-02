# Ex No: 02 - Design & Implementation of Full Custom 2:1 MUX using Cadence EDA Tools

## Aim

The aim is to design and simulate a full custom 2:1 multiplexer (MUX) using Cadence EDA tools, ensuring accurate logic operation through waveform analysis and verification.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment
- Open the Cadence Virtuoso tool and set up the working library.
- Create a new schematic cell view for the 2:1 MUX design.

### 2. Schematic Design
- Select NMOS and PMOS transistors from the library.
- Implement the following logic equation for the 2:1 MUX output:  
  **Y = (A · S′) + (B · S)**
- Connect the respective transistors to form the desired logic.
- Assign input voltage sources for control signal (S) and data inputs (A and B).

### 3. Simulation
- Verify the schematic design for connection errors.
- Launch the Analog Design Environment (ADE).
- Configure transient analysis to observe switching behavior.
- Set simulation parameters such as voltage levels, sweep range, and step size.
- Use Spectre simulator to perform the analysis.

### 4. Waveform Analysis
- Observe the output waveform to ensure correct MUX functionality.
- Confirm that the output reflects the selected input (A or B) based on the control signal (S).

## Circuit Diagram


### 1. Schematic of Full Custom 2:1 MUX
![WhatsApp Image 2025-09-02 at 14 09 41_b7fc427d](https://github.com/user-attachments/assets/644133c7-01d3-4e48-891d-647c671a7bc1)



### 2. Transient Response Setup

![WhatsApp Image 2025-09-02 at 13 49 21_19efe27b](https://github.com/user-attachments/assets/c232ef0b-4134-4c19-a61e-684004146542)


### 3. Transient Analysis Output
![WhatsApp Image 2025-09-02 at 13 49 21_21b6c683](https://github.com/user-attachments/assets/1f2c3a24-5f75-4c25-81c4-fca888d4d912)


## 4.Output
![WhatsApp Image 2025-09-02 at 14 09 40_ff1d779e](https://github.com/user-attachments/assets/aa65625c-6d6f-4026-b6ae-d2c40e5064e0)


## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
