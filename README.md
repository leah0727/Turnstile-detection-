# Turnstile detection mobile application for the Visually Impaired
2024 Winter Ambient AI Bootcamp & Competition Hosted by Seoul National University Graduate School of Data Science

## Overview
- Developed a subway turnstile detection model for the visually impaired using the YOLOv8m model, with an architecture focused on user convenience and accessibility.
- Collected a dataset of 3,987 images from 16 stations, covering 9 different types of turnstiles.
- Utilized Roboflow for data labeling, labelling features into ‘entrance’, ‘stop’, and ‘go’.
- Selected the YOLOv8m model for its high accuracy, real-time detection & feedback capabilities, and optimization for mobile applications.
- Refined labeling classes to ‘entrance’ and ‘go-entrance’ for clearer feature differentiation, improving model performance.
- Addressed detection issues on side views by adding datasets of special cases and improved performance by applying data augmentation techniques.
- Developed user scenarios and adjusted parameters such as epochs.
- Ultimately, achieved significant improvements in Precision (0.95) and Recall (0.917), while successfully reducing inference time from 24ms to 11ms.
- Skills: Python, Roboflow, YOLOv8 (Ultralytics), pandas, OpenCV, gTTS (Google Text-to-Speech), Google Colab
