# Voice-Authentication-CNN
A simple Voice Authentication system using pre-trained Convolutional Neural Network.

## Enrollment:
Enroll a new user using an audio file of his/her voice

first move to the project directory

``python3 voice_auth.py -t enroll -n "name of person" -f C:\path\to\audio\audio.wav``

## Enrollment using csv:
Enroll mutiple users using a .csv file containing list of names and file paths respectively

``python3 voice_auth.py -t enroll -f C:\path\to\csv\list.csv``

 
## Recognition:
Authenticate a user if it matches voice prints saved on the disk

``python3 voice_auth.py -t recognize -f C:\path\to\audio\audio.flac``


## For both recognition and command matching

``python3 cmd_match.py -t recognize -f C:\path\to\audio\audio.flac``

## For setting new command

"change the text of 91th line of cmd_match.py"
