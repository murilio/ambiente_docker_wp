Ambiente de desenvolvimento WordPress com Docker
==============
![Docker Compose](logo.png?raw=true "Docker Compose Logo")

## WordPress
- Ambiente para rodar o WordPress e banco com docker e dentro da pasta **src** colocar todos os arquivos para o seu tema.

## Rodar o projeto

- **Comando:** git clone https://github.com/murilio/ambiente_docker_wp.git ou download ZIP
- **Terminal:** cd ambiente_docker_wp
- **Comando docker:** docker-compose -f "docker-compose.yml" up -d --build
- **Acessar o WP**: http://localhost:8080 - (Tem que instalar)
- **Ativar tema:** painel > Appearance > Themes > **[Active your theme]**