# AUTOSAR DIO Driver - TM4C123

## Overview
This project implements an AUTOSAR-compliant Digital Input/Output (DIO) driver at the MCAL layer for the TM4C123GH6PM microcontroller.

## Features
- Channel read/write APIs
- Port read/write APIs
- Configurable post-build configuration
- AUTOSAR standard data types (Std_Types, Platform_Types)
- Development Error Tracer (DET) integration

## Architecture
The driver follows AUTOSAR layered architecture:
- MCAL Layer (DIO Driver)
- ECU Abstraction (via configuration)
- Application Layer (main.c for testing)

## Files Description
- Dio.c / Dio.h → Core driver implementation
- Dio_Cfg.h → Configuration definitions
- Dio_PBcfg.c → Post-build configuration
- Dio_Regs.h → Register mapping for TM4C123
- Det.c / Det.h → Error handling module
- main.c → Testing application

## Tools & Technologies
- Embedded C
- AUTOSAR Architecture (MCAL Layer)
- TM4C123GH6PM (Tiva C)
- Code Composer Studio

## Author
Hassan Yasser
