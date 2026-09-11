# Thalayattam Technologies

## AI-Powered Malayali Head Movement Recognition System

Thalayattam Technologies is an AI-powered computer vision system that detects and classifies predefined head-movement patterns and maps them to culturally inspired Malayalam responses.

The system uses real-time face landmark detection, head pose estimation, temporal feature extraction, and a machine learning classifier to recognize head movements.

---

## Features

- Real-time camera-based head movement detection
- Face landmark tracking using MediaPipe
- Head pose estimation using OpenCV
- Personalized neutral-position calibration
- Temporal movement feature extraction
- Random Forest gesture classification
- Confidence-based prediction
- WebSocket communication between frontend and backend
- Interactive web interface

---

## Supported Responses

The system currently recognizes five predefined movement classes:

| Class | Response |
|---|---|
| ATHE | അഥെ |
| SHERI | ശരി |
| VENDA | വേണ്ട |
| NOKKAM | നോക്കാം |
| ARIYILLA | അറിയില്ല |

These classes represent predefined movement patterns designed for this project and are not intended to define universal cultural meanings.

---

## System Architecture

```text
Camera
   ↓
Lovable Frontend
   ↓
WebSocket
   ↓
FastAPI Backend
   ↓
MediaPipe Face Landmarker
   ↓
Head Pose Estimation
   ↓
Yaw / Pitch / Roll
   ↓
Temporal Feature Extraction
   ↓
Random Forest Classifier
   ↓
Gesture + Confidence
   ↓
Frontend
