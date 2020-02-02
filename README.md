# Q-Deep-Learning mini-project
This is a mini-project on Deep Reinforcement Learning from the Deep Learning course of the master **MVA** by **Vincent Lepetit**. A large part of the ipython notebook code is written by him.<br><br>

### Game context:
A rat runs on an island and tries to eat as much as possible. The island is subdivided into $N\times N$ cells, in which there are cheese (+0.5) and poisonous cells (-1). The rat has a visibility of 2 cells (thus it can see $5^2$ cells). The rat is given a time $T$ to accumulate as much food as possible. It can perform 4 actions: going up, down, left, right.<br><br>

### Objectif:
Implement a QDL(Q-Deep Learning) solution to solve the problem above by maximizing the Q-value function of the agent(rat).<br><br>

### Demo:
The video **game_demo.mp4** is a demo of a game after training.<br>
The grid represents the island where the rat is colored **white**, the bonus cells **red** and the poisonous cells **blue**.
