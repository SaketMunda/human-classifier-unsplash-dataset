# Human classifier using Unsplash Lite Dataset

**Problem Definition**:

Building a Human classifier using Transfer Learning on [Unsplash Lite Dataset](https://unsplash.com/data)

Demo Link : [coming soon]()

## End-To-End Deep Learning Model 

This repository demonstrates the power of Transfer Learning using models available on [TensorFlow Hub](https://www.tensorflow.org/hub) saved models. But, the main goal to touch the base of each steps during an end-to-end flow of a deep learning model using Transfer Learning.

So basically, this **custom human-classifier model is a computer vision model which takes an input image, and tells whether that image contains human or not**.

## What I've Learned

- Data Extraction from [Unsplash Lite Dataset](https://unsplash.com/data)
  - Build your own dataset(train & test) for human and non-human images
  - Check file `create_unsplash_dataset_human_classifier.ipynb`
- Image preprocessing using `tf.keras.preprocessing.image_dataset_from_directory`
- Data Augmentation as a layer
- Using Functional API for building the model
- Created a `base model` for leveraging the pre-trained model available through `tf.keras.applications`
  - For this experiment, I've used [EfficientNetB0](https://www.tensorflow.org/api_docs/python/tf/keras/applications/efficientnet/EfficientNetB0) Model
- Monitor the model's training using callbacks
  - TensorBoard callbacks for tracking loss curves and accuracy per epoch

## Steps to follow (if you want to try and playaround)

1. Download Unsplash Lite Dataset from [here](https://unsplash.com/data)
2. Store the Downloaded zipfile where you can access through `jupyter notebook` or `google colab`, *I prefer google drive and access it on colab*
3. Create a dataset based on your experiments, here I'm building Human Classifier so I've created a dataset of Human and Non-human, you can do the same by replacing the keywords used in file `create_unsplash_dataset_human_classifier.ipynb`.

*By now you should have two directories train and test in your drive and inside of each directory must contain folders with same name as the class name for the experiment and inside of those folders must have their respective images.*

Also you can read the blog for more details : https://5aket.hashnode.dev/human-classifier-using-transfer-learning

### Deployment


## Demo

## Acknowledgements

- [Unsplash](https://unsplash.com/)
