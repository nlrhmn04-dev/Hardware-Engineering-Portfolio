# Velocity-Based Training Device

Real-time barbell velocity measurement system using IMU sensor fusion.

## Overview
Weight-lifting device using ESP32 and MPU6050 IMU to measure barbell velocity, validated through camera analysis.

## System Architecture

![System Architecture](VBT_System_Architecture.drawio.png)

## Specifications
- **Accuracy**: <8% error in velocity loss measurements
- **Sensor**: MPU6050 IMU (accelerometer + gyroscope)
- **Microcontroller**: ESP32
- **Analysis**: Python with FFT

## Key Features
- Real-time velocity calculation
- FFT analysis to characterize frequency content
- High-pass filter (0.2 Hz cutoff) to minimize drift
- Custom 3D-printed enclosure

## Technical Details
- Analyzed acceleration data using Fast Fourier Transform
- Determined optimal filter cutoff to preserve motion signals
- Camera validation for ground truth measurements

## Tools Used
- ESP32 microcontroller
- MPU6050 IMU
- Python (NumPy, Matplotlib, SciPy)
- SolidWorks for enclosure design
- 3D printing

---

**Project Date**: 2024  
**Status**: Completed
