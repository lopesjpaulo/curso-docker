# CURSO DE DOCKER

## Comandos válidos

Executar o container. Se a imagem não for encontrada no cache, ela é baixada, o container criado e executado.

    docker container run 'container'

Executa o container, mapeando para a porta escolhida

    docker container run -p 8080:80 'container'

Mostra os containers em execução

    docker container ps

Mostra todos os containers criados, em execução ou não.

    docker ps -a

Acessa o bash do container criado. Acessando o bash do container debian criado.

    docker container run -it debian bash

Atribuindo nome ao container

    docker container --name 'nome do container' -it debian bash

Reutilizar container

    docker container start -ai mydeb