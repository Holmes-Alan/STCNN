# STCNN
Efficient Video Super-Resolution via Hierarchical Temporal Residual Networks

By Zhi-Song Liu, Wan-Chi Siu and Yui-am Chan

The paper can be found in [IEEE](https://ieeexplore.ieee.org/abstract/document/8792098)

# BibTex
       @ARTICLE{8792098,  
              author={Z. {Liu} and W. {Siu} and Y. {Chan}},  
              journal={IEEE Access},   
              title={Efficient Video Super-Resolution via Hierarchical Temporal Residual Networks},   
              year={2021},  
              volume={7},  
              number={},  
              pages={129112-129126},
       }
        
# Key points:

• We propose a Space-Time Convolutional Neural Network, in which we have improved the residual block by adding an adaptive weighting convolution process and global & local connections to learn deep feature representation for video SR.

• The convolution in ST-CNN is done by our proposed Spatial Convolution Packing (SCP) scheme. We can then use fewer parameters and less computation to combine the channel information with the spatial domain for joint training. 

• To boost up the visual quality, we also combine the frame overlapping and patch overlapping processes to form ST-CNN as the proposed ST-CNN+ to further enhance the SR quality in terms of PSNR.

# Dependencies
    Python > 3.0
    OpenCV library
    CAFE
    NVIDIA GPU + CUDA
    MATLAB 6.0 or above

# Complete Architecture
The complete architecture is shown as follows,

![structure](/figures/fig3.png)


# Implementation
You can download the pre-trained models from:
https://connectpolyu-my.sharepoint.com/:f:/g/personal/16903300r_connect_polyu_hk/EvwpX5r_nEFJvRju_UqlnJ8BrU45WT2AMKBbmN7PIBkt9g?e=lHsaqG


For RefSR-VAE, 
run RefSR_VAE.ipynb

For SISR-VAE,
run VAE-SR.ipynv

# Visual Comparison

## compare with state-of-the-art
This figure shows the comparison among different face SR algorithms on RefSR dataset
![figure1](/figures/compare_1.PNG)

## compare with state-of-the-art
This figure shows the facial identity transfer on RefSR dataset
![figure2](/figures/compare_2.PNG)

Please cite our paper for using our dataset or models.
