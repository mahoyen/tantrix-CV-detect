# tantrix-CV-detect

This repository has the code to create networks that use the dataset created in [this repository](https://github.com/mahoyen/tantrix-detect-dataset-generation).

Here I have tried multiple methods. I tried the library [mindsdb](https://www.mindsdb.com/) without any success.
Next I made my own convolutional neural network, in [computervision-self.ipynb](https://github.com/mahoyen/tantrix-CV-detect/blob/master/computervision-self.ipynb).
First with keypoint detection on all the colours, but later changed to bounding boxes of the entire tile by taking the min max of the keypoints.
