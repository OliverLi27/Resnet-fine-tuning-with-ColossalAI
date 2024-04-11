# Resnet_fine_tuning_with_ColossalAI
## Introduction
Use ColossalAI to fine-tune the Resnet18 with CIFAR10 dataset. All the experiments and logs are in the Colab file Resnet_fine_tuning_with_ColossalAI.ipynb.

Due to Using Colab, Change the GPU number as 1.

## Github Link

https://github.com/OliverLi27/Resnet-fine-tuning-with-ColossalAI

## Model

Resnet18

## Dataset

CIFAR10

## Guidance

All the experiments and logs are in the Colab file Resnet_fine_tuning_with_ColossalAI.ipynb. Details as below.

- Connect to the Google Drive(For using Colab)
- Clone the code from the github repository, https://github.com/hpcaitech/ColossalAI.git
- CD to root path
- Install the library following the requirements
- Train the 3 models with torch
  - Train DDP with fp32 model
  - Train DDP with fp16 model
  - Train with low level zero model
- Evaluate the 3 models
  - Evaluate the DDP with FP32
  - Evaluate the DDP with FP16
  - Evaluate the Low Level Zero
  
## Result

| Model     | Booster DDP with FP32 | Booster DDP with FP16 | Booster Low Level Zero |
| --------- |-----------------------|-----------------------|------------------------|
| ResNet-18 | 85.11 %               | 84.66 %               | 84.66 %                |




