# Explainable Pneumonia Detection Project Group C2

This is a group project for ACIT4620. A deep learning model to detect pneumonia in chest x-rays from the CheXpert dataset.

# How to run: 
- Make sure you have **Python 3.10** installed.
- Create, and activate a virtual environment.
- Install the packages: pip install -r requirements.txt

- Unzip the dataset into the data/ folder. It should look something like this: C:\Users\Leo\Desktop\Group_Pneumonia_Detection\data\train

**Note:** The next two steps for CUDA and cuDNN are **only required for training the models**. If you are using a pre-saved model(example: for Grad-CAM), you can skip them.
- You must install **CUDA Toolkit 11.2**.
- You must install **cuDNN 8.1** for CUDA 11.2.

