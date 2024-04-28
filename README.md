# Image Classification for Different Types of Damages on Cars

## Description
This project was developed in SS22/23 during the course of Applied Machine Intelligence. The main task was to create and train a model able to classify different types of damages on the cars: rim, scratch, dent or something else.<br>
Thereby, we created a web-app to which the model was deployed. Check out below how to run it: ⬇️⬇️⬇️⬇️⬇️<br>

**NOTE**: The project has not been maintaned. Use at your own risk 😉

## Project Grade:
**1.7** (German scale: 1-best, 5-worst)

## Instructions 
* Option 1: Navigate to the project dir and manually run the app after installing requirements.txt file:
```
pip install -r requirements.txt
```
```
python ./main.py
```

* Option 2 (Recommended): Create docker image and run container with the following command:
```
docker-compose up
```

* Option 3: Webapp is accessible as well on k8s cluster through node port http://10.195.8.77:31501/ . eduVPN should be turned on as well (security). 

## Templates folder

Description: Contains all necessary html files for the frontend representation.

## Static folder

Description: Contains all static files for the frontend respresentation and is used as cache for uploading files from the user interface. All temporary files are automatically deleted after used.

## forms.py

Description: Contains all input fields and forms for the frontend representation.

## main.py

Runs the app and combines all files.


## requirements.txt

Contains all dependencies and required packages for running the app. 

## train_SVM.py 

Function that retrains the model. 

## Dockerfile, docker-compose.yaml

Creates docker image and runs the app container. 

## Credits:
Dionysios Mitsios, Maximilian Studt, Shiyao Xu, Chengyan Zhang, Eren Özcelik, Zishan Li, Xu Yan, Subhosri Basu, Sagnik Dutta





