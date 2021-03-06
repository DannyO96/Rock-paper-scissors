# Rock-paper-scissors
Interactive rock paper scissors game with the webcam using opencv python and numpy. And a model created on teachable machine.

## RPS Project
>> My RPS project is a project creating an interactive game of rock paper scissors in python where the player can play against the computer with a webcam
>> The technologies used in the project are opencv python and numpy, the model to read the players actions was created on teachable machine using webcam 
photos to train the model.

## Milestone 1
>> I created a model on teachable machine online where I trained the model with images representing each class which would translate to an outcome of the game i.e rock, paper, scissors or nothing. This model was then downloaded to be implemented and I began documenting my project.

## Milestone 2
>> I created a conda environment with the terminal and installed the necessary dependencies including opencv-python, tensorflow, numpy and the ipykernel.
Once the dependencies were installed I ran the model on my local machine to test its ability to read the class i was displaying to the camera.

## Milestone 3
>> I wrote code for the logic of the rock paper scissors game using if and else statements. Next I combined this code with the code to allow my model to read the actions of the player. The issue currently halting my progress is getting the answer of my models prediction in the corrects format this was originally displayed as a probabillity array however using the built in argmax function i have managed to get the answer in the form  of the index position the next step is to link each index position in the list to an answer.

## Milestone 4
>> My code now returns the answer I expected however upon reviewing my code it has been poorly organised and is difficult to understand so my current objective is to
reorganise my code so its neater and more user friendly.
>> I have made some changes to the way the code was organised and have made functions for the game, the computer and user choices. I have reworked the logic of the game to allow for repeated games.

## Milestone 4.5
>>Most of the work i have done since the last milestone has been focused on improving user experience thus i have made it so the user can play the game entirely in the camera frame i also tidied up my code an implemented some object orientated programming to keep the computer and players scores.

## Milestone 5
Further work that could be done to improve the game could be including cv2 image pastes to show the computers options in the frame or writing code for a GUI to appear in the frame whilst playing the game.
I found some issues with being able to teach a model on teachable machine namely that the created model had limitations with its ability to identify what it was being shown. A way to improve this could be by using hand landmarks and maths to identify the shape of the hand this looks as though it could greatly improve the accuracy of the model.
