# Quadcopter Drone Build --> APM2.8 Flight Controller

This is my hands-on robotics group project in first year involving the assembly and configuration of a custom quadcopter using an F450 frame and an APM2.8 flight controller. The build covered power distribution, soldering, ESC and motor integration, flight controller calibration, and initial flight tuning using Mission Planner.

## Overview

The quadcopter was assembled from individual components rather than a pre-wired kit. The project involved soldering the power distribution system, mounting and wiring the propulsion components, configuring the APM2.8, and tuning the system for stable flight.

## Hardware

| Component | Specification |
|---|---|
| Flight Controller | APM2.8 |
| Motors | 4 × Brushless Motors |
| ESCs | 4 × Matched ESCs |
| Propellers | 1045 (10 × 4.5") |
| Battery | 2S LiPo |
| Frame | F450 |
| Ground Station | Mission Planner |

## Build Process

### 1. Power Distribution & Wiring

Soldered the power distribution circuit and connected all four ESC signal lines to the APM2.8. Verified continuity and polarity before powering the system.

### 2. Frame Assembly

Mounted the motors, ESCs, and APM2.8 flight controller onto the F450 frame. Routed power and signal wiring to maintain a clean layout and minimize potential interference.

### 3. Flight Controller Configuration

Used Mission Planner to:

- Calibrate the accelerometer
- Calibrate the compass
- Configure ESC throttle ranges
- Set initial PID parameters
- Verify sensor and flight controller operation

### 4. Radio Setup & Flight Tuning

Bound the transmitter to the receiver and verified control inputs and motor responses. Conducted initial flight tests and adjusted stabilization parameters for improved flight performance.

## Issues Encountered & Fixes

### Intermittent ESC Dropout

**Problem:** One ESC intermittently lost its signal.

**Cause:** A cold solder joint on the ESC signal connection.

**Solution:** Reflowed the solder joint and verified the connection using continuity testing under load.

### Incorrect Motor Rotation

**Problem:** One motor was rotating in the wrong direction.

**Cause:** Incorrect motor wiring configuration.

**Solution:** Identified the issue during a propeller-off bench test and corrected the motor wiring before flight testing.

## What I Learned

- Systematic hardware debugging by tracing faults to individual electrical connections instead of immediately assuming a software issue.
- How motor direction, throttle calibration, and PID parameters work together to achieve stable quadcopter flight.
- Practical power distribution and wiring considerations for LiPo-powered systems.
- How PID-based flight stabilization is exposed through configurable parameters in ground station software such as Mission Planner.
- The importance of performing structured pre-flight checks before testing a custom-built aircraft.

## My Contributions

This was a team project, but my primary hands-on contributions included:

- Power distribution soldering
- ESC and motor wiring
- APM2.8 flight controller setup
- Accelerometer and compass calibration
- ESC calibration
- Initial PID configuration
- Hardware debugging
- Motor direction verification
- Initial flight testing and tuning

## Project Outcome

Successfully assembled and configured a functional F450 quadcopter using an APM2.8 flight controller. The project provided practical experience in embedded hardware integration, power electronics, brushless motor control, flight stabilization, and real-world hardware debugging.

## Project Gallery

<div align="center">

<table>
<tr>
<td align="center" width="33%">

<img src="https://github.com/user-attachments/assets/d6bda3d3-e574-4cf3-bc07-e1d7574d9500" width="100%">

<b>Quadcopter Assembly</b>

</td>
<td align="center" width="33%">

<img src="https://github.com/user-attachments/assets/a4c2333e-675b-46d8-8026-256758a051b2" width="100%">

<b>Hardware & Wiring</b>

</td>
<td align="center" width="33%">

<img src="https://github.com/user-attachments/assets/15dd0922-aa55-4467-b75e-210faf64ccaa" width="100%">

<b>Completed Build</b>

</td>
</tr>
</table>

</div>


## Key Contributors

| Aditya Anil | Devesh Sharma | Allu Srujan | Aathi Sessa Sayee P | Gaurav S Gupta | Anurag Das |
|---|---|---|---|---|---|
| Contributor | Contributor | Contributor | Contributor | Contributor | Contributor |


