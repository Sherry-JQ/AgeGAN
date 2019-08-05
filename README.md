# AgeGAN++
Our paper--AgeGAN: Face Aging and Rejuvenation with Dual Conditional GANs

The code is the extension version of AgeGAN, named as AgeGAN++
# Framework
![0](https://github.com/Sherry-JQ/AgeGAN/blob/master/img/framework_main%2B%2B.jpg)
The framework of AgeGAN++. It consists of an encoder, a decoder, a discriminator in pixel level and a representation
disentanglement component. The red arrow represents the first generation process, and the purple arrow shows how we re-change the age
condition.
# Dependencies
	python 3.5
	pytorch 0.4.1
	cython
	scikit-image
	matplotlib
	h5py
	tensorboardX
	pyyaml

# Datasets
UTKFace dataset
https://susanqq.github.io/UTKFace/
# Usage
	python main.py
The detailed config is in "./config/face-aging.yaml"
# Results
![2](https://github.com/Sherry-JQ/AgeGAN/blob/master/img/compare_caae.jpg)
Our qualitative results compared with the previous best unsupervised
GAN-based methods.

![1](https://github.com/Sherry-JQ/AgeGAN/blob/master/img/AgeGAN%2B%2B.jpg)
Experiment results for AgeGAN++. The leftmost column shows that original images are regarded as inputs, and the remaining
part represents the genareted faces of AgeGAN++. The nine columns represent the generated images
belong to nine age groups(0-3, 4-11, 12-17, etc.)
# References
"A Unified Feature Disentangler for Multi-Domain Image Translation and Manipulation" 
Alexander H. Liu, Yen-Cheng Liu, Yu-Ying Yeh, Yu-Chiang Frank Wang, NIPS 2018
 
"Age Progression/Regression by Conditional Adversarial Autoencoder" 
Zhang Zhifei, Song Yang, Qi Hairong, CVPR 2017
