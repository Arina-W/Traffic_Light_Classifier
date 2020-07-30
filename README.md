# Traffic Light Classifier


In this project, I used computer vision techniques to build a classifier for images of traffic lights.
I used a given dataset of traffic light images in which one of three lights is illuminated: red, yellow, or green.

In the [Traffic_Light_Classifier notebook](https://github.com/Arina-W/Traffic_Light_Classifier/blob/master/Traffic_Light_Classifier.ipynb) I did
pre-processing image routine, extract features that will help distinguish types of images, and use the features to classify test images into three 
categories : red, yellow, or green. 

The task can be broken down into a few sections describes below :

1. Loading and visualizing the data
2. Pre-processing
3. Feature extraction
4. Classification and visualizing error
5. Model evaluation

Here are some sample image from dataset:

![sample](https://github.com/Arina-W/Traffic_Light_Classifier/blob/master/images/all_lights.png)


# Result = 94.3% Accuracy achieved

Accuracy was determined by comparing the output of my classification model with the true labels of all 297 test images.
Out of all tests, one golden rule that is prioritized and maintained is "No red lights classified as green".

```
Accuracy: 0.9427609427609428
Number of misclassified images = 17 out of 297
```


