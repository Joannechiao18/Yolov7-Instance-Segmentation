# Yolov7-Instance-Segmentation

![](https://img.shields.io/badge/python-3.8-orange)

## 🏚️ Introductuion

This is a instance segmentation project from scratch using the pretrained official Yolov7 model. The project support performing stance segmentation for the following applications: ***Images***, ***Videos***, ***Webcams***. In addition, some of the attributes of the bounding boxes are customizable, including ***thinkness***, ***class color***,***labels***,***fps settings***. 

## 🌟 Visual Results

<p align="center">
  <a href="#">
    <img src="https://user-images.githubusercontent.com/84509949/202364037-17101803-603b-46a1-849f-7d99133b5e3f.jpg" width="250" height="200" />
  </a>
</p>


https://user-images.githubusercontent.com/84509949/202367123-e8fb4cdc-d123-4f45-ad74-7e28715bc465.mp4


## 🔨 Usage: 
1. Create a conda environment.
2. Download `Detectron2` from [here](https://github.com/facebookresearch/detectron2) and install it to the new environment with `pip install -e` using Anaconda prompt. 
3. Install the required packages with`pip install -r requirements.txt` using Anaconda prompt as well. 
4. `cd` to `yolov7-mask` and run `segment.py` with pretrained weight `yolov7-mask.pt` (you can train your own model by running `train.py`). 
5. `cd` to `runs` directory and see your results.

## 🔗 Citation

```
@article{wang2022yolov7,
  title={{YOLOv7}: Trainable bag-of-freebies sets new state-of-the-art for real-time object detectors},
  author={Wang, Chien-Yao and Bochkovskiy, Alexey and Liao, Hong-Yuan Mark},
  journal={arXiv preprint arXiv:2207.02696},
  year={2022}
}

```

## Acknowledgements

<details><summary> <b>Expand</b> </summary>
https://github.com/WongKinYiu/yolov7
</details>
