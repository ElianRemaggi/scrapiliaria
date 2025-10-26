
# correr el docker compose del repo

docker compose up -d

# Pegar en un tablero el contenido de workflow.json

docker exec -it n8n n8n import:workflow --input=/data/workflows/workflow.json

# ingresar a la url del contenedor activo

http://localhost:5678/

# inicializar ngrok

ngrok http 5678
