# Eigenfaces

Eigenfaces is a method that is useful for face recognition and detection by determining the variance of faces in a collection of face images and use those variances to encode and decode a face in a machine learning way without the full information reducing computation and space complexity.

The basic idea behind eigenfaces is to represent an image of a face as a linear combination of a set of "eigenfaces" (also known as "principal components"). These eigenfaces are derived from a dataset of training images of faces by performing a technique called principal component analysis (PCA). PCA is a method for reducing the dimensionality of a dataset, and in the case of eigenfaces, it is used to find the most important features of a face that can be used for recognition.

Once the eigenfaces have been derived from the training dataset, they can be used to represent a new image of a face. To do this, the new image is projected onto the space defined by the eigenfaces, and the coefficients of this projection are used as a feature vector for the face. This feature vector can then be compared to the feature vectors of the training images to find the closest match.

Eigenfaces have been used in a wide range of applications, including face recognition, facial expression recognition, and face verification. However, it has been surpassed by more advanced methods like deep learning based face recognition models.
