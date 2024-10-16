# Portfolio Management Agent
Portfolio Management Agent is an autonomous wealth distribution agent. 
The project was done in the context of Reinforcement Learning course at McGill University. 

In this Work, we attempted to replicate the Ensemble of Identical Independent
Evaluators (EIIE) topology presented in A Deep Reinforcement Learning Frame-
work for the Financial Portfolio Management Problem [1] on stock data to create a
portfolio manager Reinforcement Learning agent. We compared the performance
of a Convolutional Neural Network (CNN) and a Recurrent Neural Network (RNN)
function approximators as policies in the framework. The implementation used a
Portfolio Vector Memory (PVM), an Online Stochastic Batch Learning (OSBL) ap-
proach, a stochastic gradient ascend, and a fully exploiting and explicit logarithmic
reward function. Furthermore, we considered the application of a transaction fee,
fixed at 0.25%. Contrary to the cryptocurrency dataset used by Jiang, and al., we
trained and tested our agent on the historical stock data from 1 April 2018 to 1 April
2020 on 10 pre-selected assets based on their trading popularity. We compared the
performance of our models to the average stock performance baseline. Our results
showed that the agent could beat the baseline in both cases, with the CNN function
approximator almost doubling the initial wealth. Each member of the team equally
contributed to the project since the progress was done as a group over time.

[1] Z. Jiang, D. Xu, and J. Liang, “A deep reinforcement learning framework for the financial
portfolio management problem,” 2017.
