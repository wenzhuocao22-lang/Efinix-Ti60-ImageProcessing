# Efinix-Ti60-ImageProcessing

A real-time image edge detection system based on Efinix Ti60 FPGA.

This project is designed for the 2026 FPGA Innovation Design Competition.
The system implements real-time camera acquisition, grayscale conversion,
Sobel edge detection and HDMI display using FPGA hardware pipeline architecture.

## Hardware Platform

- FPGA:
  - Efinix Titanium Ti60F225

- Development Board:
  - VF-Ti60F225

- Camera:
  - TBD

- Display:
  - HDMI Monitor


## System Architecture

Camera
↓
Image Acquisition
↓
RGB to Gray
↓
Line Buffer
↓
3×3 Sobel Edge Detection
↓
Threshold Processing
↓
HDMI Output


## Functions

- [ ] FPGA development environment setup
- [ ] HDMI output test
- [ ] Camera acquisition
- [ ] Grayscale conversion
- [ ] Sobel edge detection
- [ ] Real-time display


## Project Structure
