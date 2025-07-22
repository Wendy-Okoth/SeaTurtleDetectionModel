# Sea Turtle Face Detection Model

This repository contains the code and resources for training a custom YOLOv8 object detection model to identify and locate sea turtle faces in images. The project utilizes a dataset of sea turtle images with bounding box annotations to train a robust model capable of accurate detection.

## Project Goals

* **Dataset Preparation:** Process raw image data and bounding box annotations into the YOLOv8-compatible format.
* **Model Training:** Train a YOLOv8n (nano) model using transfer learning on a custom dataset.
* **Model Evaluation:** Assess the trained model's performance using standard object detection metrics (Precision, Recall, mAP).
* **Inference:** Demonstrate how to use the trained model to make predictions on new, unseen images.

## Dataset

The dataset used for training is sourced from a competition (e.g., Kaggle, or a similar source). It consists of:
* `IMAGES_512.zip`: A collection of sea turtle images, each 512x512 pixels.
* `Train.csv`: A CSV file containing bounding box annotations for the training images, with normalized `x`, `y`, `w`, `h` coordinates.
* `SampleSubmission.csv`: A sample submission file (used for inference output formatting if applicable).

**Note:** Due to file size limitations, the original `IMAGES_512.zip` and the trained `best.pt` model are not directly committed to this repository. Links to download them (or access the trained model) are provided below:

* [trained model weights](https://drive.google.com/uc?id=10RZTojUYdDgqn3EnjcEgS-SpslE7HE8j&export=download)
* [complete dataset](https://drive.google.com/uc?id=1cay0V4judlmnphCV9O6YOTht5nXh2bMX&export=download)
