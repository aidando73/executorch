```bash
source ~/miniconda3/bin/activate
conda create --prefix ./env python=3.10
conda activate ./env

git submodule sync                 
git submodule update --init

./install_requirements.sh

examples/models/llama/install_requirements.sh

pip install llama-stack
llama model list
```

