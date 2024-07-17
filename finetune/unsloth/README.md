## Environment setup
```
conda create --name unsloth-env python=3.10 pytorch-cuda=12.1 pytorch cudatoolkit xformers -c pytorch -c nvidia -c xformers -y
conda activate unsloth-env
pip install -r requirements.txt
python -m ipykernel install --user --name=unsloth-env

curl -fsSL https://ollama.com/install.sh | sh
```

## Instructions from
https://docs.unsloth.ai/tutorials/how-to-finetune-llama-3-and-export-to-ollama
https://old.reddit.com/r/LocalLLaMA/comments/1e416fo/stepbystep_tutorial_how_to_finetune_llama_3_8b/
https://colab.research.google.com/drive/1WZDi7APtQ9VsvOrQSSC5DDtxq159j8iZ?usp=sharing#scrollTo=QmUBVEnvCDJv
