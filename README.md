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
```

## Current Status

- [x] Mouth preprocessing notebook
- [x] CNN training notebook
- [x] Eye analysis notebook
- [ ] Complete integration of eye and mouth signals
- [ ] Fully tested real-time webcam detection

*Update this checklist as each component is verified.*

## Installation and Setup

### Prerequisites

- Python 3
- Git
- Visual Studio Code or Jupyter Notebook

### Clone the Repository

```bash
git clone https://github.com/Sakshi0822/Drowsiness-Detection-ML-Project.git
cd Drowsiness-Detection-ML-Project
```

### Create a Virtual Environment

```bash
python -m venv .venv
```

### Activate the Virtual Environment on Windows

For Command Prompt:

```bat
.venv\Scripts\activate.bat
```

For PowerShell, if script execution is permitted:

```powershell
.\.venv\Scripts\Activate.ps1
```

### Install Dependencies

```bash
python -m pip install opencv-python mediapipe numpy pandas matplotlib torch torchvision jupyter
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook you want to run in the browser.

Recommended order:

1. `02_mouth_preprocessing.ipynb`
2. `03_mouth_cnn_training.ipynb`
3. `04_eye_analysis.ipynb`
4. `05_integrated_drowsiness_system.ipynb`

## Dataset Requirements

This project uses the YawDD (Yawning Detection Dataset) for yawning-related analysis.

Large datasets and generated files may not be included in this repository. Before running the notebooks:

1. Obtain the required dataset.
2. Place the files in the directory structure expected by the notebooks.
3. Check that the dataset paths in each notebook match your local folders.
4. Ensure any required pretrained models or MediaPipe model files are available.

## Technologies Used

- Python
- PyTorch
- OpenCV
- MediaPipe
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Future Improvements

- Integrate eye closure and mouth-state predictions into a unified system.
- Improve prediction reliability under different lighting conditions.
- Develop and test a real-time webcam detection pipeline.
- Document model evaluation results and limitations.

## Disclaimer

This project is intended for educational and research purposes. It should not be used as the sole basis for real-world driver safety decisions.
