# Customized_trt_pose_dataset
## Introduction
We found that when the trt_pose model was dealing with videos of people who fell, some frames of the falling person at certain angles would be unrecognizable. This is because:
1. Most of the original dataset are walking people and dancing dancers.
2. Although the original model has done affine transformation (data augmentation), the augmented angle is too small.
 
## Method
Augmented training dataset in specific eight directions.

## Environment
- Pytorch
- Python
- Please follow the README file of the referenced website below

## Usage



## Reference
1. https://github.com/NVIDIA-AI-IOT/trt_pose

