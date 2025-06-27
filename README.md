# UCR_Time_Series_Classification_Deep_Learning_From_Scratch
This repository is the implementation of "Time Series Classification from Scratch with Deep Neural Netwroks: A Strong Baseline" - research paper!

The paper is implementing three deep neural networks namely:
1. Multi Layers Perceptron (MLP)
2. Fully Connected Convolutional Neural Network (FCN)
3. Residual Network (ResNet)

The main objective of the research paper is that this three simple neural networks are getting good results without using any cross validation or any feature engineering and data preprocessing. They are evaluated through a pure end-to-end training on the raw time series data, the ResNet and FCN acheive comparable or better performance than COTE and MCNN. The global average pooling in convolutional model enables the exploitation of the Class Activation Map (CAM) to find out the contributing region in the raw data for the specific labels.

The structure of the neural networks is given in the below image: 
![image](https://github.com/user-attachments/assets/57c88375-292e-466e-ab73-e4770149d046)

The code refrence is taken from the official research paper's code. The only thing is that they implemented the neural networks using Keras whereas, I have implemented it using PyTorch which I learnt to do from Stat Quest's guide to Neural Networks and AI :). Please checkout the code!
