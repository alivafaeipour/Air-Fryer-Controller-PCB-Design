# Air Fryer Controller – PCB Design & Hardware Development

<p align="center">
  <img src="./Images/AI_Project_Cover.jpg" alt="AI-generated Air Fryer Controller project visualization" width="800">
</p>

<p align="center">
  <i>AI-generated project visualization — not a photograph of the actual project.</i>
</p>

An STM32-based air fryer controller featuring PID temperature control and a custom PCB designed in Altium Designer.

This repository documents the hardware development process, including PCB design, PCB fabrication, component assembly, STM32 configuration, and the final assembled board.

> **Note:** This project was originally developed as a university project by a colleague. My contribution focused on PCB design, PCB fabrication, component assembly, and hardware development.

---

## Project Overview

The project is an STM32-based air fryer control system designed to manage the cooking process using temperature feedback and PID control.

The hardware was developed around a custom-designed PCB, followed by physical PCB fabrication and component assembly.

The main focus of this repository is the **hardware development and PCB design process**.

### Main Features

* STM32-based control system
* PID temperature control
* Temperature feedback
* Custom PCB design
* PCB fabrication using chemical etching
* Manual component assembly and soldering
* Hardware prototyping and testing

---

## My Contribution

My main contribution to the project included:

* PCB design using **Altium Designer**
* Component placement
* PCB routing
* PCB layout review
* PCB preparation for fabrication
* PCB fabrication using copper-clad board and chemical etching
* Manual drilling and PCB preparation
* Component soldering and assembly
* Hardware inspection after assembly

The complete firmware source code, Gerber files, and original Altium project files are not included in this repository.

---

## Hardware Design

### Schematic

<p align="center">
  <img src="./Images/Schematic.png" alt="Project Schematic" width="900">
</p>

---

### PCB Layout – 2D

<p align="center">
  <img src="./Images/PCB_2D.png" alt="PCB 2D Layout" width="900">
</p>

---

### PCB Layout – 3D

<p align="center">
  <img src="./Images/PCB_3D_1.png" alt="PCB 3D View 1" width="800">
</p>

<p align="center">
  <img src="./Images/PCB_3D_2.png" alt="PCB 3D View 2" width="800">
</p>

---

## STM32 Configuration

The microcontroller configuration was prepared using **STM32CubeMX**.

<p align="center">
  <img src="./Images/STM32CubeMX.png" alt="STM32CubeMX Configuration" width="900">
</p>

The CubeMX configuration is included to document the microcontroller setup used in the project.

---

## PCB Fabrication

The PCB was physically fabricated using a copper-clad board and a chemical etching process.

The fabrication process included:

1. PCB layout preparation
2. Transfer of the PCB pattern
3. Chemical etching
4. Manual drilling
5. Component placement
6. Soldering and assembly
7. Hardware inspection

This process was used to convert the Altium PCB design into a functional physical prototype.

---

## Final Result

The final assembled PCB is shown below.

<p align="center">
  <img src="./Images/Final_Project_1.jpeg" alt="Final Assembled PCB - View 1" width="800">
</p>

<p align="center">
  <img src="./Images/Final_Project_2.jpeg" alt="Final Assembled PCB - View 2" width="800">
</p>

---

## Tools & Technologies

| Category             | Tool / Technology                    |
| -------------------- | ------------------------------------ |
| PCB Design           | Altium Designer                      |
| MCU Configuration    | STM32CubeMX                          |
| Microcontroller      | STM32                                |
| Control Method       | PID Temperature Control              |
| PCB Fabrication      | Copper-Clad Board + Chemical Etching |
| Assembly             | Manual Soldering                     |
| Hardware Development | PCB Design & Prototyping             |

---

## Repository Structure

```text
Air-Fryer-Controller-PCB/
│
├── README.md
│
└── Images/
    ├── Schematic.png
    ├── PCB_2D.png
    ├── PCB_3D_1.png
    ├── PCB_3D_2.png
    ├── STM32CubeMX.png
    ├── AI_Project_Cover.jpg
    ├── Final_Project_1.jpeg
    └── Final_Project_2.jpeg
```

---

## Project Scope

This repository is intended as a **hardware development portfolio**.

To keep the project focused on the hardware design process, the following files are intentionally not included:

* Complete firmware source code
* Gerber files
* Altium Designer source/project files
* Manufacturing files

The repository instead provides selected documentation and visual references showing the PCB design, fabrication, assembly, and final hardware result.

---

## Disclaimer

This repository documents my contribution to a university project and is intended for portfolio and educational purposes.
