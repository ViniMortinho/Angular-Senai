# Angular Senai

- Pré-requisitos
  - Verificar a versão do gerenciador de pacotes e do Node.js
  - Instalação do Angular CLI
- Criar um novo projeto Angular
- Servidor de desenvolvimento
- Geração de código
- Construção
- Executando testes unitários
- Executando testes de ponta a ponta
- Ajuda adicional

Este projeto foi gerado com Angular CLI versão 16.1.5.

## Pré-requisitos

Antes de começar, certifique-se de ter instalado o Node.js e o Angular CLI globalmente em seu sistema.

### Verificar a versão do gerenciador de pacotes e do Node.js

Para verificar a versão do gerenciador de pacotes npm, abra o terminal e execute o comando `npm -v`. A versão atual é 9.6.7.

Para verificar a versão do Node.js, execute o comando `node -v` no terminal. A versão atual é 18.17.0.

### Instalação do Angular CLI

Para instalar o Angular CLI globalmente, execute o comando `npm install -g @angular/cli`. Se você precisar instalar uma versão específica do Angular CLI, adicione a versão após o `@angular/cli`, por exemplo: `npm install -g @angular/cli@xx.x.x`.

Para verificar se o Angular CLI foi instalado corretamente, execute o comando `ng version`.

## Criar um novo projeto Angular

Para criar um novo projeto Angular, abra o terminal na pasta onde deseja criar o projeto e execute o comando `ng new nome-projeto`. Isso criará uma nova pasta com o nome especificado e gerará a estrutura básica do projeto Angular.

Para verificar as pastas criadas, execute o comando `dir`. Para acessar a pasta do projeto, use o comando `cd nome-projeto`.

Se você usa o Visual Studio Code como editor de código, pode abrir a pasta do projeto diretamente no editor executando o comando `code .` na pasta do projeto.

## Servidor de desenvolvimento

Execute `ng serve` para um servidor de desenvolvimento. Navegue até `http://localhost:4200/`. O aplicativo será recarregado automaticamente se você alterar qualquer um dos arquivos de origem.

## Geração de código

Execute `ng generate component component-name` para gerar um novo componente. Você também pode usar `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Construção

Execute `ng build` para construir o projeto. Os artefatos de construção serão armazenados no diretório `dist/`.

## Executando testes unitários

Execute `ng test` para executar os testes unitários via Karma.

## Executando testes de ponta a ponta

Execute `ng e2e` para executar os testes de ponta a ponta através de uma plataforma de sua escolha. Para usar este comando, você precisa primeiro adicionar um pacote que implemente capacidades de teste de ponta a ponta.

## Ajuda adicional

Para obter mais ajuda sobre o Angular CLI, use `ng help` ou confira a página Visão geral do Angular CLI e referência de comando.

