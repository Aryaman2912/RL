## Cliff Walking

The environment consists of a 4x12 gridworld. Reward is -1 on all transitions except those into the region marked "The Cliff". Stepping into this region results in a reward of -100 and sends the agent instantly back to the start. The below figure gives a better idea.
![](https://miro.medium.com/max/3000/1*52MwrYKyzQXuKZ88rqu70A.png)
The notebook contains the implementation of Q learning for the above environment and also a comparision with Sarsa.
