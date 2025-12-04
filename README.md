STM32 CAN Communication Project

This project demonstrates CAN (Controller Area Network) communication between two STM32 microcontroller boards. It allows data exchange between nodes over the CAN bus, showcasing basic transmit and receive functionality.

⚡ Features

✅ Transmit and receive messages over CAN bus

✅ Configurable baud rate and message ID

✅ Real-time debugging via serial monitor

✅ Demonstrates master-slave or peer-to-peer communication

🔧 Hardware Required

2 × STM32 boards (e.g., STM32F103, STM32F4)

CAN transceivers (e.g., MCP2551)

Connecting wires and breadboard

Optional: LEDs or buzzer for message indication

🛠 Software & Libraries

STM32CubeIDE

HAL library for CAN peripheral

Optional: STM32CubeMX for CAN initialization

Serial terminal for debugging (e.g., PuTTY, Tera Term)

⚡ Setup Instructions

Connect the CAN_H and CAN_L lines between two STM32 boards via CAN transceivers.

Configure the CAN peripheral in STM32CubeIDE / CubeMX:

Set the correct baud rate (e.g., 500 kbps)

Enable interrupts for message receive

Load the transmitter code on one STM32 board and receiver code on the other.

Open serial monitors on both boards to view transmitted and received messages.

📌 Notes

Make sure the CAN bus is terminated with 120 Ω resistors at each end.

Supports both standard (11-bit) and extended (29-bit) identifiers.

Can be extended for multi-node communication networks.
