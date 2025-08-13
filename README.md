# Ollama | IA autohospeada OpenIA, Gemini, DeepSeek

Ver en "http://localhost:3000"

Para la descarga de nuevos modelos desde https://ollama.com/library, anotad el nombre del modelo y usad el siguiente comando;

docker exec ollama ollama pull NOMBRE-del-MODELO

Ejemplo

docker exec ollama ollama pull gemma3:latest #Ojo, este modelo ocupa 3GB, image & text

docker exec ollama ollama pull gemma3:1b #Ojo, este modelo ocupa 850MB, text

docker exec ollama ollama pull gpt-oss:latest #Ojo, este modelo ocupa 14GB, text

docker exec ollama ollama pull llama3.1:latest #Ojo, este modelo ocupa 4,9GB, text

docker exec ollama ollama pull deepseek-r1:1.5b #Ojo, este modelo ocupa 1,1 GB, text

<img width="181" height="256" alt="image" src="https://github.com/user-attachments/assets/5a1305dc-1fd9-442d-9683-436426fff57d" />
