# NUCLEO SPI & Input Device Suite

This repository contains STM32 NUCLEO projects focused on output visualization via an LED matrix and interaction with digital input devices like keyboards and rotary encoders. These exercises integrate SPI communication, GPIO handling, and real-time user input response.

## Project Contents

### 1. LED Matrix via SPI (Homework 09)
- **Function**: Controls a LED matrix using SPI communication.
- **Features**:
  - Sends data to LED matrix row by row.
  - Supports dynamic patterns or static messages.
- **Learning Outcome**:
  - SPI peripheral configuration and usage.
  - LED matrix addressing and timing control.

### 2. Digital Keyboard Interface (Homework 10)
- **Function**: Reads input from a matrix keypad and processes key presses.
- **Features**:
  - Scans rows/columns for active key.
  - Displays or acts on pressed keys.
- **Learning Outcome**:
  - GPIO input handling.
  - Matrix keypad scanning logic.

### 3. Rotary Encoder Reader (Homework 10)
- **Function**: Reads and interprets input from a rotary encoder.
- **Features**:
  - Detects direction of rotation.
  - Optionally updates counter or UI element.
- **Learning Outcome**:
  - Quadrature signal decoding.
  - Interrupt-based input reading.

---

## Technologies Used

- **Hardware**: STM32 NUCLEO board, LED matrix (SPI), keypad, rotary encoder
- **Software**: STM32CubeIDE, STM32 HAL Drivers
- **Concepts**:
  - SPI communication
  - Matrix scanning (keyboard)
  - Rotary encoder decoding
  - GPIO interrupts and input logic

---

## How to Run

1. Open any project folder inside the repo in **STM32CubeIDE**.
2. Connect the NUCLEO board and corresponding hardware (matrix, keypad, encoder).
3. Build and flash the firmware.
4. Interact with:
   - LED matrix patterns (via SPI)
   - Keyboard key detection
   - Rotary encoder rotation
