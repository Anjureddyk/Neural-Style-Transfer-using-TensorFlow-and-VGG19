# Neural-Style-Transfer-using-TensorFlow-and-VGG19

## Overview
This project implements Neural Style Transfer using TensorFlow, VGG19, and TensorFlow Hub. Neural Style Transfer is a technique that involves applying the artistic style of one image to another image while preserving the content of the latter. The project uses a pre-trained VGG19 model to extract content and style features from images, and optimizes a generated image to match the style of the style image and the content of the content image.

## Introduction
Neural Style Transfer uses deep neural networks to apply the artistic style of one image to the content of another image. This project leverages the pre-trained VGG19 model to extract high-level features from the images and TensorFlow Hub to apply the style transfer using a pre-trained model for arbitrary image stylization.

## Installation
1. Clone the repository:
   git clone https://github.com/Anjureddyk/Neural-Style-Transfer-using-TensorFlow-and-VGG19.git

   cd style-transfer

3. Create and activate a virtual environment:
   python -m venv venv

   source venv/bin/activate   # On Windows use `venv\Scripts\activate`

5. Install the required packages:
   pip install -r requirements.txt

## Results
The generated images after each epoch will be displayed and saved in the output directory, showcasing the evolution of the image as it adopts the style of the style image while retaining the content of the content image.

## References
* A Neural Algorithm of Artistic Style
* TensorFlow Documentation
* TensorFlow Hub

## License
This project is licensed under the MIT License. See the LICENSE file for details.
