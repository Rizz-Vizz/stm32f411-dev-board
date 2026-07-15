<div align="center">
  
# STM32F411 Development Board

![Altium Designer](https://img.shields.io/badge/Altium_Designer-A5C85A?style=for-the-badge&logo=altium&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)

<i>This repository contains the hardware design files for a custom, Altium Designer-based STM32F411 development board. The project encompasses the complete PCB design lifecycle, including schematic capture, component selection, routing, and manufacturing data generation.</i>
</div>


## Hardware Specifications

- **Microcontroller**: STMicroelectronics STM32F411 (ARM Cortex-M4)
- **Sensor**: TDK InvenSense MPU-6050 (6-Axis IMU) via I2C interface
- **Power Architecture**: 5V (USB) to 3.3V via on-board LDO regulator
- **Connectivity**: Micro-USB (Power and Data)
- **Debug Interface**: Serial Wire Debug (SWD)
- **PCB Stackup**: 4-Layer design for optimal signal integrity and EMI mitigation


## Visual Documentation

### Schematic
![Schematic 1](images/Screenshot%20(816).png)
![Schematic 2](images/Screenshot%20(817).png)
![Schematic 3](images/Screenshot%20(818).png)
![Schematic 4](images/Screenshot%20(819).png)


### PCB Layout (2D)
![PCB 2D View](images/Screenshot%20(812).png)

### 3D Render
![3D View](images/Screenshot%20(811).png)

## Repository Structure

- `/Project_Files`: Altium Designer project and source documents (`.PrjPcb`, `.SchDoc`, `.PcbDoc`)
- `/Gerbers`: Standard RS-274X Gerber files and NC Drill files for PCB fabrication
- `/BOM`: Bill of Materials (CSV/Excel format)

## Manufacturing

To manufacture this PCB:
1. Export the contents of the `/Gerbers` directory into a `.zip` archive.
2. Submit the archive to a preferred PCB fabrication service.
3. Reference the `/BOM` directory for component procurement.

## References

The hardware design methodology and architecture are based on the instructional material provided by Phil's Lab ("STM32 PCB Design - Complete Walkthrough").

- [Reference Video](https://www.youtube.com/watch?v=PMEpQZ90f34&t=5077s)
- [Altium Designer Documentation](https://www.altium.com/documentation/)
