# Smart-Traffic-Signal-Optimization-System
## Overview

The Smart Traffic Signal Optimization System is an AI-powered traffic management solution that dynamically adjusts traffic signal timings based on real-time vehicle density.

Traditional traffic systems work on fixed time intervals, causing unnecessary waiting time, traffic congestion, fuel wastage, and delays for emergency vehicles. This project solves these issues by using computer vision techniques to detect vehicles, estimate traffic density, and optimize green signal duration for each lane.

The system can also prioritize emergency vehicles such as ambulances by overriding the normal signal sequence and providing a green corridor for faster movement. In addition, the project can be extended with traffic prediction, dashboard analytics, multi-junction synchronization, and IoT integration for smart city deployment.
## Features

- Real-time vehicle detection using computer vision
- Dynamic traffic signal timing adjustment
- Traffic density estimation for each lane
- Supports image, video, and live camera input
- Emergency vehicle detection and prioritization
- Adaptive green signal allocation
- Reduces waiting time, congestion, and fuel wastage
- Predictive traffic analysis for next signal cycle estimation
- Dashboard for traffic monitoring and analytics
- Multi-lane and multi-junction support
- Historical traffic data storage and analysis
- Can be integrated with IoT devices and CCTV cameras
- Suitable for smart city traffic management systems
## Tech Stack

- Python
- OpenCV
- NumPy
- Pandas
- Matplotlib
- YOLO / Haar Cascade Classifier
- TensorFlow / PyTorch
- SQLite / MongoDB (if database is used)
- Flask / Streamlit (for dashboard or web interface)
- Arduino / IoT Modules (if hardware integration is used)

## Working

1. Traffic images, videos, or live camera feeds are provided as input
2. Vehicles are detected using computer vision models
3. Vehicle count for each lane is calculated
4. Traffic density is estimated in real time
5. The system dynamically allocates green signal duration
6. Emergency vehicles are detected and prioritized
7. The signal controller overrides the normal sequence if an ambulance or emergency vehicle is detected
8. Traffic data is stored for future analysis and prediction
9. Dashboard displays traffic density, vehicle count, and signal timings
10. Multi-junction traffic synchronization can be implemented for larger road networks

## Screenshots

1. YOLO model object detection
   <img width="875" height="436" alt="image" src="https://github.com/user-attachments/assets/11e5ffa7-f4e7-4132-8b53-943cd70d95e6" />

2. Batch signal time
   <img width="684" height="336" alt="image" src="https://github.com/user-attachments/assets/79e32ec3-6046-45f7-a7a7-8b215badc9a4" />

3. Vehicle count over time
   <img width="1004" height="518" alt="image" src="https://github.com/user-attachments/assets/347c0d7a-1096-4103-96be-cc94f6db3d44" />

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
4. Predicted next signal and vehicles
   <img width="482" height="387" alt="image" src="https://github.com/user-attachments/assets/d000fe57-7775-46db-982a-8ee94273776b" />

5. Next signal change prediction
   <img width="996" height="524" alt="image" src="https://github.com/user-attachments/assets/24f06716-b729-4fa8-91e7-ff7d3ad3b8f9" />
