# Traffic Sign Detection and Classification

This project implements a **computer vision pipeline for detecting and classifying traffic signs** using OpenCV and machine learning techniques.

The system performs **color-based segmentation in HSV color space** to detect candidate traffic sign regions and then applies a trained classifier to recognize the specific sign category.

The model achieves approximately **91% accuracy on the GTSRB traffic sign dataset**.

---

## Project Overview

The pipeline consists of the following steps:

1. Image preprocessing and resizing
2. Conversion from BGR to HSV color space
3. Color-based segmentation to detect red and blue traffic signs
4. Morphological operations to refine detection
5. Bounding box extraction of candidate signs
6. Machine learning classification of detected signs

---

## Results

- Classification Accuracy: **~91%**
- Dataset: **German Traffic Sign Recognition Benchmark (GTSRB)**

The system successfully detects and classifies multiple traffic signs in real-world scenes.

---

## Technologies Used

- Python
- OpenCV
- NumPy
- Scikit-learn
- Matplotlib
- Computer Vision
- Machine Learning

---

## Repository Structure
traffic-sign-detection-classification
│
├── traffic-sign-detection-classification.ipynb
├── README.md
└── requirements.tx

---

## Future Improvements

Possible improvements for this project include:

- Deep learning-based traffic sign detection (CNN / YOLO)
- Real-time detection using video streams
- Model deployment using FastAPI or Streamlit
- Integration with autonomous driving systems

---

## Author

Abdelrahman Karam  
AI Engineer | Machine Learning | NLP | Computer Vision
