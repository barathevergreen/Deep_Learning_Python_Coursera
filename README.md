__Deep Learning Specialization: Coursera - Andrew Ng__

__Neural Networks and Deep Learning:__

1.Logistic Regression with a Neural Network mindset - building an image recognizing algorithm for cat/non cat binary classifier from scratch
  - Reshape dimensions
  - Standardization
  - Compute Cost, Update Parameters using GD, predict W and b
  - Prediction
  - Learning rates analysis

2.Neural Network with one hidden layer on a Linearly Non Seperable dataset
- compare and contrast with Logistic regression
- test for additional layers - Impact of overfitting

3.Deep Neural Network - 2 Layers and L Layers:
- Use of ReLU for hidden layers and Sigmoid for output layer
- Linear Forward, Activation Forward, Cost Function (Store necessary values in cache)
- Backward Prop - Sigmoid, Relus, INput -- get gradients with respect to cost
- Update Parameters to get Weights and Bias using Grad Descent
- Predictions
- Learning Rates analysis - Early stopping
- Analysis of mislabelled images - Identify failure pattern

__Regularization and Optimization__

4.Initialisation
- Zero,Random and He initialisations
- L2 Regularization
- Dropout - inverted dropout. Divide A[L] and dA[L]/Keep_prob
- Gradient checking - 1 hidden layer, Multi layer

5.Optimization: 
- Gradient descent
- Mini Batch Gradient Descent
- Momentum
- Adam
- Comparison and best case analysis

__Frameworks - TensorFlow:__

6.Deciphering of Finger Signs -- to detect number from hand language between 0 to 5
- Basics and Methods
- Forward Prop, Cost
- Using Placeholders and Update Parameters using Adam Optimizer

__CNN and RNN:__

7.Convolutional Neural Networks:
- Building CNN from scratch using numpy
- ConvNet implementation using TensorFlow -- Multiclass classification using finger signs
- ResNets - Deep Neural Networks 50 Layers implementation using Keras using finger signs
- YOLO model - Traffic Image detection system for anomalous driving using Keras and Tensorflow backend
- Using VGG-19 as a pretrained model, creating a Neural style algorithm using TensorFlow
		calculate Total cost from Content cost and style cost
		create a NST image from content and style images
- (Ideas from FaceNet)Using ConvNet pretrained model, implement a face verification and face detection algorithm using keras and tensorflow
		using convNet to compute 128D encodings - architecture from inception model
		triplet loss function
		face verification and face detection from given images

8.Recurrent Neural Nets:
- RNN Step by step
- Word Embeddings
- Sequence to sequence architecture
- Attention models
