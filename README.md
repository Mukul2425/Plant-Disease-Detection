# Plant Disease Detection

This repository contains an implementation of a machine learning-based system for detecting plant diseases from images. The project utilizes a trained deep learning model to classify and identify diseases affecting plants.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Project Files](#project-files)
- [How to Use](#how-to-use)
- [Acknowledgments](#acknowledgments)

## Introduction

Crop diseases affect plant growth and yield, leading to significant losses. Early detection and diagnosis are crucial to mitigate the effects. This project leverages deep learning to automate the process of plant disease detection from images.

## Features

- Deep learning model trained to classify various plant diseases.
- Easy to use with provided Python scripts and Jupyter Notebooks.
- Contains mappings for disease classes to help interpret model results.

## Requirements

To run this project on your local machine, ensure you have the following:

1. Python installed (>= 3.6)
2. Required dependencies as mentioned in the `requirements.txt` (if available):
   - TensorFlow/Keras for deep learning.
   - Libraries for preprocessing and handling data such as `numpy` and `pandas`.

## Project Files

The repository includes the following important files:

- **[Plant_Disease.ipynb](./Plant_Disease.ipynb)** - Jupyter Notebook for model training or testing.
- **[class_mapping.json](./class_mapping.json)** - A JSON file mapping class indices to plant disease names.
- **[plant_disease.py](./plant_disease.py)** - Python script for inference and visualization.
- **[plant_disease_model.h5](./plant_disease_model.h5)** - Pre-trained deep learning model file.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Mukul2425/Plant-Disease-Detection.git
   cd Plant-Disease-Detection
   ```

3. **Run the Notebook**:
   Open and run the `Plant_Disease.ipynb` notebook for step-by-step guidance on using the model.

4. **Inference Script**:
   Use the `plant_disease.py` script for classifying new plant images:
   ```bash
   python plant_disease.py --image_path <path_to_image>
   ```

## Acknowledgments

This project was inspired by the need for modern tools to aid in agricultural health and productivity. Special thanks to open datasets of plant diseases and deep learning communities.

---

For issues or contributions, please file an issue on this repository. Thank you for your interest!
