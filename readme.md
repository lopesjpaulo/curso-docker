# CURSO DE DOCKER

## Comandos válidos

Executar o container. Se a imagem não for encontrada no cache, ela é baixada, o container criado e executado.

    docker container run 'container'

Mostra os containers em execução

    docker container ps

Mostra todos os containers criados, em execução ou não.

    docker ps -a

Acessa o bash do container criado. Acessando o bash do container debian criado.

    docker container run -it debian bash