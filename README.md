# Mask-Detection
Mask Detection System implemented using ResNet and OpenCV. Used Python as the programming language along with PyTorch as the deep learning framework.

I have written an article on Medium explaining the project - https://medium.com/jovianml/mask-detection-using-resnet-and-opencv-67a501c420e0

![Wearing a Mask](https://github.com/Ajtambad/Mask-Detection/assets/33771353/073c0466-9883-4d2e-a055-010be0e33e9a) 

1) The model correctly detects that I am wearing a mask. 

![Not wearing a mask](https://github.com/Ajtambad/Mask-Detection/assets/33771353/d3178dbc-bca7-414a-85d8-15aab32ef993)

2) The model correctly detects that I am not wearing a mask. 

![Improperly wearing a mask](https://github.com/Ajtambad/Mask-Detection/assets/33771353/490c2e62-76da-4ca8-a4f1-a758d5d6a2ba)  

3) Since the training dataset for improper wearing has been clubbed with the dataset for people not wearing a mask, it detects that I am not wearing a mask. Therefore, it is working as intended.

Dataset was obtained from Kaggle - https://www.kaggle.com/vtech6/medical-masks-dataset 

Credits to Mr Dohun Kim's notebook (https://www.kaggle.com/dohunkim/visualizing-medical-mask-dataset) which helped with retrieving faces and labeling them. 
