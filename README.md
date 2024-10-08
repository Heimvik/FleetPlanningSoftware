# Distributed LED System
## Overview
The Distributed LED System is a networked lighting project using ESP32 microcontrollers and individually addressable RGB LED strips. The system consists of a master node that processes signals and multiple slave nodes, each controlling a 1-meter LED strip. The system supports various lighting modes, including synchronization with music and spatial sound effects. When finished with the circuits to the second revision, the firmware for it will be developed in embedded C. Future progress will appear here shortly.

## Features

- **Centralized Control**: Master node coordinates LED patterns across all slave nodes.
- **Dynamic Lighting Modes**:
  - Static Colors
  - Dynamic Patterns
  - Music Synchronization
  - Spatial Sound Effects
- **Real-time Communication**: Efficiently communicates between master and slave nodes using MQTT/WebSockets.
- **User Interface**: Web-based or mobile app interface for control and configuration.


Status as of 09.10: Awaiting programmer for ESP32-WROOM32E, continuing prototyping with rpi.
