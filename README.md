# DioRepo-Desafio-GitHub
Desafio DIO - Primeiro Repositorio disponibilizado no GitHub
Criação do Repositório no GITHUB

Este primeiro desafio consolida as informações aprendidas nas aulas de Git e GitHub, atraves da criação de um repositório no ambiente GITHUB e com os versionamentos controlados pelo GIT (GitBash).

A utilização do Readme com a extenção .md markdown --> uma linguagem de formatação que auxilia na apresentação do sue portifolio no ambiente GitHub.
## links Uteis
[Sintaxe Basic Mardown](https://www.markdownguide.org/basic-syntax/)

obs: escrever o nome do link entre os os colchetes cria o link, e entre parenteses a URL do link.

😉👍

Um Resumo dos comandos aprendidos
COMANDOS NO GIT PARA SALVAR UM REPOSITORIO NO GITHUB
Considerando que os seus ambientes GIT e GITHUB estao configurados
 com user, e-mail, keySSH pub/priv - os comandos a serem informados serão:

Inicialmente voce vai CRIAR de arquivo/pasta "trabalho" local 
no seu diretorio desktop ou no diretorio /C...

Abrir esta pasta "trabalho" no GIT BASH diretorio desktop ou no C/..

Atraves do Comando CD ==> Acessar o diretorio que vai trabalhar 

==> O Comando GIT STATUS vai mostrar como esta o status do GIT naquele
momento e para aquele diretorio. A cada comando voce pode dar um 
GIT STATUS para verificar o que esta sendo esperado por fazer !!!!
==> o Comando LS vai listar o que existe na pasta
==> o Comando DIR vai listar o que existe no diretorio

1 - < git init > - Este comando vai criar um arq ".git" para este repositorio
Ex.: c/projetos-dio/pasta-dio ==> criou um arquivo ".git" nesta pasta 
para controlar o repositorio que vamos salvar nela.
vai informar que inicializou um repositorio .git vazio no caminho 
c/projetos-dio/pasta-dio

2 - Estes dois comandos sao responsáveis pelo controle de versão:
< git add . > (vai salvar todos os arquivos na area de STAGE) 
ou < git add nome do arquivo> (vai salvar este arquivo na area de STAGE) 

==> Se der um < git status > neste momento, o GIT vai informar quais os
arquivos sao esperados para darem COMMIT

< git commit -m > "mensagem explicativa sobre os repositorios criados"
Este comando vai efetivamente salvar o arq. no Git para versionamento

3 - < git branch -M main > ==> caso vc tenha criado o BRANCH no GITHUB 
como MASTER ==>  este comando vai garantir que vc salve no BRANCH MAIN

==> AGORA TEREMOS QUE CRIAR UM PROJETO NO GITHUB !!!

CLICK NO GATINHO DO GITHUB ==> VAI PARA A TELA PRINCIPAL ==> APERTE NEW

 E CRIE UM NOVO REPOSITORIO / Se quiser crie o arq .md README 

4 - Voltar para o GIT BASH para efetuar o comando que vai linkar o seu 
repositorio do GITHUB ao seu arquivo dentro do diretorio do seu computador

< git remote add origin > git@github.com:seuusuario/seurepositorio.git 
a parte do git@.... faça um copy/paste do endereço do repositorio no 
GITHUB que for apresentado pelo HTTP:// ou SSH ou CLI...
OBS: estamos usando o link do SSH ==> git@github.com:JavaliHub/DioRepo-Desafio-GitHub.git

5 - < git push -u origin main/master > dependendo de como vc criou o seu
branch no GITHUB
