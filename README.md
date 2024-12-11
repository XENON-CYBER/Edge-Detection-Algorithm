# Edge Detection on FPGA

## Project Overview
This project implements an **edge detection algorithm** on an FPGA to detect a line in a **10x10 grayscale image matrix**. The system outputs the start and end coordinates of the line, displayed on a **7-segment display**.

## Features
- **Input**: A 10x10 grayscale matrix (values 0–255).
- **Algorithm**: Uses the **Prewitt Filter** for vertical and horizontal edge detection.
- **Output**: Displays line coordinates on a 7-segment display (e.g., `1,2` and `1,8`).

## System Design
- **Edge Detection Module**: Implements the Prewitt filter.
- **Display Module**: Outputs coordinates to the 7-segment display.

## Implementation
The project is written in **VHDL** for real-time processing on an FPGA.
