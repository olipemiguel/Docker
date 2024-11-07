# Documentação do Docker CLI: [Docker Document](https://docs.docker.com/)
# Estaremos realizando executando a IMAGE do UBUNTU!
# Como se ver se esta tendo alguns container em execução: [ docker ps | docker ps -a ] 
# Como se remover os container gerados: [ docker rm <|IDContainerOUNameContainer|> ]
# Como se remover todos os container gerados: [ docker container prune ]
# Como se fazer listagem da imagem instalada: [ docker images ]
# Como se remover os imagem geradas: [ docker rmi <|IDContainerOUNameContainer|>:latest ]
# Como se remover todas imagem gerada: [ docker rmi $(docker images -q) ]
# Como se remover e parar o container al mesmo tempo: [ docker rm -f <|IDContainerOUNameContainer|> ]
# Como se executar um container que já esta e montado configurado: [ docker start -ai <|IDContainerOUNameContainer|> ]
# Como se executar um container em background: [ docker run -dit <|IDContainerOUNameContainer|>  |  docker start -dai <|IDContainerOUNameContainer|> ] 
# Executar a imagem ubuntu: docker run ubuntu 
# Executar o docker com modo interativo: docker run --name <|AdicionarIdentificadorContainer|> -i -t <|NomeDaImagem|>  
# Executar container docker sem modo interativo: docker exec <|IDContainerOUNameContainer|> <|ComandoExecução|>
### ||||||||||||||||||||||||||||||||
# Como se parar um container em execução: [ docker stop <|IDContainerOUNameContainer|> ]
# Como se pausar um container em execução: [ docker pause <|IDContainerOUNameContainer|> ]
# Como se retomar um container em execução: [ docker unpause <|IDContainerOUNameContainer|> ]
# Como se retorna um container em execução: [ docker restart <|IDContainerOUNameContainer|> ]
# Como se eliminar um container em execução: [ docker kill <|IDContainerOUNameContainer|> ]
# Como se deletar um container: [ docker delete <|IDContainerOUNameContainer|> ]
# Como se renomear um container: [ docker rename <|IDContainerOUNameContainer|> <|NovoNomeContainer>]
### ||||||||||||||||||||||||||||||||
