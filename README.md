PROJECT DESCRIPTION:

Prediction of authenticity of bank notes using K Nearest Neighbors(KNN) Algorithm.


ALGORITHM DESCRIPTION:

Imported KNeighborsClassifier module from scikit-learn library.

For more information about the module visit:https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html

Imported Standard Scaler module from scikit-learn library for feature scaling.

For more information about the module visit:https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html


DATASET INFORMATION:

Data were extracted from images that were taken from genuine and forged banknote-like specimens. For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tool were used to extract features from images.


ATTRIBUTE INFORMATION:

1. variance of Wavelet Transformed image (continuous)
2. skewness of Wavelet Transformed image (continuous)
3. curtosis of Wavelet Transformed image (continuous)
4. entropy of image (continuous)
5. class (integer)


DATASET WEBSITE:

https://archive.ics.uci.edu/ml/datasets/banknote+authentication
