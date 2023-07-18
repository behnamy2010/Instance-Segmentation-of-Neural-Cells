# -Instance-Segmentation-of-Neural-Cells
Instance Segmentation of Neural Cells using Mask RCNN
**Objective:**
The objective of this project is to familiarize ourselves with the process of training the Mask RCNN model for instance segmentation of neural cells. We will utilize the Sartorius - Cell Instance Segmentation dataset, which is part of a Kaggle competition aimed at segmenting neural cells present in microscopic images.

**Dataset:**
The Sartorius - Cell Instance Segmentation dataset can be obtained by registering on Kaggle through the following link:
- Kaggle Competition Data: https://www.kaggle.com/competitions/sartorius-cell-instance-segmentation/data

**Project Description:**
1. **Mask RCNN Training with CSPResNet50 Backbone:**
   - Train the Mask RCNN algorithm with a new CSPResNet50 backbone on the provided dataset.
   - Present the results obtained from the trained model along with a selection of segmented images.
   - For implementation guidance, the ready-to-use code available in the Kaggle competition's Code section can be referenced: https://www.kaggle.com/code/abrachan/sartorius-maskrcnn-with-pytorch
   - An alternative implementation of the corrected Mask RCNN can be found here: https://github.com/robintzeng/mask-rcnn-Pytorch/blob/main/model/modified_mask_rcnn.py

**Note:**
The Mask RCNN model, augmented with the CSPResNet50 backbone, will be used for instance segmentation of neural cells in the provided microscopic images. The final report will include the model's performance evaluation, along with segmented images as visual examples. This project will serve as a valuable resource for understanding the Mask RCNN approach in instance segmentation tasks, particularly in the context of neural cell analysis.
