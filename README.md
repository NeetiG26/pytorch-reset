# pytorch-reset

brew update
brew install python@3.11
brew link python@3.11 --force
OR
brew unlink python@3.11 && brew link python@3.11
brew link python@3.11 --overwrite --force


sudo ln -s /opt/homebrew/opt/python@3.11/bin/python3.11 /opt/homebrew/bin/python3
sudo ln -s /opt/homebrew/opt/python@3.11/bin/python3.11 /opt/homebrew/bin/python3.11
exec zsh
which python3
python3 --version


Virtual environment using venv

python3 -m venv .venv
source .venv/bin/activate
python --version
which python

expected:
Python 3.11.14
…/ml-project/.venv/bin/python


Pytorch Setup

pip install torch torchvision torchaudio


Setting up Weights & Biases (W&B)

pip install wandb
wandb login

Everything shows up on
👉 https://wandb.ai/your-username


Setting up Tensorboard

pip install tensorboard
tensorboard --logdir runs --port 6006


Datasets needed h5py and gdown