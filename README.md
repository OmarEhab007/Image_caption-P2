# Image Captioning Project
This repository contains code and resources for the Image Captioning project, which is part of the Udacity Computer Vision Nanodegree program. The goal of this project is to generate captions for input images using a deep learning model.

## Project Overview
The project consists of the following main components:

- Data preparation: We use the Microsoft COCO dataset to train and evaluate our model.
- Model architecture: We use a CNN-RNN architecture to generate captions for images. Specifically, we use a pre-trained ResNet-50 model to extract features from the input image, and then feed these features into a LSTM model to generate the caption.
- Training the model: We train the model on a subset of the COCO dataset and evaluate it on a held-out validation set.
- Generating captions: Once the model is trained, we use it to generate captions for test images.
## Getting Started
To get started with this project, you need to do the following:

1. Clone this repository:
```bash
git clone https://github.com/OmarEhab007/Image_caption-P2.git
```
2. Download the COCO dataset and pre-trained ResNet-50 model by running the following command:
```bash
./download.sh
```
3. Install the required Python packages by running the following command:
```pip install -r requirements.txt```
4. Open the Jupyter Notebook 2_Training.ipynb and follow the instructions to train the model.
5. Open the Jupyter Notebook 3_Inference.ipynb and follow the instructions to generate captions for test images.
### Acknowledgements
This project is based on the Image Captioning project by Yunjey Choi.
