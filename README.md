# Liver Tumor Segmentation Using Machine Learning

## Project Overview
This project applies deep learning models U-net, ResUNet, and TransUNet for the segmentation of liver tumors from CT scans. Utilizing the LiTS17 dataset, we have explored various architectures and hyperparameters to find the most effective methods in terms of Accuracy, True Positive Rates, and Dice scores. This repository contains the code and documentation for deploying and testing these models.

## System Requirements
### Software
- Python 3.8 or above
- TensorFlow 2.x
- NumPy
- NiBabel
- Google Colab (for model execution and training)

### Hardware
- Google Colab A-100 GPU

## Usage
### Data Preparation
Ensure you have the LiTS17 dataset downloaded and stored in a directory accessible to the scripts. Update the dataset paths in the configuration files accordingly.

### Model Training and Evaluation
Navigate to the specific model notebook on Google Colab:
- U-Net.ipynb
- ResUNet.ipynb
- TransUNet.ipynb

Follow the instructions within each notebook to train and evaluate the models. Adjust the hyperparameters as necessary to experiment with different configurations.

### Running the Dual-Model Approach
To execute the dual-model approach that segments the liver and then the tumors:
1. Open the TwoModelsApproach.ipynb on Google Colab.
2. Ensure all paths and parameters are correctly set.
3. Run the notebook cells sequentially to process the data, train the models, and perform segmentation.

## Authors
Aviel Malayev, 
Omri Shalev
