# Documentação da API

* Escolher um local do computaodr para criar o projeto 
* Abrir o gitBash nesta basta

Com o gitBash aberto, executar os comenados: 
 
Criar a raiz do projeto (mkdir: make diretorio = criar pasta)
```
mkdir NOME_PROJETO
```

Acessar a pasta (cd: change diret...)
```
cd NOME_PROJETO
```

Abrir o VS Code
```
code . 
```

Criar o arquivo gerenciador de pacotes node 
```
npm init -y 
```

Criar arquivo para não enviar arquivos para o github (pode ser criado no vs code)
```
touch .gitignore
```

Criar arquivo para reservar variáveis do projeto (pode ser criado no vs code)
```
touch .env
```

## Instalar os pacotes do projeto

Instalar pacotes para o projeto
```
npm i express nodemon dotenv
```

* Será o servidor da api 
* i: install
* nodemon: atualizar os arquivos alterados sem parar o servidor
* dotenv: gerenciador de variáveis de ambiente

Criar pasta src
```
mkdir src
```

Criar arquivo js
```
touch src/server.js
```

Adicionar arquivos e pastas no .gitignore (escrever direto no VSCode)
```
node_modules
.env
```

git init

ls -a


