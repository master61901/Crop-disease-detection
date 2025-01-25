#Crop Disease Prediction Project
Welcome to the Crop Disease Prediction project! This repository contains a machine learning model designed to predict plant diseases using leaf images. By leveraging advanced deep learning techniques, this project aims to assist farmers in timely disease identification, ultimately improving crop yield and quality.
Table of Contents
Project Overview
Features
Installation
Usage
Model Architecture
Results
Contributors
License
Project Overview
Agriculture is vital for global economies, yet plant diseases pose significant challenges. Traditional methods of disease diagnosis are often slow and labor-intensive. This project employs MobileNet, a lightweight Convolutional Neural Network (CNN), to automate the detection and classification of plant diseases from leaf images.
Project Overview
Features
High Accuracy: Utilizes state-of-the-art deep learning techniques for precise disease classification.
User-Friendly Interface: A GUI that allows easy interaction with the model.
Real-Time Predictions: Quickly identifies diseases from uploaded leaf images.
Installation
To set up the project locally, follow these steps:
Clone the Repository
bash
git clone https://github.com/yourusername/crop-disease-prediction.git
cd crop-disease-prediction
Install Required Packages
Ensure you have Python 3.x installed. Then, install the necessary packages using pip:
bash
pip install -r requirements.txt
Download the Dataset
Download the dataset from Kaggle and place it in the data/ directory.
Run the Application
Start the application by executing:
bash
python app.py
Usage
Launch the application.
Click on the "Select Image" button to upload a leaf image.
The model will process the image and display the predicted disease along with a confidence score.
Usage Example
Model Architecture
The model is built using MobileNetV2, which is optimized for performance on resource-constrained devices. The architecture includes:
Input Layer: Accepts images of size 100x100 pixels.
Depthwise Separable Convolutions: Reduces computational load while maintaining accuracy.
Custom Classification Head: Tailored for multi-class classification with 38 output classes.
Model Architecture
Results
The model has been evaluated on a diverse dataset, achieving high accuracy in classifying various plant diseases. Below are some sample results:
Leaf Image	Predicted Disease	Confidence Score
Leaf Image 1	Leaf Blight	92%
Leaf Image 2	Powdery Mildew	88%
Contributors
This project was developed by:
Rahul Singh (mcs24027@iiitl.ac.in)
Saksham (mcs24025@iiitl.ac.in)
Rohit Bahuguna (mcs24038@iiitl.ac.in)
Jay Katre (mcs24041@iiitl.ac.in)
License
This project is licensed under the MIT License - see the LICENSE file for details. Feel free to explore the repository, contribute, or reach out if you have any questions! Together, we can enhance agricultural productivity through technology.
