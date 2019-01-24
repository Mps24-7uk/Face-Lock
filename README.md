# Face-Lock

 It is capable of identifying or verifying a person from a video frame.

In order to successfully implemented this project. We have to follow certain steps:

1. Create the training dataset
-Capture 100 samples of faces by using Haar Cascade
-Grayscale image to remove the noise

2. Train the Model
-Retrieve the dataset
-train the Model by using the face.LBPHFaceRecognizer_create method

3. Classifying the New Input i.e User face
-Extract the face from the webcam by using Haar cascade
-Feed the Face Image to our pre-trained model. 

If the Face matches, it will unlock the screen.
