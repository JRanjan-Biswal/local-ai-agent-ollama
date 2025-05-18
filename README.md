# LOCAL AI AGENT

## dependency required
1. ollama
    * llama3.2
    * mxbai-embed-large
2. langchain
3. langchain-chroma
3. panda

## create virtual env
1. python -m venv venv
2. .venv/Scripts/activate

## installing dependency 
1. pip install ./requirements.txt

## installing ollama
1. go to `ollama.com`
2. install ollama
3. open terminal
    * check if ollama exist `ollama`
    * install ollama model `ollama pull llama3.2`
    * install embedding model `ollama pull mxbai-embed-large`

## start project
1. python main.py
