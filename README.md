# Person Activity Detection
Streamlit app: 

<img src="https://github.com/jayprachaya/ActivityDetect/blob/868ec3d89d6b4f0f3ca4a2487b33d11f702caa96/img/output7.gif" style="max-width: 20%;" align="center" />

# Dataset
- Image size: `640x480 pixels`
- Class: `Sit, Sleep and Stand`
- Data volumn (image)
  | Image class  | Train   | Validation |
  | ------------ | ------- | ---------- |
  | Sit          | 68      | 13         |
  | Sleep        | 73      | 14         |
  | Stand        | 64      | 13         |
  | Multi-calss  | 10      | 2          | 

- Annotation Tools: LabelImg (YOLO format)
  https://github.com/tzutalin/labelImg

# Model
- Model Training: Use pretrained model `YOLOv5s`
  https://github.com/ultralytics/yolov5
- Train on Colab

# Result
<img src="https://github.com/jayprachaya/ActivityDetect/blob/f9a542c5d391a71dd5e6ec8c1ff5b351196e4590/img/results.png" style="max-width: 20%;" align="center" />
