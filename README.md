# MISSFish
The <b>M</b>arine <b>I</b>nstitute and <b>S</b>martBay under<b>S</b>ea  <b>Fish</b> dataset

---

## Dataset:
Due to the limited space on Github, the subset annotated videos (45 videos, ~3G) are hosted on Google Drive [link] (https://drive.google.com/file/d/1SnWTu-3tgarfKXuq4vHjcjJZvHDUfi78/view?usp=sharing).
 
Annotations are in [](data/annotations), currently the annotation is in MaskRCNN format. 

Full video set (over 330k, historical and live videos) can be accessed at: [](https://smartbay.marine.ie/) 

---
## Model

The Mask RCNN used in this work is based on matterport repo [link](https://github.com/matterport/Mask_RCNN)

--- 
## Trained Model
Our trained model can be downloaded at [](model/niap_maskrcnn/)
Once we have trained a new model, it will be added to the model folder. 

---
## Docker 
To simplfy the setup, we used [tensorflow/tensorflow:1.15.0rc2-gpu-py3-jupyter](https://hub.docker.com/layers/tensorflow/tensorflow/1.15.0rc2-gpu-py3-jupyter/images/sha256-95d97c5c888e053af622964a150c205a39360064a962d7d5767038ad83b2d9b3?context=explore) docker conainer.

---
## Tools
Some tools, e.g. extract frames from video, are available.

---
## Sample
A sample of how to training a MaskRCNN model is avalalbe in the Sample folder

---
## Funding
This research work is funded by the National Infrastructure Access Programme, which is funded by the Marine Institute under the Marine Research Programme with the support of the Irish Government. This publication has emanated from research supported in part by a research grant from Science Foundation Ireland (SFI) under Grant Number SFI/12/RC/2289\_P2.

---
## Citation
If you use this dataset in your research, please cite this project.
```
@article{missfish,
  title   = {Please holder},
  author  = {please holder},
  journal= {please holder},
  year={please holder}
}
```

