# Driver Drowsiness Detection ML Project

A Python-based machine learning project focused on driver drowsiness detection using mouth-state analysis and eye movement analysis. The project uses a Convolutional Neural Network (CNN) for mouth-state classification and Eye Aspect Ratio (EAR) for monitoring eye closure.

The project is being developed toward an integrated, real-time webcam-based drowsiness detection system.

## Project Objectives

- Detect mouth states associated with yawning.
- Train a CNN model for mouth-state classification.
- Analyze eye landmarks and calculate the Eye Aspect Ratio (EAR).
- Study eye closure, blink patterns, and closure duration.
- Combine eye and mouth analysis into a unified drowsiness detection workflow.

## Workflow

1. **Mouth Preprocessing:** Extract mouth regions from images and prepare them for CNN training.
2. **Mouth CNN Training:** Train and evaluate a CNN model for mouth-state classification.
3. **Eye Analysis:** Use MediaPipe landmarks to calculate EAR and analyze eye closure.
4. **Integrated Drowsiness System:** Develop a combined approach using eye and mouth signals.
5. **Real-Time Detection:** Work toward webcam-based drowsiness monitoring.

## Project Structure

```text
Drowsiness-Detection-ML-Project/
├── 02_mouth_preprocessing.ipynb
├── 03_mouth_cnn_training.ipynb
├── 04_eye_analysis.ipynb
├── 05_integrated_drowsiness_system.ipynb
├── README.md
├── run_notebook.cmd
├── pdf_extract.txt
├── .gitignore
└── Drowsiness-Detection-ML-Project-master/
