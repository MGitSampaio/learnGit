# Aprendendo Git e Github
Vamos iniciar dizendo que usaremos apenas o terminal de comandos
vamos iniciar instalando o git.
@>> sudo apt install git
Para ver se instalou como deveria.
@>> git --version | retorna a versão do git
crie a pasta do seu projeto e digite:
@>> git init | inicializa o projeto
@>> git add nome_do_arquivo | adiciona o arquivo ao stage
@>> git rm nome_do_arquivo | retira o arquivo do stage

@>> git add . | adicona todos os arquivos ao git necessário antes do commit(sempre)

@>> git commit -m "o que foi feito" | sobe par ou altera seu projeto para o git
@>> git push | sincroniza as versôes fazer sempre após o commit
@>> git staus | retorna o status do seu projeto
@>> git --logonline | lista os commits já realizados e seus id
@>> git branch | retorna as branchs existentes no repositório
@>> git branch nome_da_branch | cria uma nova branch

