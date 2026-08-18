# Comandos Utilizados no Projeto

Este documento reúne os comandos de terminal (Linux, Git e Docker) usados durante os meus estudos sobre linux.

## Navegação (Linux/PowerShell)

### pwd
Mostra o caminho completo do diretório atual.


### ls
Lista os arquivos e pastas do diretório atual.


### cd
Muda de diretório.


### exit
Sai do terminal do container Docker.


## Git

### git config
Configura a identidade (nome e e-mail) usada nos commits.


### git status
Mostra o estado atual do repositório: arquivos modificados, adicionados ou prontos para commit.


### git add
Adiciona arquivos para serem incluídos no próximo commit.


### git log
Mostra o histórico de commits já realizados.


### git remote
Gerencia a conexão entre o repositório local e o repositório remoto (GitHub).


### git branch
Renomeia ou cria uma branch.


### git push
Envia os commits salvos localmente para o repositório remoto (GitHub).


## Docker

### docker start
Inicia um container que já existe, mas está parado.


### docker exec
Executa um comando dentro de um container que já está rodando (nesse caso, abre um terminal bash).


### docker ps -a
Lista todos os containers, inclusive os que estão parados.


### docker rm
Remove um container (o `-f` força a remoção mesmo se ele estiver rodando).


## Docker Compose

### docker compose up -d
Sobe o(s) container(s) definidos no arquivo `docker-compose.yml`, em segundo plano.


### docker compose exec
Entra no terminal de um serviço específico definido no `docker-compose.yml`.

## Editor de Texto (nano)

### mkdir + cd + nano
Fluxo usado para criar uma pasta de estudos e documentar os comandos testados dentro dela:

