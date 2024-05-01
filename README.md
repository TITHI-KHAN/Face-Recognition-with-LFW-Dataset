# Face Recognition with LFW Dataset

![image](https://github.com/TITHI-KHAN/Face-Recognition-with-LFW-Dataset/assets/65033964/1185f570-b750-4408-8978-91adfe3841b7)

## Dataset

Labelled Faces in the Wild (LFW) Dataset - https://www.kaggle.com/datasets/jessicali9530/lfw-dataset
opencv-face-recognizer Dataset - https://www.kaggle.com/datasets/libor8/opencvfacerecognizer

## Code Explanation

1. **Imports and Setup**: The code begins by importing necessary libraries such as warnings, os, matplotlib, PIL, random, pandas, cv2 (OpenCV), numpy, and sklearn. It also sets up the directory path for the LFW dataset and creates necessary directories.

2. **Load and Display Sample Images**: It loads sample images from the LFW dataset, displays their properties, and then displays a few sample images from randomly selected persons to understand the variety and distribution of faces.

3. **Visualize Diversity of Faces**: It selects random persons and displays one random image per person to visualize the diversity of faces in the dataset.

4. **Visualize Distribution of Images Per Person**: It loads a CSV file containing information about the number of images per person and plots a histogram to visualize the distribution of images per person.

5. **Basic Statistics**: It provides basic statistics about the number of images per person.

6. **Load Metadata Files**: It loads additional metadata CSV files for analysis.

7. **Face Detection and Recognition**: It performs face detection using OpenCV's pre-trained face detector and recognizes faces by comparing their embeddings with embeddings extracted from the dataset using an OpenFace model.

8. **Visualize Recognition Results**: It loads a test image, detects faces, recognizes them, and overlays recognition labels and confidence scores on the image.
