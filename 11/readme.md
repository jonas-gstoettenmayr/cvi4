`> open folder` 

/home/azureuser

`> Create new terminal`

`git clone https://github.com/schedldave/cvi4ic-notebooks.git`
`git submodule update --init --recursive`

`curl -LsSf https://astral.sh/uv/install.sh | sh`
`uv venv`
`source .venv/bin/activate`
`uv pip install git+https://github.com/openai/CLIP.git`
`uv pip install -r requirements.txt`

Open notebook and select kernel
`>Python: Select Interpreter`
`Enter interpreter path`
`Find...`
`/home/azureuser/cvi4ic-notebooks/11/.venv/bin/python`


```
pip install torch torchvision --index-url https://download.pytorch.org/whl/cu121
```