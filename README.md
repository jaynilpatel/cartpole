# CartPole

**Problem Statement:** https://gym.openai.com/envs/CartPole-v1/

The goal is to balance a pole by moving the cart from side to side to keep the pole balanced upright using reinforcement learning algorithm. 

>**Constraints:**
>The environment is viewed as successful if we can balance for 500 frames, and failure is viewed when the pole is more than 15 degrees from >fully vertical. Every frame that we go with the pole "balanced" (less than 15 degrees from vertical), the "score" gets +1, and the target >is a score of 500. The model is trained from the scenario where the score was 50 and above.


```bash
#install dependencies

#install tflearn
pip install tflearn

#install gym
pip install gym

#install numpy
pip install numpy
