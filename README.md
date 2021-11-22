# Handwritten-Mathematical-Expression-Recognition (Pytorch)



  
This program uses Attention and Coverage to realize **HMER** (HandWritten Mathematical Expression Recognition)


# Requirements

	Python 3.7 and above
	Pytorch == 1.8.2 and above check you compatibility with Cuda 10.2
	

# Training and Testing
1. Install Requirements and pretrained Densenet weights can be download [here](https://download.pytorch.org/models/densenet121-a639ec97.pth))  .
2. Decompression files in **off\_image\_train** and **off\_image\_test**, and this will be your training data and testing data. 
3. python **'gen_pkl.py'**. This python file will compress your training pictures or testing pictures into a **'.pkl'** file. Moreover, you should write the correct location of your data files. 
4. python **'Train.py'** for training.
5. python **'Densenet_testway.py'** for testing.  
6. Open the source code of **HMER V2.0**. You can see detials in HMER_v2.0. 

# Experiment
+ This model is testing in CROHME 2016 dataset. All of my experiments are running in two TITAN XP GPUs. The batch_size is 6, the max len is 48 and the max Image size is 100000.  

+ The best result of this model is: 

+ > WER loss: **17.160%**  
 ExpRate: **38.595%**  


