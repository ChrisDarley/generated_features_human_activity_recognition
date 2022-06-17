# generated_features_human_activity_recognition

The data is from the UCI machine learning repository. The dataset used is human activity recognition using smartphones.
https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones

The data used for this notebook is a set of engineered features generated for each 128 timestep portion of activity.
Using linear discriminant analysis, accuracy greater than 96% can be achieved when predicting the activity being performed.

This notebook and the accuracy achieved is meant to be a benchmark of success for the cnn based model found here:
https://github.com/ChrisDarley/cnn_activity_recognition.  I am attempting to see how closesly I can approximate the accuracy of lda on the generated features by using cnn architecture on the raw accelerometer and gyroscope data.
