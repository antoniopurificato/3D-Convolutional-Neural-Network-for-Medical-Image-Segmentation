# 3D-Convolutional-Neural-Network-for-Medical-Image-Segmentation
This project was developed for the **Neural Networks** exam, academic year 2021/2022, University La Sapienza of Rome.
 
## Getting Started
The goal of the first task of this project is to modify the classical U-shaped architecture of the  convolutional neural network for MRI (U-Net). In the second task was provided a TensorFlow implementation of my network to work with a breast cancer dataset (BUSI).
 
### First task
The dataset used for this task is [IXI Tiny](https://brain-development.org/ixi-dataset/). The original IXI dataset is a collection of 600 MR brain images from normal, healthy subjects. The architecture consists of a contracting path to capture context and a symmetric expanding path that enables precise localization. <br>
In the upsampling part we have also a large number of feature channels, which allow the network to propagate context information to higher resolution layers.
 
### Second task
The dataset used for this task is [BUSI](https://academictorrents.com/details/d0b7b7ae40610bbeaea385aeb51658f527c86a16). Is possible to see how the network implemented for the first tisk is able to achieve really good results also for the segmentation of breast cancer images.
 
## Installing 
 
In this repository there are 2 Colab Notebooks. All the code can be runned using Google Drive on every browser.<br>
You have simply to paste all the Notebooks in your Drive.<br>

## Results
 
### First task

<p align="center">
 <img src="/src/NN.png" width="500" title="Results of first task" >
<p\>
 
### Second task

<p align="center">
 <img src="/src/NN2".png" width="500" title="Results of second task." >
<p\>


## Author
- *[Antonio Purificato](https://github.com/antoniopurificato)*
 
## References
 
### U-Net: Convolutional Networks for Biomedical Image Segmentation
```
@article{DBLP:journals/corr/RonnebergerFB15,
  author    = {Olaf Ronneberger and
               Philipp Fischer and
               Thomas Brox},
  title     = {U-Net: Convolutional Networks for Biomedical Image Segmentation},
  journal   = {CoRR},
  volume    = {abs/1505.04597},
  year      = {2015},
  url       = {http://arxiv.org/abs/1505.04597},
  eprinttype = {arXiv},
  eprint    = {1505.04597},
  timestamp = {Mon, 13 Aug 2018 16:46:52 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/RonnebergerFB15.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
}
```


### Swin-Unet: Unet-like Pure Transformer for Medical Image Segmentation
```
@ARTICLE{2021arXiv210505537C,
       author = {{Cao}, Hu and {Wang}, Yueyue and {Chen}, Joy and {Jiang}, Dongsheng and {Zhang}, Xiaopeng and {Tian}, Qi and {Wang}, Manning},
        title = "{Swin-Unet: Unet-like Pure Transformer for Medical Image Segmentation}",
      journal = {arXiv e-prints},
     keywords = {Electrical Engineering and Systems Science - Image and Video Processing, Computer Science - Computer Vision and Pattern Recognition},
         year = 2021,
        month = may,
          eid = {arXiv:2105.05537},
        pages = {arXiv:2105.05537},
archivePrefix = {arXiv},
       eprint = {2105.05537},
 primaryClass = {eess.IV},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2021arXiv210505537C},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
}
```


