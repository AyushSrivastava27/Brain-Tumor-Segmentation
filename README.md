## Brain Tumour Detection Using MRI Images

### 1. Problem Definition

Classification and Segmentation of Brain Tumours from MR Images Using Deep Transfer Learning.

### 2. Data

The data we're using is for Kaggle's Brain Tumor MRI Dataset

https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

This dataset is a combination of the following three datasets:
- figshare
- SARTAJ dataset
- Br35H

### Visualization

![Different Brain Tumor Class Images](https://github.com/AyushSrivastava27/Brain-Tumor-Segmentation/assets/98225930/74a65599-f9cd-4a40-ab35-fd9eff9433cd)


### Fine-Tuning Deep Learning Models for Multimodal Brain Tumors

- **Implemented Deep Learning and Transfer Learning by fine-tuning and comparing EfficientNetB0, ResNet50V2, InceptionV3,
and DenseNet121**

- **Performed various experiments to determine the best model using matrices like Accuracy, Precision, Recall, and F1-score**

### Model Fusion Technique

#### Feature Concatenation

To improve the classification of brain tumor MRI images, we have used the feature concatenation model fusion technique. 

Specifically, after assembling and training the model on our dataset, we concatenated the layers of EfficientNetB0 and InceptionV3.
 
 Our model evaluation produced some outstanding performance metrics:
 
 - **Accuracy**: 99.47%
 - **Precision**: 99.47%
 - **Recall**: 99.47%
 - **F1 score**: 99.42%
