# Overview

Links to the [documentation](https://justin900429.github.io/object_detection/)

## Introduction
This project is for users to quickly deployed their object detection application. The backend used [Google Cloud Vision API](https://cloud.google.com/vision/) for object detection. The release now can only used the built in object detection trained by Google. In the future release, we will add [Google AutoML](https://cloud.google.com/automl) to fulfill costumed needs.

## Classes
The library contain two classes for use:  

* Detection  
    User can use this class to get the return image with bounding box on it.
      
* Interface  
    This class supports the GUI interface for the detection images and allows user to upload images to [Google Cloud Storage](https://cloud.google.com/storage/).
    
## Installation
```commandline
pip install GC-Detection
```

## Example Code
The example code was upload to the github directory, please visit [here](https://github.com/Justin900429/object_detection/tree/main/example)