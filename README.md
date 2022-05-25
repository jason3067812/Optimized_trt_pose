# Optimized_trt_pose
## Introduction
We found that when the trt_pose model was dealing with videos of people who fell, some frames of the falling person at certain angles would be unrecognizable. This is because:
1. Most of the original dataset are walking people and dancing dancers.
2. Although the original model has done affine transformation (data augmentation), the augmented angle is too small.
 
## Method
Add more augmented dataset (rotate the image in specific eight directions) into original training dataset by modifying data loader.

## Environment
- Pytorch
- Python
- Please follow the README file of the referenced website below

## Usage
- Start training: run train_eight_direction.py
- 

## Reference
1. https://github.com/NVIDIA-AI-IOT/trt_pose

