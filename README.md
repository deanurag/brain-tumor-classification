
---

# Brain Tumor Classification Using CNN

## Overview

This project aims to develop a machine learning model to classify MRI images into three types of brain tumors: glioma, meningioma, and pituitary tumor. The model enhances diagnostic accuracy and aids in early detection, potentially improving patient outcomes.

## Table of Contents

- [Brain Tumor Classification Using CNN](#brain-tumor-classification-using-cnn)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Dataset](#dataset)
  - [Model Architecture](#model-architecture)
  - [Results](#results)
  - [License](#license)
  - [Acknowledgements](#acknowledgements)

## Dataset

The dataset used in this project consists of MRI images categorized into three types of brain tumors:
- Glioma
- Meningioma
- Pituitary Tumor

The dataset is split into training, validation, and test sets to evaluate the model's performance.

## Model Architecture

The model is implemented using a Convolutional Neural Network (CNN) with the following architecture:
- Convolutional Layers: Extract features from the input images.
- Pooling Layers: Reduce the spatial dimensions of the feature maps.
- Fully Connected Layers: Perform classification based on the extracted features.

The model is optimized using the Adam optimizer to achieve high accuracy.

To run this project, you need to have Python and the following libraries installed:

- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

You can install the required libraries using pip:


## Results

The model achieved a classification accuracy of 92% on the test dataset, demonstrating its effectiveness in accurately identifying different types of brain tumors from MRI images.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The dataset used in this project was provided by Kaggle.
- Special thanks to the contributors of TensorFlow and Keras for their excellent libraries.

---

