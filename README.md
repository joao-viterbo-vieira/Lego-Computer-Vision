# Lego Kit Assembly - Computer Vision Project

A computer vision system for camera calibration and Lego brick analysis, including fault detection and kit assembly verification.

## Overview

This project implements a complete computer vision pipeline for analyzing Lego bricks and verifying kit assemblies. The system includes camera calibration using chessboard patterns and various image processing techniques for brick detection, fault identification, and kit verification.

![Example image](./data/Kit/ImageA_kit.png)

## Project Structure

```
CV_Assign1/
├── LegoBrick_CV.ipynb      # Main Jupyter notebook with all exercises
├── requirements.txt         # Python dependencies
├── Assign1_CV.pdf          # Assignment specification
└── data/                    # Image datasets
    ├── Calibration/         # Chessboard calibration images
    ├── Isolated/            # Individual brick images (colored)
    ├── Fault/               # Images for fault detection
    └── Kit/                 # Kit assembly images
```

## Exercises

### Exercise 1: Camera Calibration
Implementation of camera calibration using chessboard patterns to obtain intrinsic camera parameters and distortion coefficients.

### Exercise 2-4: Lego Brick Analysis
- Brick detection and color classification
- Fault detection in brick assemblies
- Kit verification and validation

## Requirements

- Python 3.10+
- OpenCV 4.8.0+
- NumPy 1.24.0+
- Matplotlib 3.7.0+
- Pandas 2.0.0+
- Jupyter Notebook

## Installation

1. Clone or download this repository

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

### Running the Main Notebook

```bash
jupyter notebook LegoBrick_CV.ipynb
```

The notebook contains all exercises with detailed implementations and visualizations.

## Data

The project includes several datasets:

- **Calibration**: Chessboard pattern images for camera calibration
- **Isolated**: Individual Lego brick images with different colors (blue, green, red, yellow)
- **Fault**: Images containing brick assemblies with potential faults
- **Kit**: Complete kit assembly images for verification

## Key Features

- Automatic chessboard pattern detection with multiple size configurations
- Camera intrinsic parameter estimation
- Lens distortion correction
- Color-based brick detection and classification
- Fault detection in assemblies
- Kit completion verification

## Dependencies

All dependencies are listed in `requirements.txt`:

- opencv-python & opencv-contrib-python for computer vision operations
- numpy for numerical computing
- matplotlib for visualization
- pandas for data analysis
- jupyter for interactive development

## License

This is an academic project for educational purposes.


## Authors

- Francisco Pinto
- João Soares
- João Vieira

## Notes

- Ensure all image paths in the notebook match your local directory structure
- The calibration process automatically tests multiple chessboard configurations
- Results include detailed visualizations for each processing step
