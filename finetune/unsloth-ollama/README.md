## Environment setup
```
conda create --name unsloth-env python=3.10 pytorch-cuda=<11.8/12.1> pytorch cudatoolkit xformers -c pytorch -c nvidia -c xformers -y
conda activate unsloth-env
pip install -r requirements.txt
python -m ipykernel install --user --name=unsloth-env
```
