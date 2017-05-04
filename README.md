# Object Detection with CNNs

![object-detect-demo](http://2.bp.blogspot.com/_IDEWI0P9RbA/TB6VMSU8JxI/AAAAAAAAAB4/jlGsKvWF3Ds/s1600/detection.png)

>What is Object Detection?
>The task of assigning a label and a bounding box to all objects in the image.

An object detection problem can be approached as either a classification problem or a regression problem. As a classification problem, the image are divided into small patches, each of which will be run through a classifier to determine whether there are objects in the patch. Then the bounding boxes will be assigned to locate around patches that are classified with high probability of present of an object. 
In the regression approach, the whole image will be run through a convolutional neural network to directly generate one or more bounding boxes for objects in the images.

Object Detection as Classification - RCNN variants.
Object Detection as Regession - YOLO, SSD.


## Popular State of Art approaches:

* FasterRCNN (Faster R-CNN: Towards Real-Time Object
Detection with Region Proposal Networks)
* YOLO (You Only Look Once: Unified, Real-Time Object Detection)
* SSD: Single Shot MultiBox Detector






## Credits