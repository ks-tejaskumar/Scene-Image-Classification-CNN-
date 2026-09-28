# Scene Image Classification using CNN

## Project Overview
This project implements a Convolutional Neural Network (CNN) model to classify images of different scenes. The model is trained on a dataset of labeled scene images and aims to accurately categorize images into their respective scene classes.

## Features
- **Data Pipeline:** Efficient image preprocessing and augmentation.
- **Model Architecture:** Custom CNN architecture optimized for spatial feature extraction.
- **Evaluation:** Training and validation scripts with comprehensive performance tracking.
- **Prediction:** Simple interface to classify new, unseen images.

## Dataset
- **Source:** [Insert Dataset Name or Source, e.g., Kaggle Dataset]
- **Details:** The model was trained on [Number of images] images across [Number of classes] categories.

## Installation

1. Clone the repository:
   ```bash
   git clone [Insert your repository link here]
   cd Scene-Image-Classification-CNN-

## Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

## Install dependencies:
pip install -r requirements.txt

## Usage:
1. Train the model:
python train.py

2. Evaluate performance:
python evaluate.py

3. Predict scene class for a new image:
python predict.py --image_path path/to/your/image.jpg

## Results:
Accuracy: 95.36% (training), 57.67% (validation, final epoch)
Key Findings: The CNN model classifies images into three categories: buildings, forest, and sea. The model shows signs of overfitting, with high training accuracy but volatile and generally low validation accuracy, indicating challenges in generalizing to unseen data.

## Contributing:
Contributions are welcome! Please fork this repository and create a pull request with your improvements.
