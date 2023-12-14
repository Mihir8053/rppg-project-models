# Contactless-Heartrate-Estimation
Contactless Heartrate estimation using Hybrid Deep Learning architectures.

## Installation
1. Install conda from https://docs.conda.io/projects/conda/en/latest/user-guide/install/windows.html
2. Install CUDA and cuDNN from NVIDIA's website.
3. Open anaconda terminal and run `conda create -n rppg python=3.8 pytorch=1.12.1 torchvision=0.13.1 torchaudio=0.12.1 cudatoolkit=10.2 -c pytorch -q -y`
4. move into the repo directory `cd Contactless-Heartrate-Estimation`
5. `conda activate rppg`
6. `pip install -r requirements.txt`
7. `git clone https://github.com/fbcotter/pytorch_wavelets`
8. `cd pytorch_wavelets`
9. `pip install .`


## Usage
1. Now do the changes in the config file `UBFC-rPPG.yaml`.
2. `python main.py`
