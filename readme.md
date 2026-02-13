# Notes

```sh

// Abrir firewall:
netsh advfirewall firewall add rule name="Ollama 11434" dir=in action=allow protocol=TCP localport=11434 
netsh advfirewall firewall show rule name="Ollama 11434"


docker compose up -d
docker compose down

docker ps

docker exec -it ollama bash


// Comandos para esto:
ollama list

# ollama pull llama3.1:8b
# ollama run llama3.1:8b


ollama pull gpt-oss:20b
# Alternativas muy buenas:
# ollama pull llama3.1:8b
# ollama pull mistral:7b
# ollama pull qwen2.5:7b

```
