#Git Curso

Curso Git

Este é um repositorio para o git curso

Como funciona o GIT e seus comandos

Tudo oque eu preciso saber estará aqui nesse README

//Abrir o vscode pela linha de comando

*git config --global -e

*git config --global core.editor "code -- wait"


//Verifico o Status do arquivo

*Git status


//Adicionar o arquivo (para ser possivel commitar as alterações

*Git add + nome do arquivo


//Commitar

*Git commit


//Show LOG

*Git log


//Show LOG detalhadamente

*Git show + numero do commit

//Olhar as alteraçôes feitas antes de commitar

*Git diff


//Retornar o arquivo para antes da edição

*Git checkout + nome do arquivo


//Retornar o arquivo depois que eu dei o "Git add" mas me arrependi ou adicionei coisa errada

*Git reset HEAD + nome do arquivo


//Commitei errado alguns comandos para voltar a versão

*git reset --soft = volta o commit

*git reset --mixed = volta o commit mas volta os arquivos para serem visto no log e depois é possivel dar o checkout

*git reset --hard = mata tudo oque foi feito no commit e volta para a versão que você quer



//Para enviar os arquivos para o repositório remoto 

*git remote add "NOME" git@github.com:SamirHamud/"nome do repositorio".git

*git push -u "NOME master


//TECLA I = MODO INSERÇÃO NO TERMINAL BASH

//ESC + :WQ SALVA E SAI

