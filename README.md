# 🛡️ Smart Sentry: AI Surveillance System

An advanced security solution that combines Computer Vision and Pattern Recognition to monitor environments and identify threats in real-time.

## 🚀 Capabilities
*   **Object Detection:** Real-time identification of specific objects using AI models.
*   **Face Recognition:** Identifies known individuals and flags unknown visitors.
*   **Smart Alerts:** Sends captured images and security notifications via Telegram.
*   **Event Logging:** Tracks all security incidents in an organized monitoring dashboard.

## 🛠️ Technology
*   **Core:** Python, OpenCV
*   **AI Models:** Face Recognition, Object Detection (e.g., YOLO or SSD)
*   **Communication:** Telegram Bot API

## 📂 How to Use
1. Run `sentry_main.py`.
2. The system will initialize the camera feed and begin detection.
3. If an anomaly or unauthorized face is detected, an alert is sent to the linked Telegram ID.
