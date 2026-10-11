Wireless Warehouse Barcode Scanner
Electronic System Engineering | Politecnico di Torino
An academic electronic hardware design project focused on developing a portable wireless barcode scanner for warehouse inventory management.

The project covers electronic component selection, power consumption analysis, battery sizing, schematic design, PCB layout, and manufacturing cost estimation.

PCB Design
Wireless Barcode Scanner PCB Layout

Two-layer PCB layout developed using Cadence OrCAD and Allegro.

1. Project Overview
The objective was to design a compact, battery-powered barcode scanning system capable of acquiring barcode images and supporting wireless communication.

The proposed architecture integrates:

A CMOS image sensor for barcode image acquisition.
A low-power ARM Cortex-M3 microcontroller with Bluetooth Low Energy capability.
A rechargeable LiPo battery with USB charging.
Voltage regulation and power management circuitry.
A 2.4 GHz printed PCB antenna.
Status LEDs, a power switch, and a JTAG interface.
2. Hardware Components
Component	Selected Device	Function
Microcontroller	TI CC2640	Processing and BLE connectivity
Image Sensor	onsemi AR0130	Barcode image acquisition
Battery	LP503035, 3.7 V, 500 mAh	Portable power supply
Battery Charger	MCP73833	LiPo battery charging
Voltage Regulator	LTC3400	Power regulation
Antenna	2.4 GHz PCB antenna	Wireless communication
USB Connector	USB Type-C	Battery charging
Debug Interface	JTAG	Programming and debugging
3. Engineering Design Activities
Component Selection
Electronic components were evaluated based on electrical specifications, functionality, availability, and compatibility with the proposed architecture.

The image sensor selection included evaluating alternative devices and their suitability for PCB integration.

Power Consumption and Battery Analysis
Power consumption was estimated for the main system components, including the microcontroller, image sensor, and LEDs.

The analysis considered active and standby operating modes to estimate battery requirements and operating duration.

Schematic Design
Electronic schematics were developed using Cadence OrCAD Capture CIS.

The design was organized into:

Power management and battery charging
Microcontroller and supporting circuitry
CMOS image sensor interface
Wireless antenna and peripheral connections
PCB Design and Layout
A custom two-layer PCB was developed using Cadence Allegro.

Design considerations included:

Component placement and routing constraints.
Microcontroller and antenna positioning.
Image sensor placement near the PCB edge.
Signal routing on the top layer.
Ground plane implementation on the bottom layer.
Footprint and padstack preparation.
Bill of Materials and Cost Estimation
A Bill of Materials (BOM) was prepared, including component selection and cost analysis.

Manufacturing cost estimates were considered for production quantities of 1, 50, 100, and 1000 PCBs.

4. Engineering Tools
Cadence OrCAD Capture CIS — schematic design
Cadence Allegro — PCB layout and routing
Cadence Padstack Editor — padstack preparation
Microsoft Excel — BOM and cost estimation
Electronic component datasheets — component selection and design verification
5. Project Documentation
The complete academic project report includes system architecture, component specifications, power consumption calculations, schematics, PCB layout, and BOM analysis.

View Full Project Report (PDF)

View PCB Layout

6. Project Contributors
Academic Team Project

Milad Rahmani Nezhad
Alireza Khoshkbari
University: Politecnico di Torino, Italy

Course: Electronic System Engineering

Academic Period: January – March 2024

7. Project Scope
This repository documents the electronic hardware design and PCB development stages of an academic engineering project.

The available documentation includes design calculations, schematics, PCB layout, and component cost estimates.

Physical PCB manufacturing, firmware implementation, and functional validation are not demonstrated in the available project documentation.
