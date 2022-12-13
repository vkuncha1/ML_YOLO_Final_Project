# CS536: Final Project
Team Members:
1. Venkata Achyuth Kunchapu (Implemented the YOLO v1)
2. Sandeep Vangapandu (Researching and co-implemeted the YOLO v1)
3. Uday Mekala (Changes in Existing Architecture)

-----------------------------------------------------------------------
-----------------------------------------------------------------------

-----------------------------------------------------------------------
## How to run ?

In Paper Authors trained the model for 1 week.

In our implementation, we ran our model from 40-100 epochs estimated time is 3 hrs, (Use GPU for faster execution)

Upload your kaggle.json file in order to run the .ipynb file 
This file needs a VOC dataset from the kaggle

-----------------------------------------------------------------------
## Description:

We have re-implemented the YOLO(v1) Architecture using VOC data set.
YOLO resizes input images to 448 x 448, runs a single convolutional network on the input and The feed-forward process extracts convolutional features and regresses them into bounding box values and class probabilities

Code includes calculation for Mean Average Precision(maP) for test and training dataset,

Train maP:

0.84


Test maP

0.20



-----------------------------------------------------------------------
## Sample Output:




<img width="1093" alt="res2" src="https://user-images.githubusercontent.com/113220900/206961108-3dc1a92d-a0f1-4df5-a03c-eaf8837d3bee.png">
<img width="1066" alt="Untitled 4" src="https://user-images.githubusercontent.com/113220900/206961121-b6d649b3-3386-434b-8988-602c8bb4d1e5.png">







-----------------------------------------------------------------------
## References:

1. https://www.youtube.com/watch?v=n9_XyCGr-MI (Implemented after understanding this lecture on YOLO v1)
2. https://www.kaggle.com/code/burakkocak14/pytorch-yolov1-from-scratch
3. https://github.com/JeffersonQin/yolo-v1-pytorch




