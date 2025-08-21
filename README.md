# n8n-ollama-postgres-waha-docker-compose
# implementing docker-compose.yml to handle n8n automations

In environment variables

**waha** container: 

**WHATSAPP_HOOK_URL**, you need specify the webhook url from n8n (access in localhost:5678, after create a webhook node copy the url and past to WHATSAPP_HOOK_URL)

since we using the local networking to conect the containers, you need use the name of host istead "localhost".

you need pull the ollama model, just run this command: **docker exec -it ollama ollama pull llama3.2**
