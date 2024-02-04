"# Deep-Learning-StableBaselines" 

Conda commands

conda clean -all 
conda env remove --name deep-learning
conda env list


Steps

1 - Create enviroment --> conda create --name deep-learning python=3.8
2 - Activate enviroment --> conda activate deep-learning
3 - Install GPU support --> conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia 
4 - Install Stable-Baselines3 --> pip install stable-baselines3[extra]

