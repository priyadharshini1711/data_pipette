
# Data Pipette
> This project is used to upload and save various patient records from different hospitals (HMS) to one central management unit.
> Hosting Frontend - repo - Click Here  [_here_](https://github.com/priyadharshini1711/data_pipette_frontend).
> Hosting Backend - repo - Click Here  [_here_](https://github.com/priyadharshini1711/data-pipette-backend).

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Screenshots](#screenshots)
* [Setup](#setup)


## General Information
- This is a full stack app built using React and Python for uploading and saving data files
- This app is built based on the problem statement from SIH 2019(Smart India Hackathon).
- This was to extract patient phone detail from their record using python securely and mapping it to their detail page.


## Technologies Used
- React
- Python Flask
- MySQL
- NLP


## Features
- There are two logins to the screen.
- The admin user can upload files that is under their control.
- This will extract file based on the phone numbers present in it.
- The User can Sing In / Register to use the app.
- The user can enter their phone along with their details by OTP method.
- Once their phone is verfied they can uupload and map files to their directory
- The user statistics is also visible to them.
- The user data is protects using hash and personalization techniques via OTP.


## Screenshots
![image](https://user-images.githubusercontent.com/81974121/217779869-dda790fa-e1db-46cb-a53b-c7ebc4cfe2a3.png)
<img width="1121" alt="image" src="https://user-images.githubusercontent.com/81974121/217780357-c5b5ce88-cbc2-4a8d-b311-80979aeff5c4.png">
![image](https://user-images.githubusercontent.com/81974121/217780744-2c331eba-1759-48d9-be43-7de4dcc40d20.png)
![image](https://user-images.githubusercontent.com/81974121/217781050-ddd9b6c1-40f0-4d07-887e-4c51ea217e85.png)
![image](https://user-images.githubusercontent.com/81974121/217781300-c6ac08a7-6014-48d3-8fb2-4bf1cc620b70.png)
![image](https://user-images.githubusercontent.com/81974121/217781746-0daf2090-6839-4213-8caa-b9ce35caf796.png)

## Setup
FRONTEND
- Clone the project.
- Run the command npm i.
- Run the command npm start.
- The application runs in http://localhost:3000/.

BACKEND
- Clone the project.
- Run the command pip install -r requirements.txt
- Run the command flask run.
- The application runs in http://localhost:5000/.
