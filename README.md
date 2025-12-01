# Ai-thing
Manuel Velazquez z23755622
# Facial Emotion Recognition using Deep Learning

**Course:** CAP 4630 – Intro to Artificial Intelligence  
**Instructor:** Dr. Ahmed Imteaj  
---

## 1. Project Overview

This project implements a facial emotion recognition system using deep learning.  
The goal is to classify images of human faces into seven emotion categories:

- Angry
- Disgust
- Fear
- Happy
- Neutral
- Sad
- Surprise

The project includes a baseline Convolutional Neural Network (CNN) trained from scratch and an improved model using **MobileNetV2** with transfer learning.

---

## 2. Dataset

The dataset consists of grayscale facial images labeled with one of the seven emotions above.  
Images vary in pose, lighting, and expression intensity.
- **Source:** https://www.kaggle.com/datasets/fahadullaha/facial-emotion-recognition-dataset/data
- **Format:** Images organized in folders per class
- **Used Splits:**
  - ~80% training (with augmentation)
  - ~20% validation for evaluation

> Note: The dataset itself is **not** stored in this repository due to size limits.  
> Please download it from the link above and place it in the correct folder structure as described in the notebook.

This project was developed and tested in Google Colab using Python and TensorFlow.

Main libraries:

tensorflow

numpy

matplotlib

scikit-learn

keras

How to Run the Project
Make a google collab account 
Upload the facial_emotion_project.ipynb notebook to Google Colab.
Download the dataset from the link above.
Upload/extract the dataset into Google Drive and mount it in Colab (instructions are inside the notebook).
Run the cells from top to bottom:

if need be heres my google drive 
https://drive.google.com/file/d/1p08RmCWoz1yVdRiiahF2NhL8CD93ZD7i/view?usp=sharing
And heres the collab link source thing
https://colab.research.google.com/drive/1J1QeNRGxpXI6gxjuYaMPoCm7wHBqL-XR?usp=sharing
