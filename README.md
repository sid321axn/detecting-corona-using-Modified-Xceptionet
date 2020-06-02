# Diagnosis of Corona Virus Disease (COVID-19) from Chest X-Ray images using modified XceptionNet

<pre>
Domain             : Computer Vision, Machine Learning
Sub-Domain         : Deep Learning, Image Recognition
Techniques         : Deep Convolutional Neural Network, XceptionNet
Application        : Image Recognition, Image Classification, Medical Imaging
</pre>

### Project Highlights
<pre>
1. Detected Coronavirus (COVID-19) induced Pneumonia from Chest X-Ray images using Deep Convololutional Neural Network inspired from XceptionNet architecture with 1419 Posterior Anterior (PA) view images of Chest X-ray (COVID-19 : 132 images, Viral Pneumonia : 619 images, Normal/Healthy : 668 images).
2. For classifying Normal, COVID-19 and Viral Pneumonia classes architecture of pretrained network XceptioNet modified.
3. Proposed Modified XceptionNet Network attained testing accuracy of 95.80%, Precision of 96.16%, Sensitivity of 95.60%  and F1-score of 95.88%.
</pre>

#### Dataset
<pre>
Dataset (Normal & Viral cases)     : <a href=https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia>Chest X-Ray Images (Pneumonia) Dataset (Kaggle)</a>
Dataset (COVID-19)    : <a href=https://github.com/ieee8023/covid-chestxray-dataset>COVID Chest xray dataset</a>
Our Associated Paper   : <a href=https://www.romjist.ro/full-texts/paper657.pdf>Diagnosis of Coronavirus Disease (COVID-19) from Chest X-Ray images using modified XceptionNet</a>
                   (Krishna Kant Singh, Manu Siddhartha, Akansha Singh)
                   
</pre>
The sample images of Normal, Viral and COVID-19 patients are shown in figure below:
![Image of CXR](https://i.ibb.co/b5NYxTN/sample-img.png)

<pre>
<b>Dataset Details</b>
Dataset Name            : Chest X-Ray Images (Normal vs COVID-19 vs Viral)
Number of Class         : 3
Number/Size of Images   : Total      : 1419 (555 MB)
                          Training   : 1135 
                          Testing    : 284 
                         
</pre>
#### Results
We have achieved following results which outperform 4 previous state-of-the-art deep CNNs for detection of COVID-10 from CXR.

<pre>
<b> Performance Metrics </b>
5-Fold Cross Validation Accuracy (100 Epochs)    : 96.45%
Test Accuracy                                    : 95.88%
Precision                                        : 96.16%
Sensitivity (COVID-19)                           : 96% 
Sensitivity (Viral)                              : 94% 
F1-score                                         : 95.88%
AUC                                              : 0.99
</pre>
