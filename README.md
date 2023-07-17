# Monkeypox Disease Detection
Healthcare professionals worldwide are increasingly concerned about the current monkeypox outbreak, emphasizing the importance of early diagnosis to mitigate its rapid progression. In response to that, In this project, I developed an Android app which will detect monkeypox diseases. The image dataset which was used in this project was developed by the Department of Computer Science and Engineering, Islamic University, Kushtia-7003, Bangladesh. </br>
</br>

## Workflow
1. Data exploration
2. Data Pre-processing
3. Model Training
4. Model saved to model.tflite
5. Basic Android App Development

## Data
The dataset has four classes :-
1. Monkeypox
2. Chickenpox
3. Measles
4. Normal</br>
</br>
Each class has 107 items with dimension of 224*224. For model training Data Augmentation is done.
<p align="center">
  <img width="700" src="https://github.com/Prashant812/Siya/assets/93676625/07b60226-1ec9-4c90-9684-443469ea21f9" >
</p>

## Model
CNN Model was used with model architecture :-
<p align="center">
  <img width="700" src="https://github.com/Prashant812/Siya/assets/93676625/b79676e6-c32e-49ab-96d6-d49c790139db" >
</p>

### Accuracy
* Training Accuracy - 87.38 %
* Test Accuracy - 86.46 %

## Android App
A basic android app was developed with simple architecture which consist two options :- </br>
* Take Picture
* Launch Gallery </br>
</br>
An user can install this app and click those images with skin diseases to be classfied as Monkeypox, Chickenpox, Measles, and Normal.
</br>

### Sample Responses
<p align="center">
  <img width="300" src="https://github.com/Prashant812/Siya/assets/93676625/031bbed1-e14a-443d-a2af-7f8fcd8e0744" >
  <img width="300" src="https://github.com/Prashant812/Siya/assets/93676625/42ec8013-fed1-4713-9cb9-bdf50c29e650" >
  <img width="300" src="https://github.com/Prashant812/Siya/assets/93676625/0294c0f3-6d5c-44e5-a72b-603fe14e6bae" >
</p>
<p align="center">
  <img width="300" src="https://github.com/Prashant812/Siya/assets/93676625/00a125ea-e053-4421-afd8-786c6bca4687" >
</p>






