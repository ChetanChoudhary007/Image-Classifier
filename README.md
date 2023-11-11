# Image Classifier : Happy and Sad People 

![Image Classifier](https://img.freepik.com/premium-vector/hands-holding-masks-with-happy-sad-faces-person-choosing-facial-expression-hiding-feelings-flat-vector-illustration-psychology-emotion-concept-banner-website-design-landing-web-page_74855-26025.jpg)

## Overview

Welcome to the Image Classifier project! This guide will help you set up, understand, and implement the project on your computer. Whether you are new to machine learning or looking for a practical example, this step-by-step guide is tailored for beginners.

## Prerequisites

Before you start, make sure you have the following installed:

- Python (3.x recommended)
- TensorFlow (2.x recommended)
- OpenCV
- Matplotlib
- Jupyter Notebook (optional)

You can install the required Python libraries by running:

```bash
pip install numpy os imghdr opencv-python matplotlib tensorflow
```

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/image-classifier.git
   cd image-classifier
   ```

2. **Set up Your Environment:**
   - Create a virtual environment (optional but recommended):
     ```bash
     python -m venv venv
     source venv/bin/activate  # Linux/Mac
     # OR
     .\venv\Scripts\activate  # Windows
     ```

   - Install required dependencies:
     ```bash
     pip install -r requirements.txt
     ```

3. **Explore the Code:**
   - Open the Jupyter notebook or Python script (`image_classifier.ipynb` or `image_classifier.py`) using your preferred IDE or Jupyter environment.

4. **Understand the Project Structure:**
   - Familiarize yourself with the project structure, including the data directory, code sections, and model saving paths.

## Running the Code

1. **Run Data Cleaning Section:**
   - Execute the data cleaning section to remove unsupported images and ensure data quality.

2. **Run Data Loading and Preprocessing Section:**
   - Load and preprocess the dataset to prepare it for training.

3. **Run Model Building and Training Section:**
   - Build the Convolutional Neural Network (CNN) model.
   - Train the model using the training set and validate it on the validation set.

4. **Evaluate Model Performance:**
   - View loss and accuracy curves to evaluate the model's performance on the validation set.

5. **Test the Model:**
   - Test the trained model on a sample image and observe the predicted result.

6. **Save and Load the Model:**
   - Save the trained model for future use.
   - Load the saved model and test it on a new image.
     
