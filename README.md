## INTRODUCTION 

One of the most common challenges in AI domain ML workloads is the need of expensive GPU computes which are typically used for Deep Neural networks. The reason why this is challenging is because of availability of GPU based computes in all regions and this kind of dependencies can lead to delays in productionizing such workloads. Additionally, most edge type devices do not carry GPUs generally. 
This notebook features sophisticated `Computer Vision` techniques that enable getting good enough ML model performance from niche healthcare datasets like in this case we are using a Kaggle competition data to detect `PENUMONIA`. We do a binary classification of Chest X-ray images with a high `Accuracy` & `Recall`/`Sensitivity`.

### Goal Statement
The goal of this effort is to showcase the fact that near-ideal ML training and inferencing can be done using CPU based ACC Confidential computes like Confidential VMs and Confidential ACI.

### Data Source

The data source is `https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia`.

This notebook helps us do chest X-Ray classification to identify an image as `PNEUMONIA` vs `NORMAL`.

Other datasets that also can be showcased as well:

`https://www.kaggle.com/datasets/purna135/chest-xray-dataset`

`https://www.kaggle.com/datasets/nih-chest-xrays/data`

### Steps
- Download the dataset from (`https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia`) to the repo dir
- unzip the dataset
- Run the code in the notebook `Azure Confidential Computing Computer Vision Training`

#### Conclusion

This effort shows how to create effective enough ML models on Confidential Compute TEEs like CVMs & C-ACI without needing to use GPUs or high amounts of CPU computes. 
Does not mean that we do not need GPUs in general, but there are some sophisticated techniques that can help with such scenarios as well.
