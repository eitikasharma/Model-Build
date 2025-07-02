# 🤖 Smart Parking Guide – Model Files

TFJS Model for Real-Time Parking Sign Interpretation

This repository contains the converted TensorFlow.js model files and testing assets for the Smart Parking Guide(https://github.com/eitikasharma/ParkingApp) — a mobile application designed to help dyslexic drivers interpret complex parking signs using machine learning.

# 📂 Contents

File	Description:

model.json	JSON configuration of the trained TensorFlow model

group1-shard1of5.bin to group1-shard5of5.bin	Binary weight files (split for web compatibility)

Testing.ipynb	Notebook to test the model before deployment

Model_Test.zip	Zipped dataset for model validation and inference

.gitattributes	GitHub LFS settings for handling large binary files

# 🧠 Model Info

Base Model: InceptionV3

Framework: TensorFlow / Keras

Conversion: Done using tensorflowjs_converter

Classes: 31 parking sign types

Accuracy Achieved: ~95.83% (training) with strong generalization due to data augmentation

# 📄 Testing Notebook

Use Testing.ipynb to:

Load the .json and .bin files locally

Perform predictions on test images

Validate model behavior before integrating into the app
