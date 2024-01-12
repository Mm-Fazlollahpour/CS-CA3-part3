# CS-CA3-part3
in this repository, we intend to become familiar with concepts of quantization, distribution functions between correlated and uncorrelated variables, as well as random processes, over the course of a series of processes, through conceptual questions and more advanced simulations.
The purpose of performing this exercise is to review engineering statistics and probability, study stationary random processes (WSS), and pulse modulation. At the beginning of the work and in the first section, we will have a brief overview of normal random variables, conditional probabilities, and correlations. In the second section, we will examine stationary random processes and plot their autocorrelation function in two dimensions to demonstrate their independence from time. Finally, in the concluding section, we will also become familiar with pulse modulation and attempt to implement a digital transmitter and receiver with decoding in the presence of noise.

The completed sections of the project are as follows: (CA4_Matlab_810198369.mlx)

1- Probability and Statistics

2- Random Processes: "Review of Stationary Stochastic Processes (WSS)"

3- Quantization

3-a. Definition of continuous signal and sampling, and construction of discrete signals.
following picture illustrates the continuous time graph :
![1](https://github.com/Mm-Fazlollahpour/CS-CA3-part3/assets/156366692/be4e274c-df40-40cb-9bba-9488832caa35)

now we take samples from the continuous time graph and discrete time graph below will be concluded :

![2](https://github.com/Mm-Fazlollahpour/CS-CA3-part3/assets/156366692/37a748b0-324a-485f-96ce-1661eda4d5ca)

3-b. Quantization Level Implementation.
in this part we map the discrete time graph on quantized levels, which we defined before and here is the rsult:

![3](https://github.com/Mm-Fazlollahpour/CS-CA3-part3/assets/156366692/ef605268-4eb9-4e02-8fb5-de7d7c4c849f)

3-c. Digital conversion of quantized signals.
in this part we have a sample signal which is triangular :

![4](https://github.com/Mm-Fazlollahpour/CS-CA3-part3/assets/156366692/1223e60b-8110-4f96-b0b3-597d2ee6b056)

now we make a set which is made of graphs having different amplitudes and that is encoded message:

![5](https://github.com/Mm-Fazlollahpour/CS-CA3-part3/assets/156366692/e23bc8b7-fc2c-4f46-adae-f6e9f8a6faf6)

3-d. Reception of digital signal at the receiver.
in this part we add noise to the encoded signal
following signal is recieved at the reciever :

![6](https://github.com/Mm-Fazlollahpour/CS-CA3-part3/assets/156366692/37b0b3ec-db76-4a18-91ca-98b9500c168b)

3-e. Decoding of the digital signal at the receiver.
now we have to decode the recieved signal by using some relations and base signal power 
and finally here is the final result of decoded signal :

![9](https://github.com/Mm-Fazlollahpour/CS-CA3-part3/assets/156366692/1927c241-9591-4098-ac79-5880e6628b10)

it is obvious that decoded message is as same as the quantized signal we had at first with low error rate!!


