# Human classifier using Unsplash Lite Dataset

**Problem Definition**:

Building a Human classifier using Transfer Learning on Unsplash Lite Dataset

Demo Link : [coming soon]()

## End-To-End Deep Learning Model 

This repository demonstrates the power of Transfer Learning using models available on TensorFlow Hub saved models. But, the main goal to touch the base of each steps during an end-to-end flow of a deep learning model using Transfer Learning.

So basically, this **custom human-classifier model is a computer vision model which takes an input image, and tells whether that image contains human or not**.

## What I've Learned

- Data Extraction from Unsplash Lite Dataset
- Build your own dataset(train & test) for human and non-human images
- Image preprocessing using `tf.keras.preprocessing.image_dataset_from_directory`
- Data Augmentation as a layer
- Using Functional API for building the model
- Created a `base model` for leveraging the pre-trained model available through `tf.keras.applications`
  - For this experiment, I've used [EfficientNetB0]() Model
- Monitor the model's training using callbacks
  - TensorBoard callbacks for tracking loss curves and accuracy per epoch

### Deployment



## Demo
