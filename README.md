# Car Gauge Detection

Car Gauge Detection is a computer vision project that uses deep learning to detect vehicle dashboard gauges from images or video frames. The goal is to automatically identify gauge regions for further analysis such as needle position or value estimation.

## Overview
This project implements a full training pipeline for gauge detection using a convolutional neural network. The notebook includes data loading, model training, validation, and performance evaluation using IoU as the primary metric.

## Features
- Gauge detection using deep learning
- End-to-end training and validation pipeline
- IoU-based model evaluation
- Result visualization during training
- Google Colab–ready Jupyter Notebook

## Technologies Used
- Python
- Deep Learning (CNN-based model)
- OpenCV
- NumPy
- Matplotlib
- PyTorch / TensorFlow
- Jupyter Notebook / Google Colab

## Training Details
- Epochs: 15
- Final Training Loss: 0.0418
- Validation IoU: 0.3047
- Best model checkpoint saved automatically

## Project Structure
├── Car_gauge_detection.ipynb
├── data/
├── models/
├── results/
└── README.md

## How to Run
1. Open the notebook in Google Colab or Jupyter.
2. Upload or connect the dataset.
3. Run all cells sequentially.
4. Monitor training logs and validation IoU.
5. Best model will be saved automatically.

## Results
The model successfully learns to localize car dashboard gauges, achieving reasonable IoU performance. Further improvements can be achieved with more data and augmentation.

## Future Improvements
- Improve IoU with larger and more diverse datasets
- Add gauge value regression
- Support real-time video inference
- Optimize model for edge deployment

## License
This project is for educational and research purposes.
