# Neural Style Transfer Model

## Overview
This project implements a **Neural Style Transfer (NST)** model that combines the content of one image with the artistic style of another. It leverages deep learning and a pre-trained Convolutional Neural Network (CNN) for feature extraction.

## Features
- Transfer artistic styles to content images.
- Support for multiple style images and custom blending.
- Adjustable hyperparameters for content and style loss.
- Produces high-quality, smooth outputs.

## Architecture
The model uses a pre-trained CNN (e.g., VGG-19) to extract image features and optimize a combined loss function:
- **Content Loss**: Preserves the structure of the content image.
- **Style Loss**: Matches textures and patterns of the style image.
- **Total Variation Loss** (optional): Enhances the smoothness of the generated image.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

2.Install the dependencies
  pip install -r requirements.txt

3. Download the pre-trained model weights (if required) and place them in the models/ directory.

## Results

Here are some example results produced by the model:

Content Image:![figures](https://github.com/user-attachments/assets/d7434af4-5a5a-4281-a9aa-54926ebf34a5)


Style Image:![vg_starry_night](https://github.com/user-attachments/assets/75463629-985b-4e8c-8d86-6b3f8c0256e8)


Output Image:![WhatsApp Image 2025-01-07 at 13 44 44_edc958aa](https://github.com/user-attachments/assets/fc505015-eca8-43b7-aff7-4cff34e758ed)
