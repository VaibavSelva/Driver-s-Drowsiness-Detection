# A study of machine learning-based driver drowsiness detection systems
 
  
**Dataset Description**   

The Complete System consists of 2 datasets:  
    i)   Dataset for Eye Open/Close state. The source of the dataset is https://www.kaggle.com/datasets/serenaraju/yawn-eye-dataset-new which contains 615 Open and Closed Eye state Images.  
    ii)  The Second dataset used is same as first one which contains about 600 images of Yawn/Not Yawning Driver images taken from Appropriate angle.  
    
    
# Model Training and Results 
Each dataset is utilized to train two distinct CNN models.A custom-built CNN model with an accuracy of 97% for the Eye State Classification Model and 92% for the Yawn Detection Model has been implemented.The employed architecture is relatively straightforward, consisting of 3–4 Conv2D levels, each followed by a Pooling layer, and one Dropout layer.

# Usage  
Activate the drowsiness detector using the detector.py file. You will need two model.h5 files that are located in the same directory, and you will need to specify the path to these files in the drowsiness detector module.
