# projeto_node

### Iniciar um projeto no gitHub

Criar um repositório (private ou public)
Escolher tecnologia (.gitgnore), caso disponível
Escolher a opção README.md

### Clonar o projeto para o computador locall

Escolher uma pasta correspondente aos seus projetos
Escolher um editor eficente (Vscode, Atom, Sublimetext, NetBeans, Webstorm...)

Tendo acesso ao promp de comando 

->   git clone "endereço do projeto no git hub"

### Iniciar o arquivo de configuração package.json

    npm init -y

### Instalação de dependencias

npm install "NOME DA TECNOLOGIA"

Exemplo:
->    npm install express

Sempre pesquisar a tecnologia no site que contém a documentação oficial
Exemplo (npm, yarn)
Exemplo:
->     npm install express
->     yarn add express

Obs.: A pasta node_modules contém todas as tecnologias (dependencias) de terceiros

### Desinstalar uma dependencia 

Não excluir qualquer pasta dentro de node_modules

->  npm uninstall express   (por exemplo)

### executando servidor

node "NOME DO ARQUIVO"
Exemplo:
node app
