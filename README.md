# Swimmer-PPO
Solving the Swimmer openai gym environment with PPO.

author: Petr Zelina


Main file is the `Zelina_Swimmer.ipynb`, which contains the trainig, testing and explanations.

`swimmer.mp4` is a video with the best policy I was able to achieve.

The `best_checkpoints` directory contains 3 best checkpoints from three different trainings.

The `selected_runs` directory contains tensorboard logs for these three runs. You can view the with
```
tensorboard serve --logdir selected_runs/
```
