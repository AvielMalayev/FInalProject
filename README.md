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
- A machine with access to the internet
- GPU acceleration (recommended for model training)

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

## Contributing
Contributions to this project are welcome! Please fork the repository and submit a pull request with your enhancements. For major changes, please open an issue first to discuss what you would like to change.

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
Aviel Malayev 
Omri Shalev

Project Link: https://github.com/AvielMalayev/FInalProject.githttps://github.com/AvielMalayev/FInalProject.git 
