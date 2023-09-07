# Real Time Pothole Detection

Potholes are symptoms of a poorly maintained road, pointing to an underlying structural issue. A vehicle's impact with a pothole not only makes for an uncomfortable journey, but it can also cause damage to the vehicle's wheels, tyres and suspension system resulting in high repair bills.

![](https://github.com/sudhanshu2198/Real-Time-Pothole-Detection/blob/main/videos/ezgif.com-video-to-gif.gif)

Different model architecture and backnones are utilizes for pothole detection
- FasterRCNN with Resnet: .6802 map @ iou=0.5
- SSD with Vgg : .5642 map @ iou=0.5
- SSDLite with MobileNetv3: .453 @ iou=0.5
- Yolov8m: 0.38 @ iou=0.5

Though FasterRCNN and SSD performs better but they have significantly slower speed then SSDLite model , due to which SSDLite Model with Mobilenetv3 backbone is deployed in the Streamlit as pothole detection model.

## 🔗 Links

 - [App Link](https://jakarta-indonesia-predicting-road-defects-d3xkv5edzmxlasspkvhh.streamlit.app/)
 - [Kaggle Notebook link](https://www.kaggle.com/code/sudhanshu2198/real-time-pothole-detection-using-ssd)


## 🛠 Skills
Pytorch, Torchvision, Ultralytics, OpenCV, Numpy, Streamlit, Git

## Directory Tree
```bash

├── images
│   ├── 0.png
│   │── 1.png
|   |── 2.png
│   └── 3.png 
├── videos
│   ├── pothole_Trim.mp4
├── app.py
├── utils.py
├── pothole-detection-using-faster-rcnn.ipynb
├── real-time-pothole-detection-using-ssd.ipynb
├── README.md
├── pothole_model_lite.pth
├── requirements.txt
└── packages.txt
```

## Run Locally

Clone the project

```bash
  git clone https://github.com/sudhanshu2198/Real-Time-Pothole-Detection
```

Change to project directory

```bash
  cd Real-Time-Pothole-Detection
```
Create Virtaul Environment and install dependencies

```bash
  pip install virtualenv
  venv/Scripts/activate
  pip install -r requirements.txt
```

Run Locally
```bash
  pip install virtualenv
  venv/Scripts/activate
  pip install -r requirements.txt
```

