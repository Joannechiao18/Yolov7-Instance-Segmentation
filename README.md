# Yolov7-Instance-Segmentation

![](https://img.shields.io/badge/python-3.8-orange)

This is a instance segmentation project from scratch using the pretrained official Yolov7 model. 

### Dependencies
## Usage: pip install -r requirements.txt

# Base ----------------------------------------
matplotlib>=3.2.2
numpy>=1.18.5
opencv-python>=4.1.1
Pillow>=7.1.2
PyYAML>=5.3.1
requests>=2.23.0
scipy>=1.4.1
tqdm>=4.41.0
protobuf<4.21.3

# Logging -------------------------------------
tensorboard>=2.4.1
# wandb

# Plotting ------------------------------------
pandas>=1.1.4
seaborn>=0.11.0

# Export --------------------------------------
# coremltools>=4.1  # CoreML export
# onnx>=1.9.0  # ONNX export
# onnx-simplifier>=0.3.6  # ONNX simplifier
# scikit-learn==0.19.2  # CoreML quantization
# tensorflow>=2.4.1  # TFLite export
# tensorflowjs>=3.9.0  # TF.js export
# openvino-dev  # OpenVINO export

# Extras --------------------------------------
ipython  # interactive notebook
psutil  # system utilization
thop  # FLOPs computation
# albumentations>=1.0.3
# pycocotools>=2.0  # COCO mAP
# roboflow


# New Features
1. Application: Images, Videos, Webcams.
2. Customized bounding boxes/thinkness/class color/labels/fps settings.

# Results

1. Images
<img src="https://user-images.githubusercontent.com/84509949/196133709-713959c1-59ab-4962-bb95-6ced57df031d.jpg" width="425"/> <img src="image2.png" width="425"/> 

2. Videos

3. Webcams

# Citation

```
@article{wang2022yolov7,
  title={{YOLOv7}: Trainable bag-of-freebies sets new state-of-the-art for real-time object detectors},
  author={Wang, Chien-Yao and Bochkovskiy, Alexey and Liao, Hong-Yuan Mark},
  journal={arXiv preprint arXiv:2207.02696},
  year={2022}
}

```

# Acknowledgements

<details><summary> <b>Expand</b> </summary>
https://github.com/WongKinYiu/yolov7
</details>
