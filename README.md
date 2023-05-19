# face_mask_detector
## Introduction
Real time face-mask detection using Deep Learning and OpenCV

This project uses a Convolutional Neural Network, to classify between images of people with and without mask. The CNN manages to get an accuracy of 96.88% on the test set. Then the stored weights of this CNN are used to classify as mask or no mask, in real time, using OpenCV. With the webcam capturing the video, the frames are preprocessed and fed to the model to detect that Mask is worn or not. Can detect Multiple faces as well.

## Dataset
Kaggle dataset: https://www.kaggle.com/ashishjangra27/face-mask-12k-images-dataset
This dataset has: 10K train images(5K with Mask and 5K without mask) & 992 test images(483 with Mask and 509 without Mask)

## Sample Output file
![Sample Output]()
