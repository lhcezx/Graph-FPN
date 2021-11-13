# GraphFPN: Graph Feature Pyramid Network for Object Detection

https://arxiv.org/abs/2108.00580

## Abstract

Feature pyramids have been proven powerful in image understanding tasks that require multi-scale features. State-of-the-art methods for multi-scale feature learning focus on performing feature interactions across space and scales using neural networks with a fixed topology. In this paper, we propose graph feature pyramid networks that are capable of adapting their topological structures to varying intrinsic image structures and supporting simultaneous feature interactions across all scales. We first define an image-specific superpixel hierarchy for each input image to represent its intrinsic image structures. The graph feature pyramid network inherits its structure from this superpixel hierarchy. Contextual and hierarchical layers are designed to achieve feature interactions within the same scale and across different scales. To make these layers more powerful, we introduce two types of local channel attention for graph neural networks by generalizing global channel attention for convolutional neural networks. The proposed graph feature pyramid network can enhance the multiscale features from a convolutional feature pyramid network. We evaluate our graph feature pyramid network in the object detection task by integrating it into the Faster R-CNN algorithm. The modified algorithm outperforms not only previous state-of-the-art feature pyramid-based methods with a clear margin but also other popular detection methods on both MS-COCO 2017 validation and test datasets.

## Folder structure

```
${ROOT}
└── checkpoint/
└── COCO/    
│   └── coco/
│   │    ├── .config 
│   │    ├── 2017/
│   │
│   ├── downloads/
│
│
└── data_demo/
    ├── data
    |    ├── coco
    |    ├── checkpoint
    ├── data.zip
     
├── README.md 
└── requirements.txt
```
