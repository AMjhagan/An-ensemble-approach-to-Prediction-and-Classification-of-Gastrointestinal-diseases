# An-ensemble-approach-to-Prediction-and-Classification-of-Gastrointestinal-diseases
<br />

**Aim**


The aim of this repository is to predict and classify gastrointestinal diseases using a light weight mobile compatible ensemble approach. The three models used are NASNetMobile, MobileNetV3Large and EfficientNetB7. 

A detailed video explaining this project can be found [here](https://youtu.be/gYgb3zhQskQ). [Here](https://github.com/AMjhagan/An-ensemble-approach-to-Prediction-and-Classification-of-Gastrointestinal-diseases/blob/main/Presentation.pptx) is the PPT used for the video.

The Research paper draft for this project can be found [here](https://github.com/AMjhagan/An-ensemble-approach-to-Prediction-and-Classification-of-Gastrointestinal-diseases/blob/main/Prediction%20and%20Classification%20of%20Gastrointestinal%20Diseases%20.pdf).

The research papers which we used for reference can be found [here](https://github.com/AMjhagan/An-ensemble-approach-to-Prediction-and-Classification-of-Gastrointestinal-diseases/blob/main/References.xlsx).
<br /><br />

**About the dataset**


Dataset used: WCE Curated Colon Disease Dataset Deep Learning.

The dataset can be found [here](https://drive.google.com/drive/folders/1BbDhOj90ZrwXQv1zC2atX-fgaTtsGno3?usp=sharing).

The dataset contains the following 4 classes:
* Normal
* Ulcerative_colitis
* Polyps
* Esophagitis
<br />

**Prerequisites**

The following libraries are to be installed before running the code:
* numpy
* tensorflow
* matplotlib
* keras
* sklearn
<br />

**To do**

First download the dataset from [here](https://drive.google.com/drive/folders/1BbDhOj90ZrwXQv1zC2atX-fgaTtsGno3?usp=sharing) and code from [here](https://github.com/AMjhagan/An-ensemble-approach-to-Prediction-and-Classification-of-Gastrointestinal-diseases/blob/main/Prediction%20and%20Classification.ipynb). Put both the dataset and code in a folder. 

Then assign the path of dataset to the variable "main_dir" as shown in the example below:

```python
#LOAD THE DATA
main_dir = '../input/curated-colon-dataset-for-deep-learning/'
```
<br />

**Conclusion**

This project demonstrated good performance with light weight mobile compatible models and achieved a validation loss of 0.1915 and validation accuracy of 0.9330. Thus it proves to be a valuable tool in the medical field in the future.
