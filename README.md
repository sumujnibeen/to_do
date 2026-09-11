<div align="center">

# MysticMotion

### Gesture-Controlled Augmented Reality Effects System

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Hand%20Tracking-FF6F00?style=for-the-badge)
![NumPy](https://img.shields.io/badge/NumPy-2.x-013243?style=for-the-badge&logo=numpy&logoColor=white)
![AR](https://img.shields.io/badge/Augmented%20Reality-Interactive-8A2BE2?style=for-the-badge)

<br>

A real-time computer vision project that turns hand gestures into superhero-inspired AR effects.

</div>

---

## About

MysticMotion is a real-time gesture-controlled augmented reality project built with Python, OpenCV, and MediaPipe.

The idea was simple:

**Can I use ordinary hand gestures to trigger visual effects directly inside a live webcam feed?**

Instead of relying on buttons or keyboard controls, MysticMotion uses hand tracking and custom gesture recognition to understand predefined poses and trigger animated effects in real time.

The project currently includes two gesture-based effects:

- Doctor Strange-inspired portal
- Spider-Man-inspired web shooting

---

## What I Built

- Real-time hand tracking using MediaPipe
- Custom hand gesture recognition
- Motion detection for gesture-based activation
- Doctor Strange-inspired portal effect
- Spider-Man-inspired web shooting effect
- Transparent animation playback
- Real-time alpha blending
- Webcam-based AR rendering
- Custom asset processing pipeline

---

## How It Works

The system processes the webcam feed continuously:

```text
Webcam
   ↓
MediaPipe Hand Tracking
   ↓
Hand Landmark Detection
   ↓
Gesture Recognition
   ↓
Motion Analysis
   ↓
Effect Trigger
   ↓
Transparent Animation
   ↓
Real-Time AR Overlay
