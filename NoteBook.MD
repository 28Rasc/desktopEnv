sudo service docker restart - Reinstartar o serviço docker no host.
sudo docker image build -t nome_img . - Buildar uma imagem a partir do Dockerfile.
sudo docker image ls - Listar imagens locais.
sudo docker pull <imagem> - Baixar imagem a partir do repositório 'Dockerhub'.
sudo docker system prune - Remover todas as configurações (Like reset to default).
sudo docker container inspect <ID> - Inspecionar propriedades do container.
sudo docker exec -<Flag> <ID> <COMANDO>- executar comandos dentro de containers em execução.
