# Parkinson Face & Hand Tracker

A real-time 3D landmark tracking dashboard built with HTML, CSS, and JavaScript using the MediaPipe Holistic framework. Designed to analyze and study Parkinson's disease micro-movements, this application maps high-fidelity facial tracking points and dual independent hand tracking streams using a standard webcam with zero extra hardware required.

## Live Demo
Try the dashboard directly in your browser:
**https://christopherjun979-source.github.io/ParkinsonHandTrack/**

## Key Features

* **Mirrored Real-Time Tracking Canvas:** Features a seamless, non-overlapping camera display automatically mirrored (`scaleX(-1)`) to offer an intuitive, natural reflection behavior for patients during tracking sessions.
* **Granular Visibility Control Panel:** An integrated configuration dashboard allowing users to toggle individual anatomical segments on or off. Disabling a segment immediately halts canvas rendering and hides its respective text data box to maximize vertical screen real estate.
* **Dual Independent Hand Pipelines (Stream Panels A & B):** Tracks up to two hands simultaneously, processing spatial X, Y, and Z coordinates across 21 independent joint locations per hand. The tracker features independent visibility controls for each stream and color-coded anatomical structures:
  * **Wrist Base:** Highlighted in red
  * **Thumb:** Highlighted in orange
  * **Index Finger:** Highlighted in yellow
  * **Middle Finger:** Highlighted in green
  * **Ring Finger:** Highlighted in blue
  * **Pinky Finger:** Highlighted in purple
* **Targeted Facial Telemetry:** Monitors vital spatial landmarks for facial tremor and motor asymmetry observation:
  * **Left Eye (Top/Bottom points):** Highlighted in cyan
  * **Right Eye (Top/Bottom points):** Highlighted in purple
  * **Lips Boundary (Top/Bottom/Left/Right points):** Highlighted in red
* **Performance Diagnostic Overlay:** Features an integrated, live frames-per-second (FPS) counter to monitor processing efficiency and camera stream stability in real time.

## How to Use

1. Open the live demo link in any modern desktop web browser.
2. Grant camera access permissions when prompted by your browser.
3. Position your face and hands comfortably within the camera frame.
4. Use the top configuration rows to selectively hide or show telemetry data fields based on your analysis needs.

---
*Note: This project is an active work-in-progress designed for research and educational visualization, and it is continuously updated.*
