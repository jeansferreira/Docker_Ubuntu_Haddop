docker build -t ubuntu_hadoop .
docker images
docker ps
docker run -p 8088:8088 --name my_ubuntu_hadoop -d ubuntu_hadoop
docker ps
docker exec -it my_ubuntu_hadoop bash

DOcker configuração
docker login

user: jeansferreira
senha: C@rlos2018

Criar uma imagem com o meu usuário
docker build -t jeansferreira/ubuntu_hadoop:1 .

Subir para o docker hub
docker push jeansferreira/ubuntu_hadoop

