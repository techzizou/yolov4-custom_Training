# Training a custom detector for Object Detection using YOLOv4

![](z.gif)

## **Mask detection using YOLOv4**

The **yolov4** folder contains the 4 custom files needed. (i.e. **yolov4-custom.cfg**, **obj.data**, **obj.names** and **process.py**) except **obj.zip**(labeled images)

I will be sharing my labeled custom mask dataset **obj.zip** file on the following link. You can download it from here.



The **obj.zip** file contains 1370 images along with their YOLO labeled text files. There are approximately 950 images for class **with_mask** and approximately 450 images for class **without_mask**. These images are mostly close-up images. If you want to download more long shot images, you can search for datasets online. There are many sites where you can find more datasets. See the links at the bottom. You can add your own images and their YOLO labeled text files to it. Try to find good quality images.

The **yolov4-custom.cfg**, **obj.data**, and **obj.names** files are customized for the 2 classes I am working with. (i.e. with_mask & without_mask) 

**<ins>NOTE</ins>: You can edit these custom files for your custom object dataset**



## Colab tutorial for training a custom Yolov4 detector. 

https://colab.research.google.com/drive/1zqRb08ljHvIIMR4fgAXeNy1kUtjDU85B?usp=sharing

## Check out my Medium article on this.

https://medium.com/@techzizou007/training-a-custom-detector-using-yolov4-darknet-61a659d4868

## Check out my YouTube video on this 

[Youtube Link](https://www.youtube.com)


![](video2.gif)

## **CREDITS**

###   **References**
 
*    [Alexey AB GitHub ](https://github.com/AlexeyAB/darknet)


### **Dataset Sources**
You can download datasets for many objects from the sites mentioned below. These sites also contain images of many classes of objects along with their annotations/labels in multiple formats such as the YOLO_DARKNET txt files and the PASCAL_VOC xml files.

*   [Open Images Dataset by Google](https://storage.googleapis.com/openimages/web/index.html)

*   [Kaggle Datasets](https://www.kaggle.com/datasets)

*   [Roboflow Public Datasets](https://public.roboflow.com/)

*   [VisualData Datasets](https://www.visualdata.io/discovery)


### **Mask Dataset Sources**
*   [Prajnasb Github](https://github.com/prajnasb/observations)

*   [Andrewmvd Kaggle](https://www.kaggle.com/andrewmvd/face-mask-detection)

*   [X-zhangyang Github](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset)

*   [Chandrikadeb7 Github](https://github.com/chandrikadeb7/Face-Mask-Detection)

### **Video Sources**

*  [Pexels site](https://www.pexels.com/)



