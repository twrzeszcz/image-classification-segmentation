# General Info
This is a simple image classification and segmentation project. The dataset comes from https://www.kaggle.com/crowww/a-large-scale-fish-dataset and contains images of 9 different types of fish. For each type there are also binary masks provided. In both tasks we use only the subset of images which are loaded and stored as a protobufs in multiple TFRecord files. The approach was adapted from *Hands-On Machine Learning* book. For the classification problem a pretrained model is used and for the segmentation task we build a UNet model from scratch as well as using a pretrained part of the other model. All 3 models are uploaded and can be used. Preprocessing and training for classification is done in the 
**image_classification** notebook and for segmentation in the **image_segmentation** notebook.


@inproceedings{ulucan2020large,\
title={A Large-Scale Dataset for Fish Segmentation and Classification},\
author={Ulucan, Oguzhan and Karakaya, Diclehan and Turkan, Mehmet},\
booktitle={2020 Innovations in Intelligent Systems and Applications Conference (ASYU)},\
pages={1--5},\
year={2020},\
organization={IEEE}\
}
