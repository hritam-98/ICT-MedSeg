[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/an-embarrassingly-simple-consistency/semi-supervised-medical-image-segmentation-on-1)](https://paperswithcode.com/sota/semi-supervised-medical-image-segmentation-on-1?p=an-embarrassingly-simple-consistency)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/an-embarrassingly-simple-consistency/semi-supervised-medical-image-segmentation-on)](https://paperswithcode.com/sota/semi-supervised-medical-image-segmentation-on?p=an-embarrassingly-simple-consistency)
# Simple Consistency Regularization for SSL-based Medical Image Segmentation
This is the official implementation of the paper titled ["An Embarassingly Simple Consistency Regularization Method for Semi-Supervised Medical Image Segmentation"](https://arxiv.org/abs/2202.00677) accepted in [IEEE International Symposium on Biomedical Imaging (ISBI), 2022](https://biomedicalimaging.org/2022/).

<img src="/ICT-MedSeg-Overall.png" style="margin: 8px;">

## Running the code

`git clone https://github.com/hritam-98/ICT-MedSeg`

## Requirements
Some important required packages include:
* [Pytorch][https://pytorch.org/] version >=0.4.1.
* TensorBoardX
* Python == 3.6 
* Efficientnet-Pytorch `pip install efficientnet_pytorch`
* Some basic python packages such as Numpy, Scikit-image, SimpleITK, Scipy ......

## Dataset
Download the processed data and put the data in `../data/MMWHS` or `../data/ACDC`, please read and follow the [ACDC.md](https://github.com/hritam-98/ICT-MedSeg/blob/main/ACDC.md).

## Training

Next, to train the model on ACDC, run the following:

`python main.py `

## Testing

To validate the model performance, run the following:

`python test.py`

# Citation
If you find this repository useful, please cite our work as follows:
```
@misc{basak2022embarrassingly,
      title={An Embarrassingly Simple Consistency Regularization Method for Semi-Supervised Medical Image Segmentation}, 
      author={Hritam Basak and Rajarshi Bhattacharya and Rukhshanda Hussain and Agniv Chatterjee},
      year={2022},
      eprint={2202.00677},
      archivePrefix={arXiv},
      primaryClass={eess.IV}
}
```


