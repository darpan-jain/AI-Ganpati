This repository contains a fun application made on python3 intended to dispense sweets to individuals based on their choice.

Before running the codes, we need to install all the prerequisites. Have made a requirements.txt for the same. 
Use ''' pip3 install -r requiremnts.txt ''' to install prerequisites.

**Input**

> - Run ''' python3 input.py ''' to give face input and then voice input of sweet choice (laddu/modak/pedha).

> - LEDs can be used to display the status to a user. (see Scripts)

> - The code uses the MTCNN model for Face detection.

> - Face alignment is done using dlib.

> - FaceNet is used for converting the various features of a person's face into vectors (embeddings).

**Output**

> - Run ''' python3 recognition.py '''

> - When a face is detected, the system checks if the person exists in the database.

> - On recognition, the corresponding label is displayed.

> - The robotic arm dispenses the sweet of choice once per person.

**Contents**

1. requirements.txt - contains all the prerequisites required for the functioning of the application.

2. models - conatins trained models required for face inference.
	- Note: The voice model has been pre-trained using several different voice samples.

3. uitls - contains the all dependencies that the main codes require.

4. words - contains the voice input given by user which will be used to get the label.

5. scripts - contains script files to perform various actions using Arduino GPIO pins. 

6. arduino-codes - codes for some action to be performed. 
	


*Any contributions to the project are welcome :)*