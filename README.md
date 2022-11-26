# Visualization-Platform-for-COVID-19-Focus-Segmentation
## Comprehensive Training of Intelligent Platform Design and Application work
This platform is mainly divided into four modules:</br>
1.*File Upload Module*</br>
This module is convenient for users to import nii files locally for subsequent visualization and data import of models.</br>
2.*Data Visualization Module*</br>
This module is designed to facilitate users to view the imported specific images and the results of model segmentation, and needs to have the function of adjusting the window level and window width that general medical image software has.</br>
3.*Model Inference Module*</br>
This module consists of two parts, one is to import the trained model, the other is to infer the data.</br>
4.*Inference Result Export Module*</br>
The module should be able to convert the reasoning results into files in the nii format and output them to local folders.</br>
</br>
Based on the performance difference between UNet and BiSeNetV2, two reasoning modes are designed for the platform: the classic mode and the fast mode, respectively to meet the needs of GPU in the environment and users for real-time.</br>
You can retrain models in 'src/train.ipynb'</br>
**UNet**
![UNet](Poster/UNet.JPG)
**BiSeNetV2**
![BiSeNetV2](Poster/BiSeNetV2.JPG)
The platform UI is developed using PyQt5. After being packaged into an exe file, it can run directly on the user's Windows computer without installing other dependent libraries.</br>
**MainUI**</br>
![MainUI](Poster/MainUI.png)
