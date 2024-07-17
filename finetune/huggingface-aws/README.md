# AI

## Environment setup
```
conda create -n ai python=3.11 -y
conda activate ai
pip install -r requirements.txt
python -m ipykernel install --user --name=ai
```

## To login to Huggingface
```
pip install --upgrade huggingface_hub
huggingface-cli login --token $REPLACE_WITH_YOUR_TOKEN_ON_HUGGING_FACE
```
