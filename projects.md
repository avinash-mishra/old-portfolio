---
layout: page
permalink: /projects/
---

-**I don't update this page as much, so head to my GitHub for the most recent projects**

iPython Tensorflow Notebook Tutorials
====================
![](/assets/tf.jpg) 

<a href="https://github.com/adeshpande3/Tensorflow-Programs-and-Tutorials" target="_blank">**Tensorflow Programs and Tutorials**</a> - This Github repo contains multiple iPython notebooks which serve as tutorials for learning about deploying deep learning and machine learning models. The following topics are covered. 
- **Convolutional Neural Networks**: This notebook shows you how to define a simple convolutional network using Tensorflow. We'll discuss how to load in datasets, how to create our network architecture using Tensorflow variables, as well as how to define loss functions and optimizers. 
- **Generative Adversarial Networks**: This notebook shows you how to create a simple GAN. The basic idea is that you have 2 different networks, a generator network and a discriminator network. The discriminative model has the task of determining whether a given image looks natural (an image from the dataset) or looks like it has been artificially created. The task of the generator is to create natural looking images that are similar to the original data distribution. In this tutorial, we'll look at how to create both models, and the unique process of training them to reach a Nash equilibrium. 
- **CNN's with Noisy Labels**: This notebook looks at a recent [paper](https://arxiv.org/pdf/1703.08774.pdf) that discusses how convolutional neural networks that are trained on random labels (with some probability) are still able to acheive good accuracy on MNIST. I thought that the paper showed some eye-brow raising results, so I went ahead and tried it out for myself. It was pretty amazing to see that even when training a CNN with random labels 50% of the time, and the correct labels the other 50% of the time, the network was still able to get a 90+% accuracy. 
- **And more!**

Hackathons
====================
![](/assets/chiro.png) 

<a href="https://github.com/NWChen/Chiro" target="_blank">**Chiro**</a> *Qualcomm HackMobile 2017* - Created a tool that detects and corrects your posture while sitting at a desk. We used convolutional neural networks for the binary classification problem of whether or not a person currently has good or bad posture. We gathered a large dataset of images, and used transfer learning to fine tune a pretrained Inception network. We created a camera streaming web app that sent raw RGB photos to a webserver which passed the image through a saved Keras CNN model, and rendered the results to a single page web app that alerts you when bad posture is detected. 

Sports Data Analysis
====================
![](/assets/sports.jpg) 

<a href="https://github.com/adeshpande3/March-Madness-2017/blob/master/March%20Madness%202017.ipynb" target="_blank">**March Madness 2017 Bracket Predictor Model**</a> - This iPython notebook looks at how we can use historical data on NCAA regular season games to develop a model that outputs win probability for 2 given teams facing each other. We can frame this as a supervised learning problem where we can use past game by game results as our labels. Each team is represented by a d-dimensional vector containing information for that team (PPG, Number of Wins, etc) during the given season. The element wise difference between the two teams is inputted into a neural network, where the output is the softmax-bounded probability of the likelihood that Team 1 will come out victorious in the matchup. I also wrote a <a href="https://adeshpande3.github.io/adeshpande3.github.io/Applying-Machine-Learning-to-March-Madness" target="_blank">blog post</a> about predicting the 2017 March Madness tournament. 
<br><br><a href="https://github.com/adeshpande3/MLB_Win_Predictor/blob/master/BaseballWinPredictor.lua" target="_blank">**MLB Win Predictor Linear Regression Model**</a> - This project looks at how a team's baseball statistics (ERA, Batting Average, RBI, etc), over the course of a season, contribute to their total number of wins. This uses the Torch7 computing framework to develop a linear regression model that takes in a set of 16 features representing traditional baseball statistics and outputs the predicted number of wins for the given season. Given the season statistics for a team, this model can predict a team's win total within 3 games (1.85% error). 

React Web Apps
====================
![](/assets/react.png) 

<a href="https://mlb-stats-app.herokuapp.com/" target="_blank">**MLB Stats App**</a> - First web application using the React JS framework. Have been hearing a lot of good things about it, so I wanted to give it a shot. This app is pretty simple. It just displays the 2016 regular season stats for each MLB team. Looking to add more functionality and iron out a few of the bugs a little later. 

Kaggle Competitions
====================
![](/assets/kaggle.jpg) 

<a href="https://github.com/adeshpande3/KaggleTitanic" target="_blank">**Kaggle Titanic**</a> - The Kaggle Titanic competition revolved around taking in a dataset of all the passengers in the Titanic, and then predicting whether or not they survived. The features in the dataset included room location, age, gender, etc. For this competition, I used a variety of different supervised learning approaches (SVMs, KNNs, Decision Trees, Neural Networks), but ultimately found that a KNN model (where K = 17) got the best accuracy of 78.95%. I used Numpy and Sklearn to help preprocess the data and create the models. 
<br><br><a href="https://github.com/adeshpande3/Kaggle-MNIST" target="_blank">**Kaggle MNIST**</a> - The Kaggle MNIST competiiton is a quite standard benchmark for all computer vision models. MNIST is a dataset of handwritten digits, and the overall goal is to have the model classify each image as a digit from 0-9. For this competition, I used a convolutional neural network written in Keras. The model gets an accuracy of 98.63%.
<br><br><a href="https://github.com/adeshpande3/KaggleGhosts" target="_blank">**Kaggle Ghosts**</a> - This playground competition was a little different in that it involved a "fake" dataset and task. The goal was to take in features of different fantasy monsters (Ghoust, Ghool, or Goblin), and output the most likely classification. Some of the features included hair length, bone length and color. An SVM proved to work the best as I was able to achieve a 73.54% accuracy. I used Numpy, Pandas, and Matplotlib to help visualize the data and features. 

Other Tutorials
====================

<a href="https://github.com/adeshpande3/Pandas-Tutorial/blob/master/Pandas%20Tutorial.ipynb" target="_blank">**Pandas Tutorial**</a> - Pandas is the one of the most popular Python libraries as it can be lots for a variety of different data sience tasks. From describing data structures to introducing the most important functions, this tutorial is a great starting point for anyone looking to start using Pandas. 
