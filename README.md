# Customized_trt_pose_dataset
## Introduction
We found that when the trt_pose model was dealing with videos of people who fell, some frames of the falling person at certain angles would be unrecognizable. This is because most of the original dataset are walking people and dancing dancers.
## Method
Added random data augmentation from -180 degrees to 180 degrees.
Customized trt_pose training dataset (data loader, data augmentation).
## Environment
- Pytorch
- Python
- Please follow the README file of the referenced website below
## Reference
1. https://github.com/NVIDIA-AI-IOT/trt_pose

