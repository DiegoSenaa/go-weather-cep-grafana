# Desafio Sistema de temperatura por CEP

### Execução Local via Docker-Compose

  
1. Suba o Docker Compose
   ```bash
   docker compose up -d
   ```

2. Exemplo curl
   ```bash
   curl --request POST --url 'http://localhost:8080' -H "Content-Type: application/json" -d '{"cep" : "02034002"}'
   ```

3. Endereço Zipkin no navegador
   ```bash
      http://127.0.0.1:9411/zipkin/
   ```
