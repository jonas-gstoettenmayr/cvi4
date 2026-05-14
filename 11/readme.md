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