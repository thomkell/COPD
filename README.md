# COPD Severity Staging Project

This repository contains code for a project focused on staging the severity of Chronic Obstructive Pulmonary Disease (COPD) using CT images. The primary goal is to improve the accuracy of COPD severity staging through the application of deep learning techniques.

## Project Overview

This project implements a model architecture based on U-Net to enhance CT image segmentation and classification. The model is trained to predict the severity of COPD based on medical imaging data.

**Note:** Due to privacy and legal restrictions, the actual CT image data used in this project is not included in this repository.

## Repository Structure

- **/notebooks/**: Jupyter notebooks detailing the process of model training and evaluation:
  - `3Dpix2pix192x192x192-Div3000-Mask-defEx2-Diceloss2-2.ipynb`: Notebook for training the 3D U-Net model.
  - `3DMetrics-ImgGenerator-Div3000-Mask-defEx2-Diceloss2.ipynb`: Notebook for evaluating the model.

## Requirements

To run the code, you will need the following libraries:

- Python 3.x
- TensorFlow
- Keras
- NumPy
- OpenCV
- Matplotlib
