
# ICU Monitor Screen Extraction

This project focuses on the extraction of ICU monitor screens from medical images using a transfer learning technique with the ResNet model. By training a customized ResNet on a specialized dataset of ICU monitor images and labels, the model effectively identifies and extracts screens from complex medical imagery. 
## Introduction

ICU monitors display critical information about patients' vital signs. Extracting this information accurately from images can significantly aid in patient monitoring and data analysis. This project employs the ResNet architecture with transfer learning to achieve high precision in extracting ICU monitor screens from various medical images.
## Features

- Utilizes transfer learning with the ResNet model for screen extraction.
- Trained on a custom dataset of ICU monitor images and labels.
- Enhances the accuracy of medical image processing.
- Facilitates better analysis and monitoring in critical care environments.
## Prerequisites

Ensure you have the following installed on your system:

- **Python** 
- **PyTorch** 
- **NumPy**
- **OpenCV**
- **Matplotlib**




## Hyperparmeters
- learning_rate: 0.001
- batch_size: 8
- epochs: 50
- optimizer: Adam
- loss: MSELoss

