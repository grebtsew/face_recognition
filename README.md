# Face Recognition With PostGis
This fork implementation focuses on creating a program that can answer these questions:

How many different persons have been at a location over a timeperiod?

Who has been at a location?

If we know a person by name, can he be seen in realtime video stream?

During execution this program does the following:
1. Load images from data folder
2. preform detections on webcam images
3. if unknown person detected, create folder and save image, also add image to recognition list
4. Now you can stop the program, rename the folder to your wanted name.
5. The pc vision will recognise you by name.
6. For higher precision add yourself in several different lights and environments.

# About
In this fork of face recognition by Adam Geitgey, I will detect faces in several realtime video streams
and save and compare them with names in folders.

Then we can send queries to the database to know how many different persons have entered, when and who they might be.

# How To Start
1. Install needed python pip packages.
2. run main or main_faster. Main_faster minimize image to speed up recognition. However main is more accurate!

# Note
I have removed ALOT of code that wasn't nessesary to keep from the original repo to make this program work.

# Source
This repository is a fork from Adam Geitgey's awesome repo : https://github.com/ageitgey/face_recognition
Check it out!
