# OS-MedSeg
This is a PyTorch implementation of: Distillation Learning Guided by Image Reconstruction for One-Shot Medical Image Segmentation.
## Overview 
<div style="text-align: center;">
  <img src="https://github.com/NoviceFodder/OS-MedSeg/blob/main/figuers/intro.png" alt="Description" width="50%" height="50%" />
</div>
Overview of our problem. Our proposed method achieves natural, realistic, and smooth segmentation, outperforming current state-of-the-art one-shot method.

## Framework Architecture
<img src="https://github.com/NoviceFodder/OS-MedSeg/blob/main/figuers/Framework.png" alt="Framework" />

## Demo
In [test_example.ipynb](https://github.com/NoviceFodder/OS-MedSeg/blob/main/test_example.ipynb), we provide a demo for medecal image segmentation. 

You can easily apply our pre-trained model and the example data we provide to predict the segmentation labels for an image.
## Dataset
We use 3 public datasets: [OASIS](https://github.com/adalca/medical-datasets/blob/master/neurite-oasis.md), [BCV](https://cloud.imi.uni-luebeck.de/s/nAHdcPDPbBsNrgX/download) and a subset of [VerSe](https://github.com/anjany/verse) in our paper. 

We provide some [example](https://github.com/NoviceFodder/OS-MedSeg/tree/main/data) pre-processed images and their corresponding labels in this repository.
## Pre-trained models
We provide our pre-trained models on OASIS, BCV, and VerSe datasets, which you can use to evaluate medical image segmentation.

You can download the OASIS pre-trained model here: [Download our pre-trained model on OASIS](https://drive.google.com/file/d/1zEt8aLy22FMb2lGZnYRT4u2B2cEIeeX4/view?usp=drive_link)

You can download the BCV pre-trained model here: [Download our pre-trained model on BCV](https://drive.google.com/file/d/1CjGejST1QTAJ715qtly_IHX_bXzoIPtR/view?usp=drive_link)

You can download the VerSe pre-trained model here: [Download our pre-trained model on VerSe](https://drive.google.com/file/d/1sHApcMk8ZMmIhI-S_Jk32YEf7nyKcZyx/view?usp=drive_link)
## Segmentation Results
### Visualization of Segmentation
<img src="https://github.com/NoviceFodder/OS-MedSeg/blob/main/figuers/res_main.png" alt="Segmentation Results" />

### Boxplots for BCV
<img src="https://github.com/NoviceFodder/OS-MedSeg/blob/main/figuers/bcv_boxplots.png" alt="BCV Boxplots"  width="50%" height="50%"/>

### Boxplots for OASIS
<img src="https://github.com/NoviceFodder/OS-MedSeg/blob/main/figuers/OASIS_boxplots.png" alt="OASIS Boxplots" />

You can find more details in our paper.

# Reference
Some codes are referenced from [VoxelMorph](https://github.com/voxelmorph/voxelmorph) and [CLMorph](https://github.com/lihaoliu-cambridge/unsupervised-medical-image-segmentation). Thanks a lot for their great contribution.
