# Face-mask-detection-walmartproject
Detecting the humans whether they have worn face mask or not automatically by the system as the breakout of worldwide pandemic COVID-19. We have used deep learning to develop the face detector model with libraries Keras, TensorFlow, OpenCV. 

->Wearing mask have become an important thing in our daily lives and will be required in order to socialize or conduct business. <br>
->The app can be connected to any existing or new IP cameras to detect people with and without mask So that it could become useful in important places like airport, hospitals, office, schools  etc.<br>

### PROPOSED WORK:<br>
We are going to build this project in two parts. <br>
**Training:** Here we’ll focus on loading our face mask detection dataset from disk, training a model (using Keras/TensorFlow) on this dataset, and then serializing the face mask detector to disk <br>
**Deployment:** Once the face mask detector is trained, we can then move on to loading the mask detector, performing face detection, and then classifying each face as with_mask or without_mask. <br>

### SYSTEM REQUIREMENTS: <br>
HARDWARE REQUIREMENTS:<br>
* PROCESSOR –I5-10210U <br>
* HARD DRIVE-1TB <br>
* RAM-8GB <br>
* WINDOWS 10 <br>
SOFTWARE REQUIREMENTS: <br/>
* PROGRAMMING LANGUAGE-PYTHON <br>
* LIBRARY-OPEN CV <br>
* LIBRARY-TENSORFLOW <br>
* LIBRARY-ARGPARSE <br>
* LIBRARY-KERAS <br>
      
To mitigate the spread of COVID-19 pandemic, measures must be taken. We have modeled a face mask detector using MobileNetV2 architecture and transfer learning methods in neural networks. To train,validate and test the model, we used the dataset that consisted of 1916 masked faces images and 1919 unmasked faces images. These images were taken from various resources like Kaggle and RMFD datasets. <br>

  The model was inferred on images and live video streams. To select a base model,we evaluated the metrics like accuracy, precision and recall and selected MobileNetV2 architecture with the best performance having 100% precision and 99% recall. It is also computationally efficient using MobileNetV2 which makes it easier to install the model to embedded systems. This face mask detector can be deployed in many areas like shopping malls, airports and other heavy traffic places to monitor the public and to avoid the spread of the disease by checking who is following basic rules and who is not.<br>
 
 Thanks for reading! :)


 
