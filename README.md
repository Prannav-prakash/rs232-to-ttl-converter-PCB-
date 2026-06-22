# RS232-to-ttl-converter-PCB
RS232 to TTL interface PCB for connecting an Inertial Labs INS-DU to a Cube Orange Plus flight controller at 921600 bps.

# Overview

This project implements a dedicated RS232-to-TTL interface board for communication between an Inertial Labs INS-DU navigation system and a Cube Orange Plus flight controller.

The board performs RS232 level shifting using the MAX3232E transceiver while also providing a power passthrough interface from an external BEC to the INS-DU. The design supports high-speed serial communication at up to 921600 baud and was developed using KiCad.

# Features
RS232 to TTL voltage level conversion using MAX3232
Compatible with Cube Orange Plus flight controller
Compatible with Inertial Labs INS-DU navigation system
Supports serial communication up to 921600 baud
External BEC power passthrough to INS-DU

# System Architecture

Cube Orange Plus UART (TTL)

↓

MAX3232E Level Shifter

↓

INS-DU RS232 Interface

Power for the INS-DU is supplied independently through an external BEC and routed through the PCB.

# Hardware Components
Integrated Circuits
MAX3232E RS232 Transceiver
Passive Components
Charge pump capacitors required by MAX3232
Power supply decoupling capacitor
Connectors
Cube Orange Plus Interface Connector
INS-DU Interface Connector
BEC Power Input Connector

# Repository Contents
KiCad Schematic Files

KiCad PCB Layout Files

Custom Symbols

Custom Footprints

3D Models

Documentation

Images
# PCB layout
<img width="765" height="562" alt="image" src="https://github.com/user-attachments/assets/6f54a6fe-3c01-4a70-93bb-0d63dd128526" />


# schematic 
<img width="1466" height="650" alt="image" src="https://github.com/user-attachments/assets/4510f70e-277f-4893-a04c-ec43675e7378" />

# 3D view 
<img width="848" height="595" alt="image" src="https://github.com/user-attachments/assets/02fafa49-4017-4cb6-bfad-8ec6779d4b22" />



