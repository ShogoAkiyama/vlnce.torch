# vlnce.torch
This repogitory is a implemention about VLC-CE algorithm.

## Setting environment
Create anaconda virtual environment
```
# We require python>=3.7 and cmake>=3.10
conda create -n habitat python=3.7 cmake=3.14.0
conda activate habitat
```

Install habitat-sim
```
conda install habitat-sim -c conda-forge -c aihabitat
```

Install habitat-lab
```
git clone --branch v0.1.7 git@github.com:facebookresearch/habitat-lab.git
cd habitat-lab
pip install -e .
```

Install requirement library
```
pip install -r requirements.txt
```