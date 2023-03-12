# Bag of Visual Words (BoVW) Model
# Introduction
BoVW is a commonly used technique in image classification. The idea behind this technique, is similar to the bag of words in NLP but in this technique we use image features as words. In Computer Vision, the same concept is used in the bag of visual words. Here instead of taking the word from the text, image patches and their feature vectors are extracted from the image into a bag. Features vector is nothing but a unique pattern that we can find in an image. To put it simply, Bag of Visual Word is nothing but representing an image as a collection of unordered image patches, as shown in the below illustration.
The following steps can be followed for implementation:
1. Extract local features from several images using SIFT.
2. Quantize the feature space. Make this operation via clustering algorithms such as K-means. The center points, that we get from the clustering algorithm, are our visual words.
3. Extract local features and compare these features with visual words to create histograms for each image both for the test and train dataset.
4. Predict the class of test images comparing with each histogram of train images.
5. Calculate the accuracy.

<p align="center">
  <img src="https://user-images.githubusercontent.com/127694899/224573613-28ea3e95-14e0-4c83-9630-e4a90937b002.png" />
</p>

# Environment Setup
The setup can be done through the following methods:
1. scipy
2. scikit-image
3. opencv
4. matplotlib

# Train and test data
The train and test data are images obtained from an object dataset.

# Quantitative results 
