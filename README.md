# Welcome to the master repo!

This is the production branch where we merge front- and backend into production.

# Instructions 
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

Description: Runs the app and combines all files.


## requirements.txt

Description: Contains all dependencies and required packages for running the app. 

## train_SVM.py 

Description: Function that retrains the model. 

## Dockerfile, docker-compose.yaml

Description: Creates docker image and runs the app container. 





