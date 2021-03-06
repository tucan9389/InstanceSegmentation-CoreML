# InstanceSegmentation-CoreML

## What is instance segmentation?

![image](https://user-images.githubusercontent.com/37643248/109685911-153c9e00-7bc5-11eb-999a-7f3ff5436743.png)
source: https://images.app.goo.gl/tqCZU7uG7WfWwAt19

## Features

- [ ] Inference the model and perform post-process yolact model
- [ ] Import a photo from device's photo library, inference, and draw the result on the screen
- [ ] Capture every frame from device's camera, inference, and draw the result on the screen
- [ ] Make it real-time when capture from camera 

## Requirements

## Getting Started

## Models

DEMO reference: https://github.com/Ma-Dan/Yolact-CoreML

#### Model size, minimum iOS version, input/output shape

| Model          | Size (MB) | Minimum iOS Version | Input Shape        | Output Shape      | Source Link                                     |
| -------------- | --------- | ------------------- | ------------------ | ----------------- | ----------------------------------------------- |
| yolact.mlmodel | 146.9     | iOS11.2             | `[1, 550, 550, 3]` | `4` MLMultiArrays | [link](https://github.com/Ma-Dan/Yolact-CoreML) |

#### Inference time (ms)

#### Total time (ms)

#### FPS

## How it works

## Project Structure

```
InstanceSegmentation-CoreML
├── InstanceSegmentation-CoreML
|   ├── AppDelegate.swift
|   ├── Assets.xcassets
|   ├── Base.lproj
|   ├── Info.plist
|   ├── mlmodels
|   |   └── yalact.mlmodel				# you need to download from release of this repository
|   └── ViewController.swift
├── InstanceSegmentation-CoreML.xcodeproj
├── README.md
└── LICENSE
```

## Models & Papers

- [Real-Time Instance Segmentation](https://paperswithcode.com/task/real-time-instance-segmentation)
- [Instance Segmentation](https://paperswithcode.com/task/instance-segmentation)

## References

- https://github.com/edouardlp/Mask-RCNN-CoreML
- https://github.com/Ma-Dan/Yolact-CoreML
