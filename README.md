## Environment set up
These are the commands I used to set up my local environment.

The pytorch installation can be fiddly depending on your set up. The installation below is for installing pytorch on a Mac, but see [this page](https://pytorch.org/get-started/locally/) for setting up on other OSes and GPUs.

```bash
git clone git@github.com:gjohl/swb_eyesea.git
conda create -n eyesea python=3.10
conda activate eyesea 
conda install pytorch::pytorch torchvision torchaudio -c pytorch
conda install -c fastai fastai
conda install -c conda-forge jupyterlab
```