## Title: Dance Tracking and Detection using Mediapipe

### A. Project Overview:
This project utilizes the Mediapipe library for real-time dance tracking and detection in videos. The primary goal is to leverage pose estimation to identify and track key body landmarks, providing insights into dance movements within the given video.

### B. Motivation
Understanding dance movements has various applications, from choreography analysis to fitness tracking. This project aims to showcase the capabilities of the Mediapipe library in tracking and visualizing dance poses in real-time.

### C. Project Structure:
The project is organized into the following components:

#### 1] Pose Estimation:
* Utilizes the Mediapipe library to estimate and track key body landmarks in each frame of the video.
* Landmarks are used to create a pose skeleton, visualizing the dancer's movements.

#### 2] Video Processing:
* Reads a video file frame by frame using OpenCV.
* Applies pose estimation on each frame and renders the detected landmarks.

#### 3] Visualization:
* Draws pose landmarks on each frame using Mediapipe's drawing utilities.
* Customizable drawing specifications, such as color, thickness, and circle radius, enhance the visualization.

#### 4] Output Video:
* Creates an output video with annotated pose landmarks, providing a visual representation of the dance movements.
* Output video is saved for further analysis or sharing.


## Results:
* The resulting video showcases the dance movements with annotated pose landmarks in real-time. The accuracy and efficiency of the pose estimation contribute to a visually informative representation of the dancer's poses.


- **Final Ouput:**

![App Screenshot](https://github.com/abhishekdeshmukh001/Dance-Tracking-and-Detection-using-Mediapipe/blob/main/Pose%20Tracking.png?raw=true)


## 🔗 Link
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhishek-sachin-deshmukh/)



## Authors

- [@abhishekdeshmukh001](https://github.com/abhishekdeshmukh001)
