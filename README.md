# Project 3

This is an **individual assignment**.

## Code Implementation & Technical Report

The final deliverables include a 4-page IEEE-format report, code implementation and a detailed GitHub readme file.

Project 2 is due Wednesday, December 7 @ 11:59 PM. Find the complete [rubric](https://ufl.instructure.com/courses/459156/assignments/5426774) in the Canvas assignment.

## Dataset 1: Flower Species Dataset

The flower species dataset is available for [download here](https://ufl.instructure.com/courses/459156/files/folder/Project%203/Dataset%201%3A%20Flower%20Species%20Classification).

## Dataset 2: Object Detection Dataset

The object detection dataset is available for [download here](https://ufl.instructure.com/courses/459156/files/folder/Project%203/Dataset%202%3A%20Object%20Detection).

## Files contained

1. training.ipynb ---- code used for training the datasets.
2. test.ipynb ---- code used for testing the datasets.
3. Project 3 - Artificial Neural Network.ipynb ---- description of project 3
4. Model ---- contains all models' weights generated from the training.ipynb. Model is too huge to update to the GitHub, there is a [link](https://drive.google.com/drive/folders/1P7yjwXsRhQl_Cu4lYlMblfAm8Cj8dDPt?usp=share_link) you can download the model weights in this project.
5. test_bounding_box.csv ---- the filenames of ten test images with labels I created
6. Project_1_report.docx ---- report in docx form
7. Project_1_report.pdf ---- report in pdf form
8. training.pdf ---- pdf form of training.ipynb
9. test.pdf ---- pdf form of test.ipynb
10. figures ---- contains the figure used in test and training set
11. README.md ---- this file.

## How to use 

Firstly, you need to download the models' weights from [here](https://drive.google.com/drive/folders/1P7yjwXsRhQl_Cu4lYlMblfAm8Cj8dDPt?usp=share_link). There are totally 4 npy files and 2 h5 files in it. File 'model_problem1_three_weights.npy' and file 'model_problem2_weights.npy' are the models' weight  of file 'model_problem1_three.h5' and file 'model_problem2.h5'. If you just need to test the model in the test.ipynb, just download these two h5 files.

I didn't upload the original dataset, so you need to download the origin data as above dataset 1 & 2 links.

Training: Training code do not need any parameters to input. It generates totally 4 models, each model is huge size. Be careful of kernal's dead when training.

Test: In test code, you need to upload file 'model_problem1_three.h5' and file 'model_problem2.h5' in order to see the performance. If you want to upload the models' weights, you need to load file 'model_problem1_three_weights.npy' and file 'model_problem2_weights.npy' and input the weights to a model by your own. For problem 3, you also need to load 'test_bounding_box.csv' which contains ten test images with labels.