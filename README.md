# OCT Retina Disease Classification using EfficientNetB3

This project applies a deep learning model using **EfficientNetB3** to classify retinal diseases from Optical Coherence Tomography (OCT) images.

## 🔍 Overview

This notebook trains a convolutional neural network for image classification on an OCT retinal disease dataset. It uses the **EfficientNetB3** architecture for transfer learning.

## 📁 Dataset

- **Source:** [Retinal OCT C8 Dataset on Kaggle](https://www.kaggle.com/datasets/obulisainaren/retinal-oct-c8)
- This dataset contains categorized retinal OCT images for deep learning tasks.

## ⚙️ Model Details

- **Architecture:** EfficientNetB3 (via Keras Applications)
- **Optimizer:** Adam
- **Loss Function:** Likely `categorical_crossentropy`
- **Metrics:** Accuracy
- **Epochs:** Custom-defined (in plotting code)
- **Batch Size:** Not explicitly defined

## 📊 Output

The notebook includes:
- Model training and validation
- Accuracy plots across epochs
- Evaluation results (final performance metrics)

## ✍️ Notes

> _**Edited by Gagan - Modified Version of Friend's Notebook**_

## 🚀 How to Run

1. Install dependencies:
    ```bash
    pip install tensorflow matplotlib
    ```
2. Run the notebook in Jupyter:
    ```bash
    jupyter notebook oct-cnn-efficientnetb3-tensorflow-edited.ipynb
    ```

## 📌 Acknowledgements

Based on a friend's original work. This version includes light modifications by Gagan.
