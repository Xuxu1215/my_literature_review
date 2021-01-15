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
This paper present a large labeled Chest Radiograph Dataset.

#### Contribution
There are three main contributions in this paper. First, this dataset consists of 224316

### **Second Pass: detail explaination**

### **Third Pass: strengths and weakness**


