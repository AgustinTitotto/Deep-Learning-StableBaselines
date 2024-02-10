"# Deep-Learning-StableBaselines" 

Steps

1 - First install anaconda
2 - Create enviroment with python 3.8 --> conda create --name <enviroment_name> python=3.8
2 - Activate enviroment --> conda activate <enviroment_name>
3 - Install GPU support if neccessary (check pythorch documentation) --> conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia 
4 - Install Stable-Baselines3 --> pip install stable-baselines3[extra]


Conda commands

conda clean -all 
conda env remove --name deep-learning
conda env list
