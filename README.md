# 🌱 Plant Disease Prediction

## Overview

This project leverages machine learning to detect plant diseases from leaf images, empowering farmers and agriculturists with early diagnosis. By processing images with deep learning models built using TensorFlow and Keras, the application classifies leaves as healthy or diseased, identifying specific plant diseases with high accuracy.

**Table of Contents**

* Features 
* Project Structure
* Installation
* Usage
* Results
* Contributing
* Contact


# Features

* Accurate Disease Prediction: Identifies plant diseases with up to 92% accuracy using convolutional neural networks (CNNs).

* Visual Analysis: Highlights infected areas in leaf images for clear diagnosis.

* Multi-Species Support: Compatible with various plant species and disease types.

* User-Friendly Interface: Easy-to-use scripts for training models and predicting diseases from new images.

#Project Structure

* plant_disease_prediction/
 ├── data/                  
 ├── models/                
 ├── src/                   
 │   ├── data_preprocessing.py  
 │   ├── train_model.py         
 │   └── predict.py             
 ├── notebooks/             
 ├── requirements.txt       
 └── README.md              

# Installation

  * Prerequisites

    * Python: Version 3.8 or higher

    * Git: For cloning the repository

    * Optional: GPU for faster model training (CUDA-enabled for TensorFlow)


# Setup

* Clone the Repository:

  * git clone https://github.com/Hrishichaudhary/Plant_diseases-Prediction.git
  * cd plant_disease_prediction

# Install Dependencies:

 * pip install -r requirements.txt

   * This installs required packages like tensorflow, keras, opencv-python, matplotlib, 
     and seaborn.

# Usage

 ## Training the Model

   * Train the CNN model using your dataset:

     * python src/train_model.py --data_dir data/ --epochs 50

       * --data_dir: Path to the dataset folder.
       * --epochs: Number of training epochs (default: 50).

# Running Predictions

## Classify a new plant leaf image:

   * python src/predict.py --image_path path/to/image.jpg
     * --image_path: Path to the input image.

# Jupyter Notebooks

Explore the notebooks/ directory for detailed data analysis, model experimentation, and 
visualizations:
  * jupyter notebook notebooks/

# Results

The model achieves high accuracy in classifying plant diseases. Below are example predictions:

| Image  | Prediction         | Confidence   |
|--------|--------------------|--------------|
| Leaf 1 | **Tomato Blight**  | **92.3%**    |
|Leaf 2  | **Healthy**        | **98.6%**    |


# Contributing

## Contributions are welcome! To contribute:
* Fork the repository.
* Create a new branch (git checkout -b feature/your-feature).
* Commit your changes (git commit -m "Add your feature").
* Push to the branch (git push origin feature/your-feature).
* Open a Pull Request.

Please ensure your code follows the project’s style guidelines and includes tests where applicable.


# Contact

## For questions or feedback, reach out to:
* Hrishikesh Kr. Chaudhary: hrishikesh.kr.chaudhary16@gmail.com
* GitHub: Hrishichaudhary
* LinkedIn: hrishikesh-kumar-chaudhary
