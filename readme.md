# Documentação
1 - Criar pasta
```
mkdir projetoBackend
```
2 - Acessar a pasta criada
```
cd projetoBackend
```
3 - Criar arquivo readme
```
touch readme.md
```
4 - Iniciar gerenciador de pacotes Node (cria um arquivo package.json na raíz do projeto)
```
npm init -y
```
5 - Instalar os pacotes para rodar a API (i = install)
* express: Será o servidor da api
* nodemon: Atualizar os arquivos alterados sem parar o servidor
* dotenv: Gerenciador de variáveis de ambiente
```
npm i express nodemon dotenv
```
6 - Abrir o VSCode
```
code .
```
7 - Criar gitignore
* O comando nano serve para criar e editar arquivos pelo terminal
* Ctrl + o: Salvar o arquivo
* Enter: Confirmar
* Ctrl + x: Fechar o arquivo
```
nano .gitignore
```
8 - Ainda dentro do terminal, editando o arquivo gitignore, adicionar pasta a ser ignorada
```
node_modules
```
9 - Criar src
```
mkdir src
```
10 - Criar arquivos dentro da pasta src
* app.js - Cria a configuração da API
* server.js - Recebe as configurações da aplicação e roda a API
```
touch src/app.js
```
```
touch src/server.js
```
11 - Criar pastas dentro da pasta src
* config - Gerencia a conexão com o banco de dados
* controllers - Gerencia as requisições das rotas e conexão com banco de dados
* routes - Gerencia as rotas da API
```
mkdir src/config
```
```
mkdir src/controllers
```
```
mkdir src/routes
```
12 - Enviando para o GitHub: Iniciar o gerenciador de arquivos .git
```
git init
```
13 - Conectar ao GitHub
```
git config --global user.name "USUÁRIO"
```
```
 git config --global user.email "EMAIL@GMAIL.COM"
```
14 - Verificar os arquivos que serão enviados
```
git status
```
15 - Adicionar os arquivos
```
git add .
```
16 - Salvar e adicionar comentário
```
git commit -m 'comentário'
```
17 - Criar repositório no GitHub e copiar URL
18 - No repositório, definir a branch main
```
git branch -M main
```
19 - Conectar com o repositório criado através da URL
```
git remote add origin URL_AQUI
```
20 - Enviar os arquivos para o GitHub
```
git push -u origin main
```
21 - Com os arquivos no GitHub, eles podem ser deletados do computador. Começar acessando a pasta anterior e fechando o VSCode
```
cd ..
```
22 - Deletar os arquivos
* rm (remove) - Comando para remover arquivo(s)
* -r (recursive) - Apaga pastas e subpastas
* -f (force) - Não pergunta confirmações
```
rm -rf projetoBackend
```