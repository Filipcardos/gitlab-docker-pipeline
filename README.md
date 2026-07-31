
# Desafio DIO - Pipeline GitLab CI/CD com Docker

## Objetivo
Criar uma imagem Docker e executar sua implantação utilizando GitLab CI/CD e GitLab Runner.

## Tecnologias
- GitLab CI/CD
- GitLab Runner
- Docker
- Nginx
- HTML/CSS

## Estrutura
- index.html
- Dockerfile
- .gitlab-ci.yml

## Executar Localmente
```bash
docker build -t desafio-dio .
docker run -d -p 80:80 desafio-dio
```

## Pipeline
1. Build da imagem Docker.
2. Execução do container.
3. Disponibilização da aplicação.

## Autor
Filipe Oliveira Cardoso

