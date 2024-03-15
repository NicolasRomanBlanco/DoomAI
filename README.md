# DoomAI

## Requirements

- CUDA Toolkit 11.8 (If you don't have a graphics card or want to use the CPU (not recommended), you should download PyTorch accordingly. To download your version, go to https://pytorch.org)

- If you encounter problems while trying to install stable-baselines3, run 'pip install --upgrade pip wheel==0.38.4 setuptools==65.5.1'


## How to use

I have created 3 levels, but in the repository you are cloning, there are many more. I recommend starting with the basic one, running each cell one by one. Then move on to 'defend_the_center' and finally to 'deadly_corridor.

## Logs

To see the logs, you need to open a terminal (I use Git Bash) in the folder where you have the environment. Navigate to where you have the logs. In my case, it would be something like 'PythonVenv\jupyter_playground\Projects\Doom\logs'. You'll see a folder named PPO_X, where X represents the training number. Enter this folder and run the following command: 'tensorboard --logdir=.'
