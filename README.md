# Image Denoising using Convolutional Neural Networks
This repository is the final project for COMP 576: Introduction to Deep Learning, Rice University. Our topic is image denoising using Convolutional Neural Networks. The repository includes: proposal, poster, final report and codes.

## Instructor
Dr. Ankit Patel, abp4@rice.edu

## Collaborators

- Iris Wu, yw110@rice.edu
- Danyu Wang, dw65@rice.edu
- Kunhua Lei, kl61@rice.edu
- Dongwei Li, dl82@rice.edu

## Abstract
Image noise can be generated by different types of inevitable factors, like circuitry and sensor of digital camera, or the environment. One of the most challenging parts in processing images is image denoising, and it is essential for applications, for example, improving image qualities and restoration. While there are already lots of proposed solutions to denoising, people are still trying to improve it, especially with high noise level images. 

In this paper, we attempted to build a CNN-based model that perform well in image denoising. This model utilizes convolutional block channel attention and encoder-decoder network with skip connection. We compared our new method with Residual Encoder-Decoder Networks (REDNet) and Pyramid Real Image Denoising Network (PRIDNet) based on Smartphone Image Denoising Dataset (SIDD) training dataset. The new method showed promising improvements in two metrics, Peak Signal to Noise Ratio (PSNR) and Structural Similarity Index Measure (SSIM). In addition, we tested our trained model on single images and Iphone photos to visualize its denoising effect.

## References
1. York University, Smartphone Image Denoising Dataset, https://www.eecs.yorku.ca/~kamel/sidd/.
2. Abdelrahman Abdelhamed, Lin S., Brown M. S. "A High-Quality Denoising Dataset for Smartphone Cameras", IEEE Computer Vision and Pattern Recognition (CVPR), June 2018.
3. Abdelrahman Abdelhamed, Timofte R., Brown M. S., et al. "NTIRE 2019 Challenge on Real Image Denoising: Methods and Results", IEEE Computer Vision and Pattern Recognition Workshops (CVPRW), June 2019.
4. Xiao-Jiao Mao, Chunhua Shen, Yu-Bin Yang. "Image Restoration Using Convolutional Auto-Encoders with Symmetric Skip Connections". 30 Aug. 2016, doi:10.48550/arXiv.1606.08921. 
5. Yiyun Zhao, Zhuqing Jiang, Aidong Men, Guodong Ju. "Pyramid Real Image Denoising Network". 2019 IEEE Visual Communications and Image Processing (VCIP), 2019, pp. 1-4, doi: 10.1109/VCIP47243.2019.8965754.
