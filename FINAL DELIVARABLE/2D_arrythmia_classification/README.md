# ECG Image Based Heartbeat Classification for Arrhythmia Detection 
 
 ECG- Image Based Heartbeat Classification For Arrhythmia Detection 


Designed By:

Deepanshu Saini


1. Introduction

1.1 Overview
According to the World Health Organization (WHO), cardiovascular diseases (CVDs) are the number one cause of death today. Over 17.7 million people died from CVDs in the year 2017 all over the world which is about 31% of all deaths, and over 75% of these deaths occur in low and middle-income countries. Arrhythmia is a representative type of CVD that refers to any irregular change from the normal heart rhythms. There are several types of arrhythmia including atrial fibrillation, premature contraction, ventricular fibrillation, and tachycardia. Although a single arrhythmia heartbeat may not have a serious impact on life, continuous arrhythmia beats can result in fatal circumstances. In this project, we build an effective electrocardiogram (ECG) arrhythmia classification method using a convolutional neural network (CNN), in which we classify ECG into seven categories, one being normal and the other six being different types of arrhythmia using deep two-dimensional CNN with grayscale ECG images. We are creating a web application where the user selects the image which is to be classified. 

1.2 Purpose
An electrocardiogram (ECG) measures the electric activity of the heart and has been widely used for detecting heart diseases due to its simplicity and non-invasive nature. By analyzing the electrical signal of each heartbeat, i.e., the combination of action impulse waveforms produced by different specialized cardiac tissues found in the heart, it is possible to detect some of its abnormalities. 

2. Literature Survey

2.1 Existing Problem
Cardiovascular diseases (CVDs) are the number one cause of death today. Over 17.7 million people died from CVDs in the year 2017 all over the world which is about 31% of all deaths, and over 75% of these deaths occur in low and middle-income countries. Arrhythmia is a representative type of CVD that refers to any irregular change from the normal heart rhythms. There are several types of arrhythmia including atrial fibrillation, premature contraction, ventricular fibrillation, and tachycardia.

2.2 Proposed Solution
An "ambulatory electrocardiogram" or an ECG) about the size of a postcard or digital camera that you'll use for 1 to 2 days, or up to 2 weeks. The test measures the movement of electrical signals or waves through your heart. These signals tell the heart to contract (squeeze) and pump blood.  You'll have electrodes taped to your skin. It's painless, although some people have mild skin irritation from the tape used to attach the electrodes to the chest. You can do everything but shower or bathe while wearing the electrodes. After the test period, you'll go back to see your doctor. They'll download the information.

3. Theoritical Analysis

3.1 Block Diagram

3.2 Hardware/Software Designing
The Training model is created using Convolutional Neural Networks (Machine Learning) and Computer Vision and the Interface is created in Flask using IBM Watson AI.

4. Experimental Investigation

In this project, we have deployed our training model using CNN on IBM Watson studio. We are deploying 4 types of CNN layers in a sequential manner , starting from :
1) Convolutional layer 2D which convolutes independently of the feature map of the previous layer. The output of the convolution layer is obtained by offsetting the convolution kernel and transferring it to the nonlinear activation function.

2) Pooling Layer  Convolution of the next layer is commonly the pooling layer. By reducing the dimension of convolution layer output data, network complexity is reduced, as well as overfitting phenomenon. Robustness of the network is enhanced in this process. The pooling layer averages or maximizes the output features of the convolutional layer, and the corresponding methods are respectively, average pooling or maximum pooling.

3) Fully-Connected layer After extracting features from multiple convolution layers and pooling layers, the fully-connected layer is used to expand the connection of all features. Finally, the SoftMax layer makes a logistic regression classification. Fully-connected layer transfers the weighted sum of the output of the previous layer to the activation function.

4) Dropout Layer There is usually a dropout layer before the fully-connected layer. The dropout layer will temporarily disconnect some neurons from the network according to the certain probability during the training of the convolution neural network, which reduces the joint adaptability between neuron nodes, reduces overfitting, and enhances the generalization ability of the network.
5.FlowChart




6. Result
	

7. Advantages & Disadvantages
7.1 Advantages
●  The proposed model predicts Arrhythmia in images with a high accuracy rate of  90.54%

●  The early detection of Arrhythmia gives better understanding of disease causes, initiates therapeutic interventions and enables developing appropriate treatments.

7.2 Disadvantages

●  Do not identify the different stages of Arrhythmia disease.

●  Do not monitor for motor symptoms.

8. Applications
●  Used to detect arrhythmia at an early stage.
●  Used to detect cardiovascular disorders.

9. Conclusion
Cardiovascular disease is a major health problem in today's world. The early diagnosis of cardiac arrhythmia highly relies on the ECG. Unfortunately, the expert level of medical resources is rare, visually identify the ECG signal is challenging and time-consuming.
The advantages of the proposed CNN network have been put to evidence. It is endowed with an ability to effectively process the non-filtered dataset with its potential anti-noise features. Besides that, ten-fold cross-validation is implemented in this work to further demonstrate the robustness of the network.

10. Future Scope
As for future work, it would be interesting to explore the use of optimization techniques to find a feasible design and solution. The limitation of our study is that we have yet to apply any optimization techniques to optimize the model parameters and we believe that with the implementation of the optimization, it will be able to further elevate the performance of the proposed solution to the next level.

11. Biblograpghy
1) https://www.frontiersin.org/articles/10.3389/fncom.2020.564015/full
2) https://www.sciencedirect.com/science/article/pii/S0169260715003314
12. Appendix
https://github.com/smartinternz02/SI-GuidedProject-7201-1640667598
