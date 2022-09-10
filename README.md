# Introduction 
This Project is based on Reinforcement Learning which trains the snake to eat the food present in the environment.

In snake game, inputs will be the position of the snake or the head of the snake and the
position of the food, so according to these inputs our agent will apply a Q-learning model with a
neural network and give the best possible move at that particular moment.

### Algorithm
We have snake and food on the board randomly placed.
* calculate the state of the snake using the 11 values 
* Now this current state is passed to the RL Model for the next state.
* After executing the next state calculate the reward. Rewards are defined as below:
  1. Eat food  :  +10
  2. Game Over :  -10
  3. Else      :    0
* Update the Q value and Train the Model.

After analysing the algorithm now we have to build the idea to proceed for coding this algorithm.<br><br>
Our Project will be divided into three Modules named <b>Agent, Game and Model</b>
# Three Module:
1 The Environment (the game that we build) <br>
2 The Model (Reinforcement model for move prediction)<br>
3 The Agent (Intermediary between Environment and Model) <br>


