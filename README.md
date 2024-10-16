# 📊 Portfolio Management Agent

This project is an autonomous wealth distribution agent developed as part of the **Reinforcement Learning course at McGill University**.

We aimed to replicate the **Ensemble of Identical Independent Evaluators (EIIE)** topology presented in the paper *"A Deep Reinforcement Learning Framework for the Financial Portfolio Management Problem"* [1]. The agent was trained on stock market data to create a portfolio management system using **Reinforcement Learning**.

## Key Features:
- We compared the performance of two function approximators: a **Convolutional Neural Network (CNN)** and a **Recurrent Neural Network (RNN)**.
- The implementation includes:
  - **Portfolio Vector Memory (PVM)**
  - **Online Stochastic Batch Learning (OSBL)**
  - **Stochastic Gradient Ascent**
  - An explicit **logarithmic reward function**
  - A **transaction fee** of 0.25%

## Dataset and Evaluation:
Unlike the original paper, which used cryptocurrency data, we used **historical stock data** [2] from April 1, 2018, to April 1, 2020. Our model was trained and tested on 10 pre-selected assets based on trading popularity. We compared the agent's performance to an average stock performance baseline.

## Results:
- Both the CNN and RNN-based agents outperformed the baseline.
- The **CNN model** nearly doubled the initial wealth, showing superior performance compared to the RNN.

This project was a collaborative effort, with each team member contributing equally over time.

## References:
[1] Z. Jiang, D. Xu, and J. Liang, “A deep reinforcement learning framework for the financial portfolio management problem,” 2017.  
[2] O. Onyschak, “Stock market dataset,” 2020. Available: [Kaggle Stock Market Dataset](https://www.kaggle.com/datasets/jacksoncrow/stock-market-dataset)
