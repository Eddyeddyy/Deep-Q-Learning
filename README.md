# Deep-Q-Learning

In this project, we explore the Q learning method of reinforcement learning for AI systems. We were given code for a pirate treasure
hunting game that involved the player, our agent, traversing a maze, our environment, to reach its goal, our end state. The code 
had already include everything from the agent and its movement to the environment and its rules. The code that we had to desing
ourselves was the part where the reinforcement learning happens, specifically a Q learning method. With reinforcement leaning we
reward our agent for actions that will lead to winning the game, and we punish our agent for actions that cause the agent to lose
the game. With Q learning, we remember the actions and the states that our agent takes and create a table where all the actions with
the states are given a Q value. As the agent continues to play, the Q value of each state/action will get updated with the appropriate 
reward or punsihment. This Q value will eventually influence the agents choice in deciding which action to take next. If the Q value
is higher for one action/state, then the agent will choice that action more frequenlty. Eventually, the agent will learn the game well
enough to have a 100% win rate. 

As a computer scientist, we have ethical responsibilities that we must uphold. We need to make sure to ensure that any code we create
is secure and especially with AI it needs to be inclusive and unbias as possible. 
