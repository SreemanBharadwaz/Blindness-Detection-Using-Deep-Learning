Blindness here referring to DiabeticRetinopathy detection People suffer from diabetes are likely to have this disease. The symptoms are swelling, blurness etc. unfortunately this disease is irreversible - It cannot be cured if it is not detected at the mild stage! The doctor has to analyse the fundus images of the patient taken by technician, all the prominent features or symptoms may not be clearly visible at mild stage which makes it difficult to diagnose it at mild stage So using automatic tools to detect it using deep learning is proposed which will take fundus image as input and classifies it into five class(stages of diabetic retinopathy)-

a)Mild

b)Moderate

c)Proliferate

d)Severe

e)No diabetic retinopathy

This repository consists of -
app.py - deployment code diabetic_retinopathy.ipynb - model training code train.csv - labeling of images static folder - consists of css and js files template folder - consists of hmtl files

The sample of dataset -
![image](https://user-images.githubusercontent.com/116734847/198073263-e1f4cb40-cc69-4f8f-86f0-27127c0fcda3.png)

The dataset consists of five classes -
![image](https://user-images.githubusercontent.com/116734847/198073692-54159a21-9b3d-46dc-8bcc-46d72f132446.png)
The architecture used here is RESNET18
The sample of model summary is shown below -
![image](https://user-images.githubusercontent.com/116734847/198073840-15e59469-1cfa-480f-9e0a-06e56ea367cb.png)
![image](https://user-images.githubusercontent.com/116734847/198073877-f98e8857-f747-4db2-a2a2-23e2d09a213b.png)
![image](https://user-images.githubusercontent.com/116734847/198073933-9d16beb0-9478-4017-bff5-d092697f6295.png)
Screenshots of tool developed -
The below is the Home page - This page includes the Risk factors, Symptoms, When to visit a doctor and information about five classes
![image](https://user-images.githubusercontent.com/116734847/198074039-8e2582a3-7833-4159-82f8-678ff9214345.png)
![image](https://user-images.githubusercontent.com/116734847/198074122-ae2a7239-2c0e-41bd-9d06-2eea307664ed.png)
![image](https://user-images.githubusercontent.com/116734847/198074166-80795973-028a-419c-bb19-5d24f8dd60e4.png)
The below is Predict page - The user has to upload a fundus image and the diagnosis will be displayed
![image](https://user-images.githubusercontent.com/116734847/198074354-e5525881-ccee-49cf-9c13-a757ebda30e2.png)


