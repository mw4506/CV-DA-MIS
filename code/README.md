## Domain Adapation for 3D Medical Image Segmentation 

## Requirements
Some important required packages include:
* Pytorch
* TensorBoardX
* Python == 3.6 
* Efficientnet-Pytorch `pip install efficientnet_pytorch`
* Some basic python packages such as Numpy, Scikit-image, SimpleITK, Scipy ......


## Usage

1. Clone the repo:
```
git clone https://github.com/ziyangwang007/CV-SSL-MIS.git 
cd CV-SSL-MIS
```

2. Dataset
Download the pre-processed data and put the data in `../data/`.

Dataset BRATS19 and dataset Brain Tumour Lesion Segmentation from [Baidu Netdisk Link](https://pan.baidu.com/s/1zqheBizWCbA6NCmaIwzUbg) with passcode: 'sucn', or [Google Drive Link]- TBC.

3. Train the model

```
cd code
python train_interpolation_consistency_training_3D_Lesion.py
```

4.  Test the model
```
python test_3D_fully.py

```

## Contributor
Steven Wu, Ziyang Wang, Chen Yang

## Reference