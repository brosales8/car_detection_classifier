# Building a Car Detection and Tracking using a Classifier
### Udacity - Self-Driving Car NanoDegree

**Author:** Bryan Rosales
**Date:** August 24th, 2017


Overview
---

The focus of this project is to fit a SVM classifier using features extraction technique (Spatial Bin, Color Histogram, HOG) on car and no car images. Then, using a video that show the road, the pipeline makes a grid search to extract pictures in order to feed the classifier and get output identification of there is a car or not. Also, if a car is identified, it is tracked while the camera (video) can see it. The general idea is to show how the self-driving car identify the surronding environment when on the road.  
Please see [Writeup](https://github.com/brosales8/car_detection_classifier/blob/master/WriteUp.html) for more details of the project.

Files
---
- [P5.ipynb](https://github.com/brosales8/car_detection_classifier/blob/master/P5.ipynb) Jupyter Notebook file providing the source code of the classifier.
- [WriteUp.html](https://github.com/brosales8/car_detection_classifier/blob/master/WriteUp.html) Step by step explanation of the process followed to reach the scope of the project.
- [/test_images](https://github.com/brosales8/car_detection_classifier/tree/master/test_images) Images provided by Udacity to build the pipeline.
- [/output_images](https://github.com/brosales8/car_detection_classifier/tree/master/output_images) Classifier SVM output Images. 
- [/videos](https://github.com/brosales8/car_detection_classifier/tree/master/videos) Videos provided by Udacity to test the pipeline.
- [/dataSet](https://github.com/brosales8/car_detection_classifier/tree/master/dataSet) Image dataset of cars and no cars.