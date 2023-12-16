# cs370
Here is the final project for SNHU CS 370. Using a DQN, I trained an intelligent agent to find a path in a maze to the treasure.

I was given the maze matrix, as well as the moves the intelligent agent could make. The neural network model was also built for me with two
convoluted layers, using a PReLu activation function and the Adam optimizer. The 'play_game' function and the 'completion_check' function 
was also written for me. The TreasureMaze.py and GameExperience.py files were given to me. 
I was tasked with writing the algorithm used to train the model.

I created the qtrain() function that implemented a deep-Q learning algorithm that used an Epsilon-greedy method to update Q-values. While there is no
explicit Q-table being updated, the experience served as a type of Q-table that stored the history of moves made by the intelligent agent along with
their outcomes. The algorithm made use of the epsilon value to decide if the next action taken by the intelligent agent should explore or exploit experience. 

After each chosen action is taken and stored in experience, the epsilon value was updated by 5%, making sure the agent was exploiting previous experience, 
exploring only when necessary. 

Learning how to build neural networks and RL models will absolutely be necessary knowledge in my future as a computer scientist. It is our job to build 
software responsibly, ethically, and efficiently. This class explored the bias and ethics behind AI technology, and what goes into building such models. 

I approached this project as a problem to be solved. I wanted the intelligent agent to find the treasure using the most efficient strategy possible, while staying
within the limits. I believe giving us all of the code was a bit biased, and did not allow us to fully explore and have the experience of building our own model, 
but in real-world scenarios, the freedom to experiment, explore, and choose the correct model and neural network structure will be essential in solving whatever
the client's specific need or problem. I will use the knowledge gained in this course to ensure ethical procedures are followed, from the training and building of the
model, and beyond. This is my responsibility as a developer and to society. As AI continues to grow, developers must keep ethics at the forefront of innovation.
