# Automatic Image Captioning

This project implements an automatic image captioning system using deep learning techniques, specifically Convolutional Neural Networks (CNNs) for image feature extraction and Recurrent Neural Networks (RNNs) for language modeling. The model is trained on the Flickr8k dataset, a publicly available benchmark dataset containing 8,000 images with five captions each.
## Author 
Kiran Kher(https://github.com/kirankher/)

## Problem Overview

In a world filled with images from diverse sources, providing meaningful captions can enhance accessibility and understanding. This project addresses the challenge of automatically generating descriptive captions for images, eliminating the need for explicit textual descriptions. The application extends its utility to assist individuals with visual impairments, promoting inclusivity and equal opportunities.

## Features

- **Image Feature Extraction:** Utilizes CNNs to extract relevant features from input images.
- **Language Modeling:** Employs RNNs to generate coherent and contextually relevant captions for the images.
- **Flickr8k Dataset:** Trains the model on a comprehensive dataset containing a variety of images with associated captions.
- **Web Interface:** Implements a user-friendly web interface for users to upload images and receive generated captions.
- **Inclusive Design:** Aims to make images more accessible and understandable, especially for individuals with visual impairments.

## Requirements

### Hardware Requirements

- Processor: Any Processor above 2 GHz
- RAM: 8GB or above
- GPU: NVIDIA GeForce GTX 1060 or equivalent for accelerated deep learning
- Storage: 1TB SSD or higher for dataset storage

### Software Requirements

- Python environment with TensorFlow, Keras, and OpenCV
- Jupyter Notebook for development
- Operating System: Windows 10 or Linux
- Code editor: Visual Studio Code or equivalent
- Web browser for model deployment
- Flask framework for web application development

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/automatic-image-captioning.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Download the Flickr8k dataset and place it in the designated directory.

4. Train the model using the provided scripts:

    ```bash
    python train_model.py
    ```

5. Run the web application:

    ```bash
    python app.py
    ```

6. Access the application through your web browser at `http://localhost:5000`.

