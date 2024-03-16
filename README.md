# Ai-for-Media23-24
# YOLOv5 Style Transfer and Mask Application

This project combines the powerful object detection capabilities of YOLOv5 with cutting-edge style transfer techniques and mask applications, creating a unique pipeline for processing images. By applying artistic style transfer to the objects in an image and accurately masking detected objects, we achieve a blend of artistic expression and object detection.

## Setup

To get started, clone the YOLOv5 GitHub repository and install the necessary dependencies:

git clone https://github.com/ultralytics/yolov5

cd yolov5

pip install -qr requirements.txt comet_ml

## Train

For those looking to train YOLOv5 with custom datasets, using Roboflow for dataset label management. It simplifies the tasks of organizing, labeling, and preparing datasets for training. Visit Roboflow for more information.

## Style Transfer and Mask Application

Select Style Images: Select one style image of Picasso to be used as the basis for style migration.

Apply Style Migration: Apply the selected styles to the target detected images using a style migration algorithm such as that implemented in PyTorch. Existing style migration libraries such as StyleTransfer in torchvision.models can be used.

Generate Masks: Use the results of YOLOv5 detection to create a mask for each detected object.

Apply Mask: Apply style migration to non-targeted areas of the image, preserving the original appearance of the target object, or vice versa, applying style migration only to the target object.

## AI Disclaimer

AI-Generated Features: Border Extraction and Blending

The methodologies for extracting object borders and blending them seamlessly with stylized backgrounds were developed with the assistance of AI prompts provided to OpenAI's GPT models. These processes leverage advanced algorithms to ensure the integrity of object detection while integrating artistic elements.



## Credits and References:

YOLOv5 GitHub Repository: https://github.com/ultralytics/yolov5

PyTorch Style  Transfer Documentation: https://pytorch.org/tutorials/advanced/neural_style_tutorial.html?highlight=style%20transfer

Roboflow: https://roboflow.com
