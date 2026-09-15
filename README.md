# Papra

$ mkdir -p ./app-data/{db,documents} && docker compose up -d

Ver en "http://localhost:1221"

Una vez registrado, puedes eliminar la opción de registrarse modificando la línea 13 del archivo docker-compose.yaml por:

 AUTH_IS_REGISTRATION_ENABLED=false
