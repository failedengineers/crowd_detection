

This is a simple backend project that predicts crowd risk from a video.

Upload a video → system detects people using YOLO → returns risk:
LOW / MEDIUM / HIGH

tech Used
- Django
- OpenCV
- YOLOv8 (Ultralytics)

How it works
- Takes video as input
- Counts people in frames
- Calculates crowd density
- Gives risk level

API
POST `/api/analyze-video/`

Body:
- video (file)



}

https://drive.google.com/file/d/1uZ7AfhiGChmqfE5xf5U_eQH8d7602rFE/view?usp=drivesdk
https://github.com/user-attachments/assets/29cdc3f5-73ed-4cea-be95-6c66d3ca0fd5

<img width="1747" height="980" alt="Screenshot 2026-03-29 174954" src="https://github.com/user-attachments/assets/59424f50-f5de-4d01-b6b7-967cc3383380" />
