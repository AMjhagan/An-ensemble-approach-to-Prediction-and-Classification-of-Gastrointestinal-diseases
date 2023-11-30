# An-ensemble-approach-to-Prediction-and-Classification-of-Gastrointestinal-diseases

**Aim**


The aim of this repository is to predict and classify gastrointestinal diseases using a light weight mobile compatible ensemble approach. The three models used are NASNetMobile, MobileNetV3Large and EfficientNetB7.


**About the dataset**


Dataset used: WCE Curated Colon Disease Dataset Deep Learning.

The dataset can be found [here](https://drive.google.com/drive/folders/1BbDhOj90ZrwXQv1zC2atX-fgaTtsGno3?usp=sharing).

The dataset contains 4 classes:
* Normal
* Ulcerative_colitis
* Polyps
* Esophagitis


**Prerequisites**


The following libraries are to be installed before running the code:
* numpy
* tensorflow
* matplotlib
* keras
* sklearn

**To do**

First download the dataset from [here](https://drive.google.com/drive/folders/1BbDhOj90ZrwXQv1zC2atX-fgaTtsGno3?usp=sharing) and code from [here](https://github.com/AMjhagan/An-ensemble-approach-to-Prediction-and-Classification-of-Gastrointestinal-diseases/blob/main/Prediction%20and%20Classification.ipynb). Put both the dataset and code in a folder. 

Then assign the path of dataset to the variable "main_dir" as shown in the example below:

```python
#LOAD THE DATA
main_dir = '../input/curated-colon-dataset-for-deep-learning/'
```

**Conclusion**

This project demonstrated good performance with light weight mobile compatible models and achieved a validation loss of 0.3229 and validation accuracy of 0.8950. Thus it proves to be a valuable tool in the medical field in the future.
