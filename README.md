# ResNet18_Weather_Classification

## 📌 Overview
This project implements a ResNet-based Convolutional Neural Network to classify weather conditions from images. It demonstrates an end-to-end pipeline using a custom image dataset of various weather scenarios.

## 📚 Background
What is ResNet?
ResNet (Residual Network) is a deep convolutional neural network architecture known for introducing residual connections, which allow layers to learn identity mappings. This helps mitigate the vanishing gradient problem and enables training very deep networks.

The ResNet used in this project is a custom implementation with the following architecture:
- Residual blocks with skip connections
- Four convolutional stages: [64, 128, 256, 512]
- Adaptive average pooling followed by a fully connected layer
- Inspired by ResNet-18 configuration

## 🧾 Dataset: Weather Conditions Dataset
**Description:**
The dataset contains images categorized by different weather types. Each category is stored in a separate folder and represents a distinct class. Example weather categories include: cloudy, sunny, rainy, foggy, snowy.

- Total Classes: Varies depending on subfolders
- Format: JPEG/PNG images
- Directory Structure:

```
weather-dataset/
└── dataset/
    ├── cloudy/
    ├── foggy/
    ├── rainy/
    ├── snowy/
    └── sunny/
```
**Data Preprocessing**
- Images are resized to 224x224
- Normalized to [0, 1] by dividing pixel values by 255
- Split: Train: 70%, Validation: 20%, Test: 10%

## 📐 Task Adaptation
The classification problem is adapted to a multi-class classification task based on weather types. Each image is assigned a label depending on its folder name. Labels are integer-encoded using the folder structure automatically.

## 🏗️ Project Structure

## 🔧 Installation
You can clone and run on local machine

## 🧪 Training the Model
```
```
## 📏 Evaluation Metrics

## 🖼️ Sample Results

## 📌 References