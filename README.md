Build a complete deepfake and AI-generated video detection application.
The app should include:

Purpose: Detect whether an uploaded video is real, AI-generated, or manipulated (deepfake).

Features:

Video upload (MP4, MOV, WebM).

Frame extraction and preprocessing.

Deepfake detection using a combination of:
• CNN-based facial artifact detection
• Audio–visual inconsistency analysis
• Lip-sync mismatch detection
• Eye-blink and micro-expression anomaly detection
• Temporal frame inconsistency analysis

Provide a confidence score (0–100%) with an explanation of key signals.

Highlight suspicious frames visually.

Include an API endpoint for programmatic detection.

Provide a clean UI dashboard.

Technical stack (example):

Backend: Python + FastAPI

Deep learning: PyTorch or TensorFlow

Models to suggest: XceptionNet, EfficientNet-based detectors, LipForensics, Wav2Lip anomaly models

Frontend: React or Next.js

Database: PostgreSQL or MongoDB for logs

Output requirements:

Generate the full system architecture

Provide code templates for each module

Write the API specification

Include pseudo-code for the detection model pipeline

Write data preprocessing steps and training procedure

Suggest benchmark datasets (e.g., FaceForensics++, Celeb-DF, DFDC)

Provide deployment guide (Docker + cloud deployment)

Constraints:

The app must NOT generate deepfakes, only detect and classify them.

Prioritize accuracy, explainability, and security.

Generate all code, architecture diagrams (text-based), and instructions.
