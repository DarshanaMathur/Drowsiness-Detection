# Drowsiness-Detection
This is a very Interesting Repository, that introduces to Face Detection, Eye Detection, CNN, Haar Classifier Models.

Here we have first of all used the Haar classifier model to detect the face of teh person in the webcam and then again using the Haar classifier we have detected the eyes of the person. 

After detecting the eyes, we have then used the previously trained CNN model, which can be downloaded by scanning the QR Code, to get the probability of the eyes being shut and open. 

Once, we have detected the eyes shut or open we have then moved forward to find out the seconds during which the eyes were closed and reduce the score when the eyes remain open. 

Once, a certain score is achieved the alarm file is called and played to alert the person regarding drowsiness. 

Note: You will require a webcam to complete this project. 
