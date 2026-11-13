# full-fledged-RAG

# TO INSTALL uv
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex" 

cd full-fledged-RAG

uv init --bare
uv python pin 3.12
uv sync
uv venv --python 3.12
.venv\Scripts\Activate.ps1
uv add -r requirements.txt
