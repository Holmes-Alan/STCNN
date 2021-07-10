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

![structure](/figure/network.png)

Proposed Spatial Convolution Packing (SCP) scheme.

![scp](/figure/scp.PNG)


# Implementation
You can download the pre-trained models from:
https://drive.google.com/file/d/1N_3AYEhKCgItjdyvijzCLXLPrTVzqh2X/view?usp=sharing


For STCNN

run ST-CNN_test.ipynv

# Quantitative and qualitative Comparison

## compare with state-of-the-art
This table shows the comparison among different video SR algorithms.
![figure1](/figure/table.PNG)

## compare with state-of-the-art
This figure shows the running time comparison.
![figure2](/figure/time.PNG)

## compare with state-of-the-art
This figure shows the visual comparison.
![figure3](/figure/compare.PNG)

Please cite our paper for using our dataset or models.
