#  Crop Disease Prediction (ML Model)

This project predicts crop diseases from leaf images using a trained deep learning model.  
It uses **MobileNetV2 (Transfer Learning)** and supports testing with any local image.

##  Features

-  Pre-trained MobileNetV2 model
-  Predict diseases from leaf images
-  Shows prediction confidence
-  Jupyter Notebook for testing

##  Project Structure

Crop-Disease-Prediction/
├── Crop_Disease_Model.ipynb # Jupyter Notebook for training & testing
├── plant_disease_model.h5 # Pre-trained model file
├── tobacco-mosaic-virus.jpg # Example test image
└── README.md # This file

yaml
Copy
Edit


##  Model Information

- **Base Model:** MobileNetV2 (ImageNet weights)
- **Input Size:** 128x128 pixels
- **Output:** 23 plant disease classes (from PlantVillage dataset)
- **Saved Model Path:**  
  `C:\Users\sagni\Downloads\Crop-Disease-Prediction\plant_disease_model.h5`

##  How to Run

###  Requirements
- Python 3.x
- TensorFlow
- Keras
- Pillow
- Matplotlib

###  Install Dependencies
```bash
pip install tensorflow keras pillow matplotlib
