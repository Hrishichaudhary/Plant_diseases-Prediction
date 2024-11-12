__~~Plant Disease Prediction__~~🌱

__Overview__:
This project aims to detect plant diseases from images using machine learning models. The application processes images of plant leaves and classifies them as healthy or diseased, identifying specific plant diseases to aid farmers and agriculturists.



__Table of Contents__:
Features
Project Structure
Installation
Usage
Results
Contributing
License
Features
Predicts plant diseases with high accuracy.
Provides detailed visual analysis of infected areas.
Supports multiple plant species and diseases.


__Project Structure__:
plant_disease_prediction/
├── data/                 # Dataset and related files
├── models/               # Saved models and training scripts
├── src/                  # Source code for model and processing
│   ├── data_preprocessing.py
│   ├── train_model.py
│   └── predict.py
├── notebooks/            # Jupyter notebooks for exploration and experimentation
├── requirements.txt      # Dependencies
└── README.md             # Project documentation


~~ Installation ~~
__Prerequisites__:
1. Python 3.x
2. Git


~~ Setup ~~
__Clone the repository__:
git clone https://github.com/Hrishichaudhary/plant_disease_prediction.git
cd plant_disease_prediction

__Install dependencies__:
pip install -r requirements.txt


~~ Usage ~~
__Training the Model__:

Use train_model.py to train the model with your dataset:- python src/train_model.py --data_dir data/ --epochs 50

__Running Predictions__:

Use predict.py to classify a new image of a plant leaf:- python src/predict.py --image_path path/to/image.jpg

__Jupyter Notebooks__:- Explore notebooks/ for detailed exploration and visualization of the dataset and models.



__Results__

---Here’s an example of the predictions produced by the model:

Image   |   	Prediction	  |  Confidence
        |                 |
        |   Tomato Blight	|    92.3%
        |    Healthy      |  	98.6%

