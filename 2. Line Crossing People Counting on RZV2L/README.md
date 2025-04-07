# Line Crossing People Counting Application

## Overview
The **Line Crossing People Counting** application provides vision-based functionality to detect and track people.  
It detects the head of a person and continuously tracks their position. A vertical reference line is drawn in the center of the screen, and the application counts people based on the direction they cross this line. It is optimized for real-time operation using input from a USB camera

### Key Features
- **Real-Time Detection and Tracking**: Continuously tracks individuals' head positions as they move within the camera’s view.
- **Directional Counting**: Counts people crossing a vertical reference line drawn at the center of the screen.  
   - If a person crosses from left to right, the **right count** increases.  
   - If a person crosses from right to left, the **left count** increases.  
- **Dynamic Bounding Boxes**: Automatically adjusts bounding boxes to match the size and position of the detected individual’s head for better visualization.

### Target Board and SW Versions
- Target Board: RZ/V2L Evaluation Board Kit
- AI SDK Version: AI Software Development Kit Version 1.00
- DRP-AI Version: DRP-AI Support Package Version 7.30

## Performance
- The application runs at approximately **25–28 FPS**.

## How to Run
To execute the application, use the following command:

```bash
./app_line_crossing_people_counting <model_path> <label_list_path>
