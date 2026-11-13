Install Ollama on your machine if you don't have it, then run these two commands:
the first is an embedding model (to embed the text and store it in VectorDB), the second is a SLM that we need to generate text.

ollama pull hf.co/CompendiumLabs/bge-base-en-v1.5-gguf
ollama pull hf.co/bartowski/Llama-3.2-1B-Instruct-GGUF

Finally download the Ollama library for Python to work with models you downloaded:

pip install ollama
