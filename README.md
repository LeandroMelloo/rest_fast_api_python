# rest_fast_api_python

Construindo API Rest robustas com Fast API e Python

# Bibliotecas e utilitários

FastAPI: Framework para construção de APIs.
HTTPX: Cliente HTTP sincrono e assincrono.
Httpie: Cliente HTTP por linha de comando.
Uvicorn: Servidor de aplicações.
Pytest: Framework para escrever e rodar testes.

# Comando para subir o servidor
uvicorn --reload api_pedidos.api:app

# Fazendo uma requisição na porta 8000/healthchec
http :8000/healthchec
# API Externa
http :8080/account/v1/whoami X-API-KEY:5734143a-595d-405d-9c97-6c198537108f
