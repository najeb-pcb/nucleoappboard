# STM32 Nucleo Application Board

A custom STM32 **Nucleo-compatible application board** designed for education, rapid prototyping, and embedded systems experimentation.  
This board extends the STM32 Nucleo platform with commonly used peripherals and interfaces suitable for laboratory exercises, student projects, and applied research work.

---

## 📌 Project Overview

The **STM32 Nucleo Application Board** is developed to:
- Support hands-on learning for STM32 microcontrollers
- Serve as a reusable application board across multiple STM32 Nucleo variants
- Provide a stable hardware platform for embedded firmware development and testing

The design is created using **KiCad** and follows good hardware documentation and version control practices.

---

## 🔧 Key Features

- STM32 **Nucleo header compatible**
- Designed for **educational and prototyping** use
- Breakout access to essential MCU peripherals
- Suitable for:
  - GPIO, ADC, PWM experiments
  - UART, I²C, SPI communication exercises
  - Embedded systems and microcontroller coursework
  - Rapid firmware and hardware validation

> Exact peripherals and features depend on the current schematic revision.

---

## 📁 Repository Structure

.
├── STM32AppBoard.kicad_sch # Schematic design
├── STM32AppBoard.kicad_pcb # PCB layout
├── STM32AppBoard.kicad_pro # KiCad project file
├── .gitignore
└── README.md


> KiCad auto-backups, cache files, and local configuration files are intentionally excluded from version control.

---

## 🛠️ Design Tools

- **EDA Software:** KiCad (version 6 or later recommended)
- **Target MCU Platform:** STM32 Nucleo series
- **Operating Systems Tested:** macOS, Linux

---

## 🚧 Project Status

- **Schematic:** In progress (iterative refinement)
- **PCB Layout:** In progress
- **Fabrication:** Not yet released
- **Firmware:** Not included in this repository

---

## 🔄 Versioning Strategy

- PCB and schematic revisions will follow tagged releases  
  (e.g. `v1.0-pcb`, `v1.1-hardware`)
- Only fabrication-relevant files will be included in releases
- Backup ZIP files are excluded to keep the repository clean and maintainable

---

## 📦 Planned Additions

- PCB renders and schematic PDFs
- Fabrication-ready Gerber files
- Bill of Materials (BOM)
- Example firmware projects
- Hardware usage notes for teaching and labs

---

## 👤 Author

**Mohd Najeb Bin Jamaludin**  
Embedded Systems • Electronics • Education & Prototyping

---

## 📜 License

License to be defined.  
Until specified, this project is shared for **educational and non-commercial reference**.

