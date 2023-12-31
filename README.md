# Agricultural Weed Identification Using Optimized Deep Learning Architecture

The work presented in this research uses state-of-the-art [YOLOv7 tiny](https://github.com/WongKinYiu/yolov7) architecture and integrates two optimization techniques within the backbone and neck components. These two optimization techniques are: (a) module re-parameterized convolutional layer (RCL), and (b) filter-based structured pruning (model compression). Both of these techniques have been adopted from [here](https://arxiv.org/abs/2307.11904) and [here](https://arxiv.org/abs/2207.02696). For more details read the paper [here]() and browse through the repository to download the trained models along with the architecture. The developed architecture uses 78% less parameters compared to the YOLOv7-Base model.

## Novel aspects of this research study are:
1. Integration of RepConv (Re-parameterized Convolutional Module in the neck compoenent)
2. Filter-based structured pruning approach
3. Conversion to FP16 (floating points) to edge deployment

## Highlights of this research swork includes:
1. [Open-source dataset](https://data.mendeley.com/datasets/8kjcztbjz2/2): 3,929 images and 12k bounding-box annotations used in this study.
2. Deep learning model optimization using pruning and integrating re-parameterization module.
3. Assessing the effects of training multiple image resolution on the optimized YOLO-Spot model.
4. YOLO-Spot_M model achieves accuracy (+1.3%) and mAP (+2.7%) compared to YOLO-base model.
5. YOLO-Spot_M with half-precision gains 5X times inferencing speed on an edge device.

## Hardware used to perform training and inference tasks:
![Hardware used](https://raw.githubusercontent.com/nitin-dominic/Agricultural_Weed_Identification_Using_Optimized_Deep_Learning/main/Appendix.png)


