# HairMuse 💇‍♀️🤖 Machine Learning Project

## Project Overview

HairMuse is an innovative machine learning application designed to recommend personalized hairstyles based on individual face shapes. Leveraging the power of deep learning and computer vision, our project uses a **ResNet50** Convolutional Neural Network (CNN) to classify face shapes and provide tailored hairstyle recommendations across all genders.

## Key Features

- **Advanced Face Shape Detection**: Accurately identifies facial features to classify face shapes
- **Deep Learning Powered**: Utilizes pre-trained ResNet architecture for precise image classification
- **User-Friendly Interface**: Simply upload a photo to receive personalized hairstyle recommendations
- **Multi-Shape Support**: Classifies faces into 5 distinct shape categories

## Supported Face Shapes

- Heart
- Oblong
- Oval
- Round
- Square

## Technical Stack

- **Language**: Python 3.8+
- **Framework**: TensorFlow
- **Model Architecture**: ResNet50
- **Libraries**: 
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - Pillow

## Prerequisites

Before installation, ensure you have:
- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- pip package manager

## Setup and Running the Project

### Local Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/HairMuseApp/HairMuseApp-ML.git
   ```

2. Navigate to the project directory:
   ```bash
   cd HairMuseApp-ML
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook HairMuseApp.ipynb
   ```

### Running on Google Colab

1. Open Google Colab:
   - Go to [Google Colab](https://colab.research.google.com/)
   - Click on "File" > "New Notebook" or "Open Notebook"

2. Clone the GitHub Repository:
   ```python
   !git clone https://github.com/HairMuseApp/HairMuseApp-ML.git
   ```

3. Change Directory:
   ```python
   %cd HairMuseApp-ML
   ```

4. Open the Notebook:
   - In Colab, use "File" > "Open notebook" 
   - Navigate to the cloned repository
   - Open `HairMuseApp.ipynb`

### Usage Guide

1. Upload a front-facing image (`.jpg`, `.jpeg`, `.png`)

2. Execute the prediction cells

### Sample Output

```
🔍 Prediction: Oval 
📊 Confidence: 44.12%
```

## How It Works

1. Image Upload: User submits a clear, front-facing photo
2. Face Detection: CNN processes facial features
3. Shape Classification: Determines face shape
4. Recommendation: Suggests most flattering hairstyles

## Future Roadmap

- Enhance model accuracy
- Expand hairstyle recommendation database
- Develop mobile application
- Implement real-time styling suggestions
