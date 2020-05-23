# Gesture-Recognition
Build a model to recognize 5 hand gestures

In this group project, you are going to build a 3D Conv model that will be able to predict the 5 gestures correctly.
# Analysis :

1. There are in total 663 videos each containing 30 frames in train folder and 100 videos with 30 frames for validation.

2. Some of the videos have the dimensions 120 X 160 , whereas some are 360 X 360

3. The folder name and corresponding gesture label is stored in train.csv and val.csv files.

4. There are total 5 gestures viz. thumbs up , thumbs down , left swipe , right swipe , stop.

5. For image preprocessing , we will be doing resizing , cropping , normalization , affine transformation , image sharpening , image segmentation.
