# CSharpAIEngine
An AI engine written in C#

## Experiment Only
This project is more about experiment and pratice rather than an actual useful AI engine, if you are looking for a proper AI engine, please consider TensorFlow, CNTK, Caffe etc.

## High Level Plan

### Layers
A list of activation function will be implemented including ReLu, Sigmoid, TanH, Dropout, MaxPooling, SoftMaxLoss, SVMLoss, Convolution, Recurrent and  LSTM etc.

### Computation Graph
Form a computation graph by using different layers, e.g. AlexNet, ResNet152 etc

### Actor
Consider to use actor pattern to do distribute computing

### Alea GPU
Consider to use Alea GPU for parallel execution to speed up training

## Phase 1
CPU only, focus on computer vision, implement ResNet152 and train Cifar10 classification with 85%+ accuracy

## Phase 1.1
Implement regression and object detection and localization with region proposal