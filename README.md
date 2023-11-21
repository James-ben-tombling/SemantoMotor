# Semantomotor
## Setup
-Use Python V3.11

### Install all of the these packages at this version:
- numpy~=1.26.0
- tensorflow~=2.14.0
- mediapipe~=0.10.5
- pandas~=2.1.1
- seaborn~=0.13.0
- matplotlib~=3.5.3
- sklearn~=0.0
- scikit-learn~=1.3.2

## To run The system 
- Run the file named app.py 

## To add a new gesture 
- Run the file named app.py 
- Press the number (K) key to start the recording gesture keypoint mode.
- Make the hand gesture you want to record with one hand.
- With the other hand press the (the number of the gesture e.g there are 5 base gesture if you want a 6th press the number 6) button to record the frame infomration of the hand gesture pose to the keypoint classifier dataset (.csv).
- repeat steps 3 and 4 in varying orientations, hands and world positions. (more = better accuracy)
- go into the file named "keypoint_classifier_label.csv" and add the name of the new gesture.
- run the file named Finger_Model_Trainer.py it will retrain the model and give you a accuracy confusion matrix of the end result.
- This new model is now applied to the app,py file, just run the app,py file and it should be good to go. 
