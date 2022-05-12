# Image Super Resolution using Generative Adversarial Networks

This project has been implemented as part of EE541 - A Computational Introduction to Deep Learning. The goal of this project is to generate high resolution images from low resolution images using GANs.

## Setup
The models for this project were trained on Google Colab Pro with NVIDIA Tesla K80 GPU. The GPU on Google Colab can be activated by changing the Runtime Type to GPU.

## Installation
- If running the code on Google Colab, you only need to activate the Nvidia GPU. No further installation necessary.
- Install conda environment using the ee541.txt file

## Downloading the Dataset
- Dataset need not be downloaded explicitly. Run the dataset download code snippet in srgan.ipynb to download the datafiles and unzip them. 
- There is no train set available for the dataset. Hence, the validation images are used for testing. The train set is split into train and validation sets when necessary.

## Code Structure
- The complete code is in the SRGAN directory
- srgan.ipynb contains the code to train the GAN model and test it.

## Architecture
The architecture for this model is insipired from the original paper by Christian Ledig et al. titled 'Photo-Realistic Single Image Super-Resolution using a Generative Adverserial Network'
