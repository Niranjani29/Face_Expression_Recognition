# Face_Expression_Recognition
Face Expression recognition model using Keras


Real time facial expression recognition of eight most basic human expressions: ANGER, DISGUST, FEAR, HAPPY, NEUTRAL, SAD, SURPRISE, PAIN.
This model can be used for prediction of expressions of both still images and real time video. 
However, in both the cases we have to provide image to the model. 
In case of real time video the image should be taken at any point in time and feed it to the model for prediction of expression. 
The system automatically detects face using HAAR cascade then its crops it and resize the image to a specific size and give it to the model for prediction. 
The model will generate eight probability values corresponding to eight expressions. The highest probability value to the corresponding expression will be the predicted expression for that image.

