# semantic_segmentation_of_ariel_images
Semantic segmentation of ariel images taken from drone

![inference_2](https://user-images.githubusercontent.com/13507973/130315529-368908e9-1c31-4dad-8b13-49a7070f78d5.png)
![inference_1](https://user-images.githubusercontent.com/13507973/130315533-78a66a51-7565-4fe4-a2e1-ef7a864d89f0.png)

* Developed a deep learning based model for segmentation of pixels in images taken from the drone into 12 categories.
* Used Deeplab-v3 architecture along with Resnet-101 as a backbone.
* Used fine-tuning on model pre-trained on Imagenet.
* Used various data augmentation techniques as the number of images in the dataset was small.
* Used focal loss as a loss function to overcome the class imbalance.
* Achieved dice score of 0.796 on the test set.
* Tools used: Pytorch, OpenCV, Albumentations, Matplotlib, Kaggle Kernels

**Kaggle competition link:** https://www.kaggle.com/c/opencv-pytorch-course-segmentation

**run code using:** https://www.kaggle.com/c/opencv-pytorch-course-segmentation/data
