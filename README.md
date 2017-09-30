# Face_keypoint_detection_CNN

Besides the conventional algorithms for detecting 128 or 68 facial keypoints, CNN's can also be used in predicting these facial keypoints on a human face. The major challenge in making a CNN predict the keypoints, is that the MaxPool layer which picks out the maximum value from the given kernel size leads to loss of information. Another challenge is of overfitting. While training on the dataset, the network has to learn predicting co-ordinates that are quite similar. Last concern is that CNN's are always better in classification task rather than prediction task.
The dataset contains co-ordinates of 30 facial keypoints for images. The CNN model which is coded tries to learn those keypoints and predicts them for other images.
The dataset was taken from a competition on kaggle whose link is given below,
https://www.kaggle.com/c/facial-keypoints-detection/data
