# Hand gesture recognition using CVZONE
This research investigates the use of the ’cvzone’ library for hand gesture recognition, which is an important part of improving human- computer interaction.  
The model for identifying these hand landmarks consists of 21 coordinates representing the positions of hand joints. A connecting line is drawn between these key points, and the angles between them are meticulously calculated.  
![21 key poins in hand](https://github.com/QuagHien/hand-gesture-recognition-using-CVZONE/blob/master/images/21%20features%20hands.png)
## Quick Start
Clone this project and install the required packages:
```
git clone https://github.com/QuagHien/hand-gesture-recognition-using-CVZONE.git
pip install -r hand-gesture-recognition-using-CVZONE/requirements.txt
```
## Hand gesture recognition
We have a simple model to identify cheating in multiple-choice exams:
```
python3 hand-gesture-recognition-using-CVZONE/HandGestureRecognitionusingCVZONE.py
```
You can experience a simpler model of mine at [MediaPipe Studio](https://mediapipe-studio.webapps.google.com/demo/gesture_recognizer) developed by Google.
