# AI-Based Online Proctoring System

## Overview
This project aims to develop an AI-based online proctoring system to monitor and ensure the integrity of online exams or assessments. The system leverages various computer vision and audio processing techniques to detect and prevent cheating behaviors during online exams.

## Features
1. **Face Detection (facial_detections.py)**
   - Detects faces in the video feed to ensure that the exam taker is present.
   
2. **Eye Tracker (eye_tracker.py)**
   - Utilizes eye detection to monitor the examinee's eye movements.
   
3. **Blink Detection (blink_detection.py)**
   - Detects blinks to prevent the presence of duplicate persons.
   
4. **Head Pose Estimation (head_pose_estimation.py)**
   - Estimates the head pose to track movements and deviations.
   
5. **Mouth Tracking (mouth_tracking.py)**
   - Tracks the mouth to detect speaking, helping to prevent cheating.
   
6. **Object Detection (object_detection.py)**
   - Detects electronic accessories or unauthorized items in the exam environment.
   
7. **Audio Detection (audio_detection.py)**
   - Monitors audio input to detect unauthorized sounds or communication during the exam.

## Requirements
- Python 3.x
- OpenCV
- TensorFlow
- dlib
- NumPy
- Other dependencies as specified in requirements.txt

## Contributing
Contributions to enhance or expand the functionality of this project are welcome! Please follow the standard guidelines for contributing and submit a pull request.
