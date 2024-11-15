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

## Performance
- The application runs at approximately **25–28 FPS**.

## How to Run
1. Use the following command to execute the application:
   ```bash
   ./app_line_crossing_people_counting <model_path> <label_list_path>