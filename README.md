# Breast Cancer Detection using Histopathology Images

## Overview

This project focuses on utilizing histopathology images to detect breast cancer. The dataset used for this project was obtained from Kaggle, and the detection model was built using Keras Tuner , and pretrained model VGG16 and ResNet50. 

## Dataset

The dataset used in this project can be found on Kaggle: [Kaggle Breast Cancer Histopathological Images](https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images/data)

Ensure that you have the necessary permissions to access and use the dataset according to Kaggle's terms and conditions.

## Model Architecture
### Keras-tuner
Keras Tuner is a hyperparameter tuning library for Keras, which is a high-level neural networks API running on top of TensorFlow or other lower-level neural network libraries. Hyperparameter tuning involves finding the best set of hyperparameters for a machine learning model to optimize its performance.

With Keras Tuner, you can define a search space of hyperparameters and search for the best combination using techniques like Random Search or Bayesian Optimization. This can be particularly useful for optimizing the performance of neural networks.
### VGG16 and ResNet-50
VGG16 (Visual Geometry Group 16) and ResNet-50 (Residual Network with 50 layers) are popular pre-trained convolutional neural network (CNN) architectures for image classification tasks. These models are available in Keras applications module and can be easily loaded for transfer learning.

VGG16:

VGG16 is known for its simplicity with a uniform architecture of 3x3 convolutional layers.
It's effective for various image classification tasks, including medical image analysis.
ResNet-50:

ResNet introduced the concept of residual learning, which helps in training very deep networks.
ResNet-50 has 50 layers and is widely used for various computer vision tasks due to its performance.
## Dependencies

Make sure you have the following dependencies installed before running the code:

- Python (version 3.10.12)
- TensorFlow (version 2.13.0)
- Keras (version 2.13.1)
- Keras Tuner (version 1.3.5)
- Other required libraries

# Breast Cancer Classification Results

## ResNet50 Model:

- **Precision:** 0.8569
- **Accuracy:** 0.8848
- **Recall:** 0.9196
- **F1 Score:** 0.8871

## VGG16 Model:

- **Precision:** 0.8892
- **Accuracy:** 0.8673
- **Recall:** 0.8343
- **F1 Score:** 0.8609

## Keras Tuner Model:

- **Precision:** 0.8784
- **Accuracy:** 0.8760
- **Recall:** 0.8684
- **F1 Score:** 0.8734

---

### Conclusion:

- The ResNet50 model demonstrated high recall, indicating its effectiveness in correctly identifying positive cases.
- VGG16 achieved a good balance between precision and recall, leading to a reliable classification performance.
- The Keras Tuner model, with its tuned hyperparameters, showcased competitive precision and accuracy.

These results provide insights into the performance of different models for breast cancer classification. Consideration of specific requirements and trade-offs between precision and recall can guide the selection of the most suitable model for your application.

---


## Future Work
Research Paper:
Document the methodology, results, and insights gained from this project to contribute to the existing body of knowledge in the field of breast cancer detection using histopathology images.

Website Hosting:
Develop and host a website where users can interact with the model, submit images for analysis, and access information about breast cancer detection.
## Contributors
[Aaditya Gupta](https://github.com/AadityaGupta700)

## Acknowledgments
Special thanks to Kaggle for providing the breast cancer histopathological images dataset and the open-source community for their valuable contributions to the field of deep learning.

Feel free to contribute, report issues, or suggest improvements. Happy coding
