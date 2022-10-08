# ReinforcementLearning

The emergence of self-driving cars has brought what were previously ideas from science function into reality. For example, the RoboRace series (www.roborace.com) is a race series for a self-driving car platform. In this project I will train a simple selef-driving racing car OpenAI Gym Racing environment (https://gym.openai.com/envs/CarRacing-v0/). The player's job is to control a small racing car on a simple track.

There are five discrete **actions** in this environment:
- left (0)
- right (1)
- brake (2)
- accelerate (3)
- none (4)

**Reward** of -0.1 is awarded every frame and +1000/N for every track tile visited, where N is the total number of tiles in track. For example, if you have finished in 732 frames, your reward is 1000 - 0.1*732 = 926.8 points.

And the **state** is represented using a single image frame (96 * 96).
