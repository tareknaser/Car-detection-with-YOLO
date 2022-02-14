# Car Detection with YOLO

### This was intended for the Week 3 programming assignment on Convolutional Neural Network for [deeplearning.ai](https://www.coursera.org/specializations/deep-learning?).

![Screenshot 1](/images/preview.png)

### Built With
- Python
- Tensorflow - ML library

### Inputs and outputs
The input is a batch of images, and each image has the shape (m, 608, 608, 3).

The output is a list of bounding boxes along with the recognized classes. Each bounding box is represented by 6 numbers (𝑝𝑐,𝑏𝑥,𝑏𝑦,𝑏ℎ,𝑏𝑤,𝑐). If you expand 𝑐 into an 80-dimensional vector, each bounding box is then represented by 85 numbers. 

### How to start car detection:
- Add your image to this Jupyter Notebook's directory, in the "images" folder.
- Write your image's name in (3.5 - Run the YOLO on an Image).
- Run the code and see the output of the algorithm!

### Prediction sample:

![Screenshot 1](/images/test.jpg)
![Screenshot 2](/images/preview2.png)

### References
The ideas presented in this notebook came primarily from the two YOLO papers. The implementation here also took significant inspiration and used many components from Allan Zelener's GitHub repository. The pre-trained weights used in this exercise came from the official YOLO website.

Joseph Redmon, Santosh Divvala, Ross Girshick, Ali Farhadi - You Only Look Once: Unified, Real-Time Object Detection (2015).

Joseph Redmon, Ali Farhadi - YOLO9000: Better, Faster, Stronger (2016).

Allan Zelener - YAD2K: Yet Another Darknet 2 Keras.

The official [YOLO website](https://pjreddie.com/darknet/yolo/).
