# Face-Landmark-Detection

# **Introduction**

Face Detection Systems have great uses in today’s world which demands security, accessibility or joy! Today, we will be building a model that can plot 15 key points on a face.

Face Landmark Detection models form various features we see in social media apps. The face filters you find on Instagram are a common use case. The algorithm aligns the mask on the image keeping the face landmarks as base points.

Facial landmark detection has been studied over decades. Numerous neural network (NN)-based approaches have been proposed for detecting landmarks, especially the convolutional neural network (CNN)-based approaches. In general, CNN-based approaches can be divided into regression and heatmap approaches. However, no research systematically studies the characteristics of different approaches. In this paper, we investigate both CNN-based approaches, generalize their advantages and disadvantages, and introduce a variation of the heatmap approach, a pixel-wise classification (PWC) model. To the best of our knowledge, using the PWC model to detect facial landmarks have not been comprehensively studied. We further design a hybrid loss function and a discrimination network for strengthening the landmarks' interrelationship implied in the PWC model to improve the detection accuracy without modifying the original model architecture. Six common facial landmark datasets, AFW, Helen, LFPW, 300-W, IBUG, and COFW are adopted to train or evaluate our model. A comprehensive evaluation is conducted and the result shows that the proposed model outperforms other models in all tested datasets.

![](https://miro.medium.com/max/2000/1*qNNr1hrFoaeAWru7VI0SbQ.png)

# **Table of Contents**
1.Introduction

2.Approach to the problem statement

3.Data loading and Preprocessing

4.Model building

5.Model training

6.Evaluation

Dataset : 

Notebook on Kaggle : 
