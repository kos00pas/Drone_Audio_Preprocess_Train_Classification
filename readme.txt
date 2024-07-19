* do the labeling somehow
    -> label 0 -=> not drone
    -> label 1 -=> drone

* make the  mfccs_labels.csv that have c0: path to mfcc.csv c1: label

* make the -> save_dataset_to_h5

* make load_dataset_and_train





Data Augmentation: Consider adding data augmentation if your dataset is small to improve generalization.
Batch Normalization/Dropout: Add BatchNormalization or Dropout layers to prevent overfitting.
Early Stopping: Use EarlyStopping callback during training to prevent overfitting by monitoring validation loss.
