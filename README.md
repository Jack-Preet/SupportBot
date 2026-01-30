## How to Run

1. **Start MongoDB:** Ensure your local MongoDB server is running.
2. **Start Ollama:** Ensure Ollama is running and you have the model: `ollama pull openchat:7b`
3. **Start the API Server:**
   ```bash
   uvicorn api:app --reload --port 8000
