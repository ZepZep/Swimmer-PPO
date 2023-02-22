# Swimmer-PPO
Solving the Swimmer openai gym environment with PPO.

author: Petr Zelina

![swimmer](https://user-images.githubusercontent.com/15908442/220720112-5ce83b92-b277-476e-9af6-72b5f3d1d879.gif)

Main file is the `Zelina_Swimmer.ipynb`, which contains the trainig, testing and explanations.

`swimmer.mp4` is a video with the best policy I was able to achieve.

The `best_checkpoints` directory contains 3 best checkpoints from three different trainings.

The `selected_runs` directory contains tensorboard logs for these three runs. You can view the with
```
tensorboard serve --logdir selected_runs/
```
