# Trajectory-tracking-to-avoid-accidents

# Problem Statement
The goal is to reduce accidents on highways by making sure that the vehicle follows a particular trajectory.

# Possible and final Solution
For developing an efficient trajectory tracking and planning system for autonomous vehicles, explored different methods 
like RL with Double DQN, Deep Neural networks(DNN), Recurrent neural Networks(RNN), Long Short-Term Memory(LSTM).The final design 
is a machine learning model based on LSTMs. The LSTM network architecture comprises an input layer, several LSTM layers, and an output layer. 
LSTM network uses multiple LSTM layers for better feature extraction. 

Developed a story board in the process of concluding to the final solution.

# Dataset
Firstly, the dataset has been obtained from an interaction dataset which contains naturalistic motions of various traffic participants in a variety of 
highly interactive driving scenarios from different countries. But we have chosen dataset of a highway environment which was our problem space. This dataset 
contained information about the agents, including their positions, velocities, yaw angle with the length and width of the vehicles. The primary goal is to 
predict the trajectory of a specific agent called the "ego agent." The ego agent is identified by selecting an interesting agent (e.g., representing the vehicle we want to predict the trajectory for). 


