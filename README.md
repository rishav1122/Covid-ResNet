[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/covid-resnet-a-deep-learning-framework-for/multi-class-classification-on-covid-chest-x)](https://paperswithcode.com/sota/multi-class-classification-on-covid-chest-x?p=covid-resnet-a-deep-learning-framework-for)
# GNR638 Project Report
![Introduction](https://github.com/rishav1122/Covid-ResNet/blob/main/Images/MAin%20SLIDE.png)
## 1.Dataset preparation

The dataset we are using is [COVIDx dataset](https://github.com/lindawangg/COVID-Net). You need to follow [this tutorial]( to
collect and prepare the dataset.

## 2.Preprocessing

```
a. Store the dataset in Project/Covid-19-Master/data
```
## 3.How to run the code?

a. First, run preprocessing.ipynb to convert the image dataset to NumPy arrays. (Or you can directly download the .npy

 files from our work)(https://drive.google.com/drive/folders/1XzyIOyF9oQdwZv57dRyLYj0Ac7GUiUdS?usp=sharing)

 Colab file[ Preprocessing _colab](https://colab.research.google.com/drive/1Tm_YNokLyevCa-CfTNjd-XbOQiaSoDNb?usp=sharing)


b. Now either (if you have sufficient RAM) directly run GNR-Project.ipynb
Colab file [ GNR_projectcolab ](https://colab.research.google.com/drive/1j2l81YE2DnvQz-XFMGHRt3hP0lgmNEKk?usp=sharing)

c. If you don’t have enough RAM, run
i. CRL.ipynb

ii. Stage1.ipynb
Colab file [ STAGE1_colab ](https://colab.research.google.com/drive/1lYrM2tdQSoYO08o_UwXYdFqQTsKkr7On?usp=sharing)

iii. Stage2.ipynb
Colab file [ STAGE2_colab ](https://colab.research.google.com/drive/10oAFcUpG2Pcfv3VB1uipnIlYpZoi3L7D?usp=sharing)

iv. Stage3.ipynb
Colab file [ STAGE3_colab ](https://colab.research.google.com/drive/1ghkwhIrxp7uBE9w2oArOLp2JC7m4lBwT?usp=sharing)

You can Download the Intermediate stage Weights from here for testing
( https://drive.google.com/drive/folders/1qy0fHMkXx0Ci6GnkVcSEznQQBj4Mz37E?usp=shar
ing )
## Results
![](https://github.com/rishav1122/Covid-ResNet/blob/main/Images/Results.png)
