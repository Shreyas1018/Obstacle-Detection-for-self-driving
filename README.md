# Obstacle Detection For Self Driving

## Overview
This project aims to develop an obstacle detection system using deep learning techniques. The system is designed to identify and locate obstacles in real-time from video feeds, making it suitable for applications in autonomous vehicles, robotics, and surveillance.

## Features
- Real-Time Detection: Processes video feeds in real-time to detect obstacles.
- High Accuracy: Utilizes deep learning models RCNN models from tensorflow for high detection accuracy.
- Scalability: Easily adaptable to different environments and is highhly light-weight because of Tensorflow Lite model format.

You can watch the demo video here.

## Installation
Prerequisites
Python 3.8+
CUDA Toolkit (for GPU support)
Anaconda (recommended for managing dependencies)
Steps
Clone the repository:

```
git clone https://github.com/your_username/obstacle-detection.git
cd obstacle-detection
```
Create a virtual environment and activate it:

``` 
conda create -n obstacle-detection python=3.8
conda activate obstacle-detection
```

## About Dataset
The model was trained on a custom dataset consisting of various types of obstacles. Dataset can be obtained [here](https://universe.roboflow.com/visually-impaired-obstacle-detection-uxdze/obstacle-detection-yeuzf).

#### Annotations:
Annotations are provided in multiple formats including TfRecord, yolo etc. For this project, TFRecord Format is used.

## Results
The model achieves the following performance metrics:

Precision: 95%<br>
Recall: 92%<br>
mAP (mean Average Precision): 94%<br>

## Contributing
Contributions are highly welcome to improve this model.

## Cite
@misc{<br>
&ensp; obstacle-detection-yeuzf_dataset,<br>
&ensp; title = { Obstacle detection Dataset },<br>
&ensp; type = { Open Source Dataset },<br>
&ensp; author = { visually impaired obstacle detection },<br>
&ensp; howpublished = { \url{ https://universe.roboflow.com/visually-impaired-obstacle-detection-uxdze/obstacle-detection-yeuzf } },<br>
&ensp; url = { https://universe.roboflow.com/visually-impaired-obstacle-detection-uxdze/obstacle-detection-yeuzf },<br>
&ensp; journal = { Roboflow Universe },<br>
&ensp; publisher = { Roboflow },<br>
&ensp; year = { 2023 },<br>
&ensp; month = { aug },<br>
&ensp; note = { visited on 2024-06-24 },<br>
}

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
