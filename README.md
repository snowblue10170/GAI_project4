# GAI_project4  
## Training DDPM on Butterfly Dataset  
This project explores optimizing the training process of a Denoising Diffusion Probabilistic Model (DDPM) using a Deep Image Prior (DIP) model.  
By running the Jupyter notebook directly, the results can be reproduced.  

The model transforms randomly generated noisy images into butterfly images.  

## Result after Optimization with DIP  
![image](images/DIP_image/0049.png)  

## Result from Original DDPM  
![image](images/standalone/0049.png)  

As shown, the DIP optimization significantly improves image quality under the same number of epochs.
