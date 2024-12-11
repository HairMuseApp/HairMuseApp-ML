# HairMuse - Machine Learning 🤖 

## Overview
HairMuseApp-ML is a machine learning project that recommends hairstyles based on face shape. The model uses **ResNet50**, a powerful deep learning architecture, to classify face shapes and provide suitable hairstyle recommendations for all genders.
This is an image classification project designed to predict 
the shape of a person’s face using Convolutional Neural Networks (CNN).
We developed this as part of our Capstone Project for predicting the ideal hairstyle based on face shape. 
The model has been built to classify the face shape of a user into one of several categories, helping them find the most flattering hairstyles. 

## Model Overview
For this project, by using a **Deep Learning** approach with **Convolutional Neural Networks (CNN)** to classify face shapes into one of the following categories:
- Heart
- Oblong
- Oval
- Round
- Square

## Features
- **Face Shape Detection**: Detects key facial features to classify face shapes.
- **ResNet Model**: Uses a pretrained ResNet model for image classification and hairstyle prediction.
- **Easy-to-use Interface**: Upload an image, and the model will recommend the best hairstyle.

## Requirements
1. **Python** version 3.8 or higher.
2. **Jupyter Notebook** or **JupyterLab** installed.
3. The required Python packages:
   - `numpy`
   - `pandas`
   - `matplotlib`
   - `seaborn`
   - `termcolor`
   - `scikit-learn`
   - `pillow`
   - `tensorflow`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/HairMuseApp/HairMuseApp-ML.git
   ```

2. Navigate to the project directory:
   ```bash
   cd HairMuseApp-ML
   ```

## Usage
### 1. Run the Notebook

Open Jupyter Notebook or JupyterLab and run the `HairMuseApp.ipynb` file. Follow the steps outlined in the notebook to process data and predict face shapes.

To open the notebook, use the following command:
```bash
jupyter notebook HairMuseApp.ipynb
```

### 2. Upload an Image

In the designated cell, upload your face image in `.jpg` or `.png` format. Ensure the image clearly shows the front-face.

### 3. Run the Prediction

Follow the instructions in the notebook to run the prediction model. The model will process the image to give face shape based on face shape.

### Sample Output

After running the prediction, you will see what kind of face shape you are as text. Below is an example of the output:

- **Prediction**: "Oval"
- **Confidence**: 44.12%

## Contributing
Feel free to fork the repository and submit pull requests. Contributions to improve the model, dataset, or add new features are welcome!


---

