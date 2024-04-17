Face Mask Detection Model
 Overview
  This repository contains code for a face mask detection model created using fine-tuning of the VGG16 convolutional neural network (CNN).
  The model is trained to detect whether individuals in images or video frames are wearing face masks or not.

 Features
 -Utilizes transfer learning by fine-tuning the pre-trained VGG16 model.
 -Capable of detecting face masks in images and video frames.
 -Provides accurate and real-time predictions.
 
 Requirements
  -Python 3.x
  -TensorFlow 2.x
  -Keras
  -OpenCV (cv2)
  -Numpy
  -Matplotlib (optional, for visualization)

  Installation
  -Clone this repository to your local machine
  -Install the required dependencies using pip

Usage
 1.Prepare your dataset:
   a.Organize your dataset into two classes: "with_mask" and "without_mask".
   b.Ensure that each class has its own directory containing corresponding images.
 2.Fine-tune the VGG16 model:
   a.Use the train_mask_detector.py script to fine-tune the VGG16 model on your dataset.
 3.Test the model:
  a.Use the detect_mask_image.py script to detect face masks in images.
  b.Use the detect_mask_video.py script to detect face masks in real-time video streams.
  
