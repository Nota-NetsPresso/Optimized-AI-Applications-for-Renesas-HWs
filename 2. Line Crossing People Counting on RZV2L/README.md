# Line Crossing People Counting Application

## Overview
The **Line Crossing People Counting** application provides vision-based functionality to detect and track people.  
It detects the head of a person and continuously tracks their position. A vertical reference line is drawn in the center of the screen, and the application counts people based on the direction they cross this line.  
- Crossing to the **right** increases the right count.  
- Crossing to the **left** increases the left count.

## Performance
- The application runs at approximately **25–28 FPS**.

## How to Run
1. Use the following command to execute the application:
   ```bash
   ./app_line_crossing_people_counting <model_path> <label_list_path>
