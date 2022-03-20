# Lunar Lander Game with Deep Q-Learning (Reinforcement Learning)

## Lunar Lander Game: 
Landing pad is always at coordinates (0,0). Coordinates are the first two numbers in state vector. Reward for moving from the top of the screen to landing pad and zero speed is about 100..140 points. If lander moves away from landing pad it loses reward back. Episode finishes if the lander crashes or comes to rest, receiving additional -100 or +100 points. Each leg ground contact is +10. Firing main engine is -0.3 points each frame. Solved is 200 points. Landing outside landing pad is possible. Fuel is infinite, so an agent can learn to fly and then land on its first attempt. Four discrete actions available: do nothing, fire left orientation engine, fire main engine, fire right orientation engine.
(https://gym.openai.com/envs/LunarLander-v2/)

## Project: 
In this study, it is aimed that the rocket system will gain the ability to land on its own. The system works with trial and error rules. He gets a reward for successful cases and a penalty point for faulty cases. Deep learning network was used together with Q learning method of Reinforcement Learning. Tensorflow library was used for deep learning network.
