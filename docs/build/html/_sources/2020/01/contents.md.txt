# 01

Literature review for Jan 2021

## Joint Modelling of Chest Radiographs and Radiology Reports for Pulmonary Edema Assessment

[Link](https://arxiv.org/abs/2008.09884 "Markdown")

注释：
Pulmonary Edema - 肺水肿

### **First pass: general information**
#### Category: 
This paper present a machine learning algorithm/approach.
#### Contribution
It is present a neural network model that jointly learns from images and text to assess pulmonary edema severity from chest radiographs. The joint image-text representation learning framework incorporates the rich information present in the free-text radiology reports and significantly improves the performance of edema assessment compared to learning from images alone. The experimental results show that joint representation learning benefits from the large amount of unlabelled image-text data.
	
### **Second Pass: detail explaination**
This section is trying to figure out three main questions.
#### What does it do?
- Uses a series of residual blocks to encode the image representation and uses the BERT model to encode the text representation.
- Data: regex labelling
#### How does it do it? 
- Image pairs (image and text report)
- One of the key contribution is: how to connect the two different classifier? (joint representation learning for both image and text)
#### What did it find? 

### **Third Pass: strengths and weakness**

* * * * * 

## CheXpert: A Large Chest Radiograph Dataset

[Link](https://stanfordmlgroup.github.io/competitions/chexpert/ "Markdown")

### **First pass: general information**

#### Category
This paper present a large labeled Chest Radiograph Dataset and one automation labeler.

#### Contribution
There are three main contributions in this paper.

### **Second Pass: detail explaination**

#### General information of CheXpert Dataset

##### meta information

View position from ViewCodeSequence_CodeMachine section, there are total 8 kind of machine code positon, there are: 

1. postero-anterior
2. antero-posterior
3. lateral
4. left-lateral
5. erect - 直立
6. left anterior oblique - 左前斜
7. recumbent - 卧式, this type is very little
8. blank 

##### class 

There are totally 14 classes in this dataset, they are: Atelectasis 肺不张, Cardiomegaly 心脏肥大, Consolidation 肺实变, Edema - pulmonary edama 肺水肿, Enlarged Cardiomediastinum 纵膈扩大, Fracture 骨折, Lung Lesion 肺部病变, Lung Opacity 肺部浑浊, No Finding, Pleural Effusion 胸腔积液, Pleural Other 胸腔其它, Pneumonia 肺炎, Pneumothorax 气胸, Support Devices.

In the original CheXpert paper, only 5 out of 14 classes that contain main pathology inidications has been evaluated, there are: Atelectasis, Cardiomegaly, Consolidation, Edema and Pleural Effusion.

#### Data Pre-processing for my project

- while processing the data to suit my project objecive, consider to use the front/erect image only which are postero-anterior, antero-posterior, erect and blank in ViewCodeSequence_CodeMachine section. 

### **Third Pass: strengths and weakness**

* * * * *

