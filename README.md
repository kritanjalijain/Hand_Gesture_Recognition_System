# Hand Gesture Recognition System
College Project- A dynamic hand gesture recognition system for controlling music player. This model recognizes hand gestures in real-time using the power of Convolutional Neural Networks.

## Project Description

The app consists of 3 different modes:
1. __**Data Collection Mode:**__ Allows the user to collect train, test, or validation data on a variety of hand gestures
2. __**Model Testing Mode:**__ Test the model's ability to discern between different gestures through real-time visualizations
3. __**Music-Player/Gesture Mode:**__ Use gestures to play music, pause music, and change the volume of music

#### OpenCV-
* Created a Region of Interest (ROI)
* Capture the background
* Create a background mask
* Use thresholding to create a binary
* Capture data

##### Trained, Validated and Tested Model using Keras on Kaggle’s Cloud Platform-
* Convert Images to NumPy Arrays
* Designed a CNN Network Using Keras
* Trained Model on Kaggle Cloud Platform
* Evaluated on 500 validation images and 500 test images
* Test Accuracy: 99.8%


### Gestures Used:
- Rad: Loads Song
- Fist: Plays/Un-pause Song
- Five: Pause Song
- Okay: Increase Volume
- Peace: Decrease Volume
- Straight: Stop Song
- None: Do Nothing 

## Packages Used
- OpenCV 
- Keras
- Tensorflow
- PyGame
- NumPy

## Files
Here's a list of files in the directory:
- `src/demo.py`: Contains all the functions to start and run the app
- `src/music`: Contains the song that will be played during 'gesture mode'


