# Driver Monitoring System Demo Application

# Nota DMS Demo

## Overview
The **Nota DMS** demo runs on Renesas RZ/V2L and showcases real-time detection of driver drowsiness and distraction. The Nota DMS solution has been partially ported and optimized for the RZ/V2L platform. It recognizes drowsy or distracted behavior and presents the monitoring results on an intuitive dashboard.

## Key Features
- **Distraction Detection**  
  Detects forward-attention loss by estimating the driver’s head pose and flagging cases where the gaze direction deviates more than ±45 degrees from straight ahead.

- **Drowsiness Detection**  
  Tracks eye landmarks to measure eye-closure duration, identifying prolonged closures that indicate drowsiness.

## Performance
- The application runs at approximately 10 FPS.

## How to Run

### 1. Download the SD-card image
Download from the following link:  
[Download Link](https://drive.google.com/file/d/1450NCNEJpAUqxiMO50N77mGGszne-LaV/view?usp=sharing)

### 2. Write the image to an SD card
Restore the downloaded image onto an SD card.

### 3. Booting
- Plug the prepared SD card into the RZ/V2L evaluation board (EVB).
- Attach a USB camera. If you also need a keyboard and mouse, connect them through a USB hub.
- Power on the board (hold the power button for about two seconds).

### 4. Run the demo
- Open a terminal.
- Move to the directory:
  ```bash
  cd /home/root
  export LD_LIBRARY_PATH=/home/root/
  ./rzv2l_application
  
