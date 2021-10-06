# Comandos CMD



​	

- DIR - Traz uma lista de diretorio.

- CD - Usado para navegar entre as pastas.

- CLS - Limpar o terminal.

- MKDIR - Criar uma pasta.

> - Esse simbolo é um redirecionador de fluxo, pega a saida da função echo e joga em um arquivo.

- DEL - Deleta arquivos.

- RMDIR - Remove directory.  /S /Q

### GIT

A sigla **SHA** significa **Secure Hash Algorithm (Algoritimo de Hash Seguro)**, é um conjunto de funções hash criptográficas projetadas pela **NSA (Agência de Segurança Nacional dos EUA).**

A encriptação gera conjunto de caracteres identificador de 40 dígitos.

_openssl sha1 texto.txt_

**BLOBS - TREES - COMMITS**

_echo 'conteúdo' | git hash-object --stdin_

  > 0cb46xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
  > --stdin - esssa função e apenas perque ela espera receber um arquivo. 

_echo -e 'conteudo' | openssl sha1_
  > 303e09f0xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

_echo -e 'blob 9\0conteudo' | openssl sha1_
  > 0cb46bxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

### Comandos

  _ssh-keygen -t ed25519 -C tiagobettega.tb@gmail.com
  cat
  pwd
  eval $(ssh-agent -s)
  ls_

**clonar um Repo.**
  _git clone 'caminho ssh'_



#### comandos do git

_-Iniciar GIT
-Iniciar o versionamento
-Criar um commit_

git int - inicializa o repo.
git add - para mover arquivos e dar inicio ao versionamento.
git commit - criar o primeiro commit.

criando um repositorio:

Abrir o Git Bash direto na pasta C:/
criar uma pasta chamada "workspace"
ja estando dentro da pasta, rode o comando para criar o repositorio:
mkdir "nome da pasta" 
depois rode o comando para inicializar ele
git init
use a o comando ls mais a flag -a para mostra arquvos ocultos.

agora crie o primeiro arquivo digitando
antes disso configure o GIT assim:

git config --global user.email "email@gmail.com"

git config --global user.name Nome

agora vamos para o arquivo
vamos criar um aquivo markdown 
o que é o arquivo markdown?
é basicamente um uma forma mais humana de se escrever um arquivo HTML

exemplo:



MARKDOWN

# Titúlo nivel 1
## Titúlo nivel 2
### Titúlo nivel 3
#### Titúlo nivel 4
##### Titúlo nivel 5
###### Titúlo nivel 6



HTML

<h1>Titúlo nivel 1</h1>
<h2>Titúlo nivel 2</h2>
<h3>Titúlo nivel 3</h3>
<h4>Titúlo nivel 4</h4>
<h5>Titúlo nivel 5</h5>
<h6>Titúlo nivel 6</h6>