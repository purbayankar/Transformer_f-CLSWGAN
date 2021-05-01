# f-CLSWGAN

# Introduction
   
This work improves the performance of the model proposed in the paper "Feature Generating Networks for Zero-Shot Learning." CVPR (2018) by Yongqin Xian, Tobias Lorenz, Bernt Schiele, Zeynep Akata. To improve the performance of the generator and the discriminator I have used axial attention transformer. It is a simple but powerful technique to attend to multi-dimensional data efficiently.


# Environment

* Python: 3.7,

* PyTorch: 1.2,

* scipy.

## Dataset

The datasets can be downloaded from <a href="https://datasets.d2.mpi-inf.mpg.de/xian/xlsa17.zip">here</a>. The datasets are 2048-d extracted feature maps from resnet-101.

## Acknowledgement

The Axial Attention code is taken from this amazing <a href="https://github.com/lucidrains/axial-attention">repository</a>.

