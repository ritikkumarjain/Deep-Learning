# Emotion Detection 

### Note 1: Most of the approaches can't be shared now. Hence providing with a overview.
### Note 2: Python Notebooks can't be shown since we are still in the process of publishing the paper.

### Project Status ![image](https://user-images.githubusercontent.com/69076815/148382182-c43da7f7-6f46-4562-9d6e-db3aa9deb700.png)
- Finding Insights: Completed
- Paper Writing: Paper Writing Done. Paper currently accepted by PCCDS

### Project Members ![image](https://user-images.githubusercontent.com/69076815/148382182-c43da7f7-6f46-4562-9d6e-db3aa9deb700.png)
- Project Supervisor: Ankur Jyoti Sarmah(Assitant Professor, Assam Engineering College)
- Nitin Bhattacharyya
- Priyankar Maroti
- Ritik Kumar Jain(Me)


### Introduction  ![image](https://user-images.githubusercontent.com/69076815/148382182-c43da7f7-6f46-4562-9d6e-db3aa9deb700.png)
The project intends to first detect various human emotions through facial recognition and then shows different applications of it. Different Machine Learning techniques are employed to achieve the goal of this project. The various applications of emotion detection in real life may be in special education where it may help people suffering from autism to recognize other people’s emotion, in work environments where it can be used as a tool to check on the emotional fluctuation of various employees and regulate the work load accordingly and in medical diagnosis of some mental diseases like depression, anxiety etc with the help of which psychiatrists can discover early signs and then suggest appropriate therapy for fast recovery from the disease.



### 1) Objectives ![image](https://user-images.githubusercontent.com/69076815/148382182-c43da7f7-6f46-4562-9d6e-db3aa9deb700.png)
The specific Objectives are: 
- Collection of Data
- Making a base CNN Model for Emotion Detection
- Hyperparamter Optimization to find suitable Model/Model parameters
- Training the Data on that model which attains highest accuracy

### 2) Data Collection ![image](https://user-images.githubusercontent.com/69076815/148382182-c43da7f7-6f46-4562-9d6e-db3aa9deb700.png)
The Facial Emotion Recognition 2013 dataset was used. It is a benchmark dataset in Emotion Recognition. This dataset is used in most of the research papers for finding a sutibale Model.

### 3) Baseline Model ![image](https://user-images.githubusercontent.com/69076815/148382182-c43da7f7-6f46-4562-9d6e-db3aa9deb700.png)
Baseline Model achieves a max accuracy of 65.55% on testing set. Model has very high Overfitting.
![image](https://user-images.githubusercontent.com/69076815/176212863-f2bdd93d-b201-4f35-b4f3-80a9d84c71c2.png)
Baseline Accuracy: 65.55%

### 4) Hyperparamter Optimization ![image](https://user-images.githubusercontent.com/69076815/148382182-c43da7f7-6f46-4562-9d6e-db3aa9deb700.png)
Keras Tuner was used for finding sutibale parameter. All of these was done in Kaggle Environment using the default Kaggle GPU that took a very long time. Greater than 15 hours.


### 4)Final Models ![image](https://user-images.githubusercontent.com/69076815/148382182-c43da7f7-6f46-4562-9d6e-db3aa9deb700.png)
Model 1: Accuracy 70.58%. High overfitting so it is not considered.
![image](https://user-images.githubusercontent.com/69076815/176213097-792994b9-cfd2-45d5-ac69-3fdd993c1ae4.png)

Model 2: Accuracy 68.21%. Variance is very low.
![image](https://user-images.githubusercontent.com/69076815/176213285-8b0a1624-22fa-4705-99bd-3957c69a7830.png)

Model 3:Accuracy: 69.55%. There is a small amount of variance but we think it can be considered for evaluation.
Final Model finded out using Keras tuner achieved a accuracy of 69.55%. 
![image](https://user-images.githubusercontent.com/69076815/176213422-afd1e709-533a-4f9c-a9e9-1187b1897664.png)



### 5) Overall Ranking In Leaderboards ![image](https://user-images.githubusercontent.com/69076815/148382182-c43da7f7-6f46-4562-9d6e-db3aa9deb700.png)

- On basis of Global Ranking
![image](https://user-images.githubusercontent.com/69076815/176214093-e328aefd-39a0-40a3-b047-068311743caf.png)
![image](https://user-images.githubusercontent.com/69076815/176214136-be6dd3a3-f2ce-4197-a6f4-257a4646face.png)


- On basis of type of Network Model used
![image](https://user-images.githubusercontent.com/69076815/176214253-ba4f6343-17fc-49be-8937-082f3b739527.png)


- On basis of No extra data  used with Fer13 dataset for training 
![image](https://user-images.githubusercontent.com/69076815/176214383-9c05db36-b27d-4eab-b7fe-2d972896e392.png)




