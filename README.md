# Road Lane Detection using VGG16-U-Net

## Overview

This project implements a deep learning based road lane detection system using a VGG16-U-Net architecture for semantic segmentation of lane markings. The model is trained on the TuSimple Lane Detection Dataset and predicts lane masks from road images.

## Features

- Semantic segmentation of road lanes
- VGG16 encoder with U-Net decoder architecture
- Transfer learning using pretrained VGG16 weights
- TensorFlow data pipeline with batching and prefetching
- Dice Loss based training
- Evaluation using Dice Coefficient, Precision, Recall, and Accuracy

## Dataset

**Dataset:** TuSimple Lane Detection Dataset

- Total Images: 3,263
- Task: Lane segmentation
- Annotation Type: Coordinate-based lane annotations converted into binary masks

## Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Pandas

## Model Architecture

- Pretrained VGG16 Encoder
- U-Net Decoder with Skip Connections
- Binary Segmentation Output

## Training

- Image preprocessing and mask generation
- Data augmentation and batching
- Training for 10 epochs
- Dice Loss optimization

## Results

- Dice Coefficient: 76.7%
- Accurate lane mask predictions on test images

## Future Improvements

- Real-time video lane detection
- Deployment using Flask/FastAPI
- Integration with autonomous driving pipelines

## Author

Tanya Gupta
