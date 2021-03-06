# deep image prior - tensorflow
A simple yet working implementation of Deep Image Prior paper [https://arxiv.org/pdf/1711.10925.pdf](https://arxiv.org/pdf/1711.10925.pdf) using tensorflow. Free to use/reuse, give me a **star** if you feel it is helpful to you. 

Currently, the denoising and inpainting use cases are implemented.

#Denoising 
remove the image compression artifact.

<img src="out-denoise/noisy-in.png" alt="Drawing" style="width: 300px;"/> <img src="out-denoise/denoised-it7500.png" alt="Drawing" style="width: 300px;"/>

Results after every 1000 iterations, [!] the last one is not always the best one:

<img src="out-denoise/denoised-it000.png" alt="Drawing" style="width: 100px;"/>
<img src="out-denoise/denoised-it1000.png" alt="Drawing" style="width: 100px;"/>
<img src="out-denoise/denoised-it2000.png" alt="Drawing" style="width: 100px;"/>
<img src="out-denoise/denoised-it3000.png" alt="Drawing" style="width: 100px;"/>
<img src="out-denoise/denoised-it4000.png" alt="Drawing" style="width: 100px;"/>
<img src="out-denoise/denoised-it5000.png" alt="Drawing" style="width: 100px;"/>
<img src="out-denoise/denoised-it6000.png" alt="Drawing" style="width: 100px;"/>
<img src="out-denoise/denoised-it6500.png" alt="Drawing" style="width: 100px;"/>

# Inpainting
Remove text on image with mask infomation provided. [!] the last one is not always the best one:

<img src="out-inpaint/corrupt-in.png" alt="Drawing" style="width: 300px;"/> <img src="out-inpaint/output-it3000.png" alt="Drawing" style="width: 300px;"/>
