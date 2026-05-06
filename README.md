# CNN-Based Real-Time Visual Monitoring System for Smart Factory Automation

##  Overview

This project presents a Convolutional Neural Network (CNN)-based system for real-time detection of surface defects in industrial environments. The system is designed for smart factory automation to improve quality control and reduce manual inspection.

##  Dataset

* NEU Surface Defect Dataset
  [https://www.kaggle.com/datasets/kaustubhdikshit/neu-surface-defect-database]
* 1,800 grayscale images
* 6 defect classes:

  * Patches
  * Crazing
  * Pitted Surface
  * Inclusion
  * Scratches
  * Rolled-in Scale

##  Model Architecture

* Custom CNN with:

  * Convolutional layers + ReLU activation
  * Max-pooling layers
  * Fully connected dense layers
  * Softmax output layer
* Optimizer: Adam
* Loss Function: Categorical Crossentropy
* Data Augmentation applied for better generalization

## Results

* Training Accuracy: **99.00%**
* Validation Accuracy: **98.55%**

The proposed model demonstrates high stability with minimal overfitting and outperforms several benchmark models on the same dataset.

##  Technologies Used

* Python
* NumPy
* OpenCV
* Matplotlib

##  How to Run

1. Install required libraries:
   pip install tensorflow opencv-python numpy matplotlib

2. Open the notebook:
   cnn_training.ipynb

3. Run all cells to train and test the model

##  Project Structure

* `src/` → training code
* `models/` → saved CNN model (.h5)
* `report/` → dissertation/report
* `results/` → output graphs
