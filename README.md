# Face Mask Detection

A simple example of using convolutional neural networks for face mask detection. There are three classes in total;
  - Incorrect_mask
    - Examples include mask on chin, mask on mouth but not nose
  - With_mask
  - Without_mask

I used a dataset from Kaggle [https://www.kaggle.com/datasets/shiekhburhan/face-mask-dataset?resource=download]. I used all images, complex and simple to train and evaluate this model. 

11629 samples were used for training spanning across the 3 classes.

The evaluation was performed on fairly balanced classses as shown by the support below

                precision    recall  f1-score   support
incorrect_mask       0.97      0.95      0.96      1012
     with_mask       0.89      0.89      0.89       942
  without_mask       0.90      0.92      0.91       953

      accuracy                           0.92      2907
     macro avg       0.92      0.92      0.92      2907
  weighted avg       0.92      0.92      0.92      2907


