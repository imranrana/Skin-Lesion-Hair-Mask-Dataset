# Skin-Lesion-Hair-Mask-Dataset
This repository contains codes and additional materials used for preparing a skin lesion hair segmentation mask dataset.

## Link to the Prepared Dataset
https://data.mendeley.com/datasets/j5ywpd2p27/1

## Repository Contents
- Inside the **unet** folder the U-net [1] model is defined in **model.py** file, unet training is performed using the unet_training.ipynb python notebook file. The task of predicting initial masks for the dermoscopic images are done using the **predict_mask.ipynb** file.

- The codes used for binarizing mask, making it transparent and creating image collage are available in the **check_annotation.ipynb** file.

- Video demonstration of the hair mask editing process is available in the **mask_editing_process.mp4** file.

## References
1. Ronneberger O, Fischer P, Brox T. U-Net: Convolutional Networks for Biomedical Image Segmentation. In: Navab N, Hornegger J, Wells WM, Frangi AF, editors. Med. Image Comput. Comput. Interv. -- MICCAI 2015, Cham: Springer International Publishing; 2015, p. 234–41. https://doi.org/10.1007/978-3-319-24574-4_28
