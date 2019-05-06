# Detection of Pneumonia in Chest X-rays using Segmented CNN- RSNA Pneumonia Detection Competition on Kaggel
### CS 634 - Prof Monogioudis

## Overview
We will utilize the methods of machine learning to create a solution to the RSNA Pneumonia Detection Challenge for Dr. Monogloudis' Machine Learning class. We do this through the use of residual network convolutional neural networks to segment out lung opacities given a digital image of a x-ray. 

The challenges we will face will be similar to the ones facing the radiologists and specialists in the clinical setting - the pneumonia digital signal is represented by an opaque area of a chest x-ray. This signal can be clouded by the noise of other pathologies or even poor x-rays of normal lungs. Please refer to the notebook for detailed methodology.

## Running the notebook

Using Google Colaboratory, import the Python notebook .ipynb file. Next Run All segments (Runtime --> Run All). In the Files slider, you should now see a submission.csv. That is our prediction for the test data. **All report write-up is within the python notebook.** 

## Additional Files
submission.csv - final predicted bounding boxes for pneumonia

model training log.txt - log of the model training based on 10 epochs

## Built With

* Keras and Tensorflow - Machine learning framework used for CNN in our project
* Matlabplot - Data analysis and visualization tool
* Numpy - Mathematical framework used for linear algebra calculations
* Pandas - Data analysis and visualization tool
* Seaborn - Data plotting and visualization


## Authors

* **Imran Hashmi**
* **Jalaj Sharma**
* **Lee Zhang**

## Acknowledgments

* Jonne on Kaggle
