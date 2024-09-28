Executar o Docker Compose
No terminal, navegue até o diretório onde está o arquivo docker-compose.yml e execute o comando:

docker-compose up -d

Isso irá baixar a imagem do Apache, criar o container e mapear a porta 8080 do seu host para a porta 80 do container. Você poderá acessar sua aplicação web no navegador através do endereço http://localhost:8080.
