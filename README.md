# CS6501-NLP-Poisoning


### Set up (tested on linux systems... )

- request llama2 (7B-chat,13B-chat) from microsoft and follow instructions: https://llama.meta.com/llama-downloads/
    - Make sure that the llama/ repository is placed in the same parent directory is this repository, there is a symbolic link in the repo that will point to it.
    - download 7B-chat and 13B-chat
- Create a conda environment:
    - ```conda create --name llamatrain```
    - ```conda activate llamatrain ```
    - ```cd llama```
    - ```pip install -e .```
- Create a kernel for using the conda environment in proj.ipynb
    - ```conda activate llamatrain```
    - ```conda install -c anaconda ipykernel```
    - ```python -m ipykernel install --user --name=llamatrain```
    - Choose llamatrain as the kernel of choice when running the jupyter notebook