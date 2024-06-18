# Custom Handwritten Character Recognition > [Go to project](https://github.com/tophercollins/handwritten-character-recognition)

## Aim

This project was designed to use the EMNIST Dataset to create a custom model for classifying the following target characters, as well as artificially constructed characters with a strikethrough:
* TARGET_CLASSES = ['0','1','2','3','4','5','C','M','V','X']
* STRIKETHROUGH_CLASSES = ['0_s','1_s','2_s','3_s','4_s','5_s','V_s']

## Data

The EMNIST data can be found at [EMNIST](https://www.tensorflow.org/datasets/catalog/emnist) and was imported the TFDS API.

## Process

* Loaded data through the TFDS API using builder.as_data_source() as data is in ArrayDataSource format.
* Filtered data by Target Classes and creates Strikethrough Classes.
* Prepared Data for training including normalizing images and one hot encoding labels.
* Viewed samples to verify clean data.
* Create a baseline model and performed a series of experiments, including Batch Normalization, Dropout, and adding complexity to avoids overfitting.
* Used Data Augmentation on final model to mimic real world data.
* Produced a final model based on experiments and tested on data.

## Conclusion

We successfully created a model which predicted a class with 99.5% accuracy.
