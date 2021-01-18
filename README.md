# MMES
Manifold Modeling in Embedded Space (MMES): An Interpretable Alternative to Deep Image Prior <br>
It is published in IEEE Transactions on Neural Networks and Learning Systems <br>
Please download our paper from IEEE (Open Access) : https://ieeexplore.ieee.org/abstract/document/9281370 <br>
Link to arXiv paper : https://arxiv.org/abs/1908.02995

It is implemented by using TensorFlow (please try our codes for image inpainting, super-resolution, deconvolution, and denoising)

 - [demo_MMES_IP(inpainting)](demo_MMES_IP(inpainting).ipynb) recovers the following incomplete image with missing entries (70% pixels are missing) <br>
 ![missing](input_IP_house_70_missing.png)
 
 - [demo_MMES_SR(super-resolution)](demo_MMES_SR(superresolution).ipynb) recovers the following low resolution image (128 x 128) to (512 x 512) <br>
 ![lowres](input_SR_sailboat_low_res_128.png)
 
 - [demo_MMES_DC(deconvolution)](demo_MMES_DC(deconvolution).ipynb) recovers the following blurred image with Gaussian kernel <br>
 ![blurred](input_DC_leaves_blur15.png)
 
 - [demo_MMES_DN(denoising)](demo_MMES_DN(denoising).ipynb) recovers the following noisy image <br>
 ![noisy](input_DN_butterfly_sig40.png)
 
 - Additional Inpainting Demo. for [gray-scale image](demo_MMES_IP(inpainting)_gray.ipynb) and [binary image](demo_MMES_IP(inpainting)_binary.ipynb) were uploaded <br>
 ![gray](Lena_ms70.png) 
 ![binary](Lena_ms70_binary(1or255).png)
