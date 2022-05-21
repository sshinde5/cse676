## CSE 676 Project: Brain Tumor Segmentation using Transformer

This is the code for CSE 676 Deep Learning course. <br> <br>
Authors: <br>
<br>
Siddhesh Udesh Shinde <br>
sshinde5@buffalo.edu <br>
UBID 50424897 <br>
<br>
Mahesh Gudisa <br>
maheshgu@buffalo.edu <br>
UBID 50416878


### Installation
First, clone the repository locally:
```
git clone git@github.com:sshinde5/cse676.git
```
Then, install Segmentation_Models_3D package :
```
pip install segmentation-models-3D
```


### Preparation

Download and extract BraTS2020 dataset from [Penn Imaging](https://ipp.cbica.upenn.edu/).
Run the data preprocessing steps from main.ipynb file.
Directory structure should be following:
```
root_dir
 ├── data
 │   ├── train
 │   │   ├── images
 │   │   ├── masks
 │   ├── val
 │   │   ├── images
 │   │   ├── masks
 │   ├── test
 │   │   ├── images
 │   │   ├── masks
...
```



### Training

Build and train the model from model from scratch as per main.ipynb file or download the trained models [Google Drive](https://drive.google.com/drive/folders/141rN2-R1gAOfyntgU5lP1qFVgaHBRWKY?usp=sharing). 


### Acknowledgement

BraTS2020 Dataset: [Penn Imaging](https://ipp.cbica.upenn.edu/) <br>
Helper code: [bnsreenu](https://github.com/bnsreenu/python_for_microscopists/tree/master/231_234_BraTa2020_Unet_segmentation) and [yingkaisha](https://github.com/yingkaisha/keras-unet-collection/blob/main/examples/user_guide_models.ipynb)

