# Ollama Endpoint
Running a public HTTP/Ollama LLM endpoint via a Google Colab notebook, benefiting from its runtime GPUs. 

## Usage
Prompt it remotely 

```
curl https://<your_ngrok_public_up>/api/generate -d '{ "model": "llama2","prompt": "Why is the sky blue?" }'
```
