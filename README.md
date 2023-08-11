# AuSRResults
This repository contains the output of the AuSR algorithms with USC-SIPI, Kodak-PCD0992, and UCID-1338 datasets.  

### Datasets Information
The datasets can be accessed at [ColorImageDatasets](https://github.com/girfa/ColorImageDatasets)  
The USC-SIPI dataset contains 8 color images with sizes of 512x512 pixels.  
The Kodak-PCD0992 dataset contains 24 color images with sizes of 512x768 pixels.  
The UCID-1338 dataset contains 1.338 color images with sizes of 512x384 pixels.  
The results are then combined into two CSV files: [watermarked-v3.csv](https://github.com/girfa/AuSRResults/blob/main/watermarked-v3.csv) and [recovered-v3.csv](https://github.com/girfa/AuSRResults/blob/main/recovered-v3.csv)  

### Statistical Analysis
The statistical analysis consists of two processes:
1. Parametric analysis (parametric or non-parametric).
2. Statistical analysis of the PSNR and SSIM grouped by the AuSR algorithms.

The statistical analysis of the watermarked images can be accessed at [watermarked-v3.ipynb](https://github.com/girfa/AuSRResults/blob/main/watermarked-v3.ipynb)  
The statistical analysis of the recovered images can be accessed at [recovered-v3.ipynb](https://github.com/girfa/AuSRResults/blob/main/recovered-v3.ipynb)  

### AuSR1
>Aminuddin, Afrig and Ernawan, Ferda "AuSR1: Authentication and self-recovery using a new image inpainting technique with LSB shifting in fragile image watermarking." _Journal of King Saud University-Computer and Information Sciences_ 34, no. 8 (2022): 5822-5840. [https://doi.org/10.1016/j.jksuci.2022.02.009](https://doi.org/10.1016/j.jksuci.2022.02.009).

### AuSR2
>Aminuddin, Afrig and Ernawan, Ferda "AuSR2: Image watermarking technique for authentication and self-recovery with image texture preservation." _Computers and Electrical Engineering_ 102 (2022): 108207. [https://doi.org/10.1016/j.compeleceng.2022.108207](https://doi.org/10.1016/j.compeleceng.2022.108207).