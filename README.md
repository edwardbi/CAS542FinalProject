# CAS542FinalProject
The final project code for CAS 542, Machine Learning class at BU

## Project Title
Efficient Deep Learning Structure and Training Method for Human Activity Recognition

## Project Description
This project is based on the UCI dataset Human Activity Recognition Using Smartphone Dataset (https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones) and enlighted by the work of Guillaume Chevalier (https://github.com/guillaume-chevalier/LSTM-Human-Activity-Recognition). The goal of this project is to predict the 6 categories of human activities (walking, walking up, walking down, sitting, standing and laying) from data generated from the accelerator and gyroscope of a mobile device that is attached to the waist of the volunteers. The experiment is done with 30 volunteers and a video clips has been provided below to show these activities:
<p align="center">
  <a href="http://www.youtube.com/watch?feature=player_embedded&v=XOEN9W05_4A
" target="_blank"><img src="http://img.youtube.com/vi/XOEN9W05_4A/0.jpg" 
alt="Video of the experiment" width="400" height="300" border="10" /></a>
  <a href="https://youtu.be/XOEN9W05_4A"><center>[Watch video]</center></a>
</p>
Our goal in this project is to find a faster running model than the LSTM model of Guillaume Chevalier. In addition, the model should be like the one proposed by Guillaume Chevalier as we would like the model to learn from no or minimal handcrafted features. In addition, we seek to improve the accruacy of the model to reach the 96% classification result of the MC-SVM proposed in the orignal work of Davide Anguita et al (2013) on the handcrafted features.

## System Specifications
We are using Tensorflow version 1.0 and Python version 3.6 in this project. And the running results are based on an Acer machine with intel core i5-8250U 1.6GHz with Turbo Boost up to 3.4GHz CPU. The DDR memory is 12GB.

## File Content Description
There are four Jupyter notebook files in this project. The End to End LSTM Model 1, End to End CNN Model 2 and the End to End CNN LSTM Model 3 are the two experiment results of the three models training under the end-to-end training method. The Feature Extractorion Training file refer to the experiments performed when using the CNN or the CNN LSTM model as the feature extrator training method.


