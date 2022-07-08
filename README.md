# Handwritten-Digit-recognition

This video Shows the demo of the working project

https://youtu.be/l0UrfApE3gk

Real-Time Hand Writing project lets the user detect the handwritten digit.
This small project is implemented on the Raspberry Pi which gives the user complete 
flexibility to travel with the device and show its use. We make the digit display on the 
SenseHat of the Raspberry pi. Since we are trying to implement the project in real-time, 
we loop through the camera to capture the photos and run it through the trained Neural Network and
check for the confidence level to be more than 50%. If the captured photo gives 50% of the confidence
we then print the digit on the SenseHat. 

In order to train the Neural Network to give the best result we use Convolution Neural Network to train
till the point it gives accuracy above 95%. With such accuracy we can be certain for the Network to give 
the accurate result for most of the case. Since we are using the Raspberry pi camera we need to check with 
the resolution to get the maximum output. Raspberry pi is a development platform where Neural Network can be trained
and implemented with not such a great difficulty, in fact Raspberry pi allows users to capture images on a regular interval 
that is such a great use in this project. .
 
