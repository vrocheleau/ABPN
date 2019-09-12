# ABPN (Attention based Back Projection Network for image ultra-resolution)

By Zhi-Song, Li-Wen Wang and Chu-Tak Li

This repo only provides simple testing codes, pretrained models and the network strategy demo.

We propose a single image super-resolution using Attention based Back Projection Network (ABPN) to achieve good SR performance with low distortion.


# For proposed HBPN model, we claim the following points:

• Attention Back Projection Block to learn cross-correlation of features.

• Refined Back Projection Block to estimate super-resolution residues for better reconstruction.

# Dependencies
    Python > 3.0
    OpenCV liberary
    Pytorch 1.1 
    NVIDIA GPU + CUDA
    MATLAB 6.0 and above

# Complete Architecture
The complete architecture is shown as follows,

![network](/figure/network.png)

# Implementation
## 1. Testing
---------------------------------------
### s1. Run **AIM_ensemble.py**. Modify the directories of files based on your working environment.

Testing images on AIM2019 Real Super-Resolution Challenge can be downloaded from the following link:

https://competitions.codalab.org/competitions/20235

General testing dataset (Set5, Set14, BSD100, Urban100 and Manga109) can be downloaded from:

https://github.com/LimBee/NTIRE2017

## 2. Training
---------------------------
### s1. Download the training images from DIV2K and Flickr.
    
https://data.vision.ee.ethz.ch/cvl/DIV2K/

https://github.com/LimBee/NTIRE2017
   
### s2. Start training on Caffe
For user who already has installed Pytorch 1.1, simply just run the following code:
```sh
$ python main.py
```

---------------------------
  
# Experimental results

Testing results on AIM2019 RealSR can be downloaded from the following link:

https://drive.google.com/open?id=1lJFvNKSUxg-pioKqjA39GPqDvvv3ceYj

## Partial image visual comparison


