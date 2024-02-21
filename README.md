# DinoRL
Deep Reinforcement Learning (DQN) with Chrome Dino Game

Inspired by Nicholas Renotte's Reinforcement Learning Course (https://www.youtube.com/watch?v=dWmJ5CXSKdw), I trained the model for 880,000 frames (approximately 5 hours), and the highest score my dino achieved is 476.

<img width="1462" alt="image" src="https://github.com/SuqingLiu/DinoRL/assets/66585292/ccf4a3bc-098c-41c0-98f9-4d3def0e8fd3">


Below are some training metrics (DQN_2 is the model trained for the longest duration, while DQN_1 was paused after a few rounds).

<img width="1021" alt="image" src="https://github.com/SuqingLiu/DinoRL/assets/66585292/c7348847-bbfc-45ba-b1e7-8c5831cf18ef">


<img width="497" alt="image" src="https://github.com/SuqingLiu/DinoRL/assets/66585292/1d11dba9-6c04-4e53-b546-a7ad027d5c9e">


I learned to use OpenAI's Gym to customize an environment setting for training reinforcement models, and I learned the Deep Q Network method.

The current model is not performing as well as expected, and I believe this is due to the increasing speed of the dino as the score gets higher. DQN may not be the best fit for this type of unstructured environment.

I will now explore other web games to see which one best fits the implementation of DQN and aim to achieve a higher score.
