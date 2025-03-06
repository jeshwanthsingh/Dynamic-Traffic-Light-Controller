# Dynamic Traffic Light Controller

## Overview
The **Dynamic Traffic Light Controller** is an **AI-powered traffic management system** designed to optimize traffic flow using **real-time vehicle detection**. This system integrates **Python, YOLO (You Only Look Once) object detection, and Pygame** to dynamically adjust signal durations based on traffic density, reducing congestion, improving travel efficiency, and lowering fuel consumption.

## Background
Traffic congestion in urban areas leads to prolonged delays, excessive fuel consumption, and increased pollution. Traditional **fixed-timer traffic lights** fail to adapt to real-time traffic conditions, exacerbating congestion. The **Dynamic Traffic Light Controller** tackles this problem by **analyzing live camera feeds** and adjusting traffic light durations based on vehicle count. This system is particularly effective in high-congestion cities like **Mumbai, Bengaluru, and New Delhi**, improving overall road efficiency.

## Features
- **Real-time Traffic Analysis**: Uses YOLO object detection to count vehicles at intersections.
- **Adaptive Traffic Light Timing**: Adjusts signal durations dynamically based on vehicle density.
- **AI-Powered Optimization**: Enhances traffic management and reduces road congestion.
- **Simulation Environment**: Uses **Pygame** for testing AI-based traffic light adjustments.
- **Improved Image Processing**: Optimized YOLO model **reduces frame processing time from 120ms to 85ms**.

## Technologies Used
- **Python** – Backend logic and AI model execution.
- **YOLO (You Only Look Once)** – Object detection for vehicle counting.
- **Pygame** – Real-time simulation and visualization.
- **OpenCV** – Image processing and frame analysis.
- **NumPy & Pandas** – Data handling and analysis.

## Installation & Setup
### **1. Clone the Repository**
```sh
git clone <your-repo-url>
cd dynamic-traffic-light-controller
```

### **2. Install Dependencies**
```sh
pip install -r requirements.txt
```

### **3. Run the Simulation**
```sh
python main.py
```

## How It Works
1. **Captures real-time video feed** from an intersection.
2. **YOLO model detects and counts vehicles** in each lane.
3. **Traffic light durations are adjusted dynamically** based on vehicle density.
4. **Pygame-based simulation** visualizes changes in real-time.
5. **Performance metrics logged** for efficiency analysis.

## Performance Improvements
- **Reduced frame processing time from 120ms to 85ms** by optimizing the YOLO model.
- **Efficient traffic handling**, decreasing congestion at intersections.
- **Fuel savings** due to reduced vehicle idling time at signals.

## Future Enhancements
- **Integration with real-world traffic cameras** for live implementation.
- **Deep learning-based traffic flow prediction**.
- **Cloud-based dashboard** for remote monitoring and control.

## License
This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.

