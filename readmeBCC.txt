Author: Saltanat Khalyk, Mukhamedjan Karatayev

Topic:  Breast cancer classification using Deep learning models
Dataset: https://www.kaggle.com/paultimothymooney/breast-histopathology-images/


Dataset description:
The original dataset consisted of 162 whole mount slide images of Breast Cancer (BCa) 
specimens scanned at 40x. From that, 277,524 patches of size 50 x 50 were extracted 
(198,738 IDC negative and 78,786 IDC positive). 
Each patch’s file name is of the format: 
uxXyYclassC.png — > example 10253idx5x1351y1101class0.png . 
Where u is the patient ID (10253idx5), 
X is the x-coordinate of where this patch was cropped from, 
Y is the y-coordinate of where this patch was cropped from, 
and C indicates the class where 0 is non-IDC and 1 is IDC.

 
We played with data and split them to train, test, validation sets.
Train 80%
Test 10%
Validation 10%

Resnet18 accuracy is 80%
Densenet accuracy is 82%

