# Javascript image classifier in browser with TensorFlow 

## Introduction 
This is a very simple image classifier. What is interesting about this particular one is the fact it is done in the browser.

## Installation 
There are no dependencies and there are only two files needed to run it. The first is the HTML file which you would need to open in your browser and the second is the Javascript file which would need to be in the same folder.

## Tips & Trick 
You will have to allow your browser to access your Webcam and obviously you would need a webcam on your machine. Chrome worked for me and I did not investigate further to see why it would not work in some of the other browsers.

## Functionality 
There are four buttons on the webpage; A to D. You have to train the four classes in the image classifier:
A ='Look at Camera’, B='Hand in Face (peeping), C='Bunny Ears with Left Hand', D='No one at desk' for example.
You can classify 4 distinct objects or postures and then see how well it classifies it. Make sure the object or postures are distinct enough to get a working model.
I suggest you take about 10 photos of each posture and make sure they are all slightly different but in line with the class 

The classifier is not saved and once you refresh or exit the browser it is reset to untrained.



