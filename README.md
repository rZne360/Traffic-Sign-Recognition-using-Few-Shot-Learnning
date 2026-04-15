# Traffic-Sign-Recognition
Siamese + YOLO Hybrid Model
Few-Shot Image Recognition using Detection + Similarity Learning
📌 Overview

This project implements a hybrid deep learning system combining:

YOLO (You Only Look Once) → for object detection
Siamese Neural Network → for similarity-based classification

The goal is to enable image recognition with very small datasets (few-shot learning), where traditional models fail due to lack of data and annotations.

🧠 Idea Behind the Project

Instead of training a heavy classifier on large datasets, this project:

Uses YOLO to detect objects in an image
Passes detected regions to a Siamese Network
Compares them with reference images
Predicts the class based on similarity score
