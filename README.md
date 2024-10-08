# Projeto de Automação de Testes com Cypress, Cucumber e PageObjects

Este projeto utiliza o **Cypress** junto com **Cucumber** e o padrão **PageObjects** para automação de testes. Siga as instruções abaixo para clonar e executar o projeto corretamente.

## Pré-requisitos

Certifique-se de que você tenha os seguintes requisitos instalados em sua máquina antes de começar:

- [Node.js](https://nodejs.org/) (versão 12 ou superior)
- [Git](https://git-scm.com/)

## Passos para clonar e rodar o projeto

### 1. Clonar o repositório

Abra o terminal e execute o comando abaixo para clonar o repositório para o seu ambiente local:

<<<<<<< HEAD
```bash

git clone https://github.com/vmalachias/https://github.com/viniciusmalachias/cypress_cucumber_web_api.git

Navegue para a pasta do projeto clonado:

 cd .\cypress_cucumber_web_api\


2. Instalar as dependências
=======

git clone https://github.com/viniciusmalachias/cypress_cucumber_web_api

Navegue para a pasta do projeto clonado:

cd seu-repositorio


### 2. Instalar as dependências
>>>>>>> 10faa69cc61fde4f7fb85a53dd5aee843da98628
Instale as dependências do projeto usando o npm (que é instalado junto com o Node.js):
npm install

Isso instalará todas as bibliotecas necessárias, incluindo Cypress, Cucumber e quaisquer outras dependências que o projeto exija.

<<<<<<< HEAD
3. Executar os testes
=======
### 3. Executar os testes
>>>>>>> 10faa69cc61fde4f7fb85a53dd5aee843da98628
Para executar os testes utilizando o Cypress em modo headless (sem interface gráfica), execute o seguinte comando:
npx cypress run

Se você preferir rodar o Cypress com a interface gráfica, use:
npx cypress open

Isso abrirá a interface do Cypress, onde você pode selecionar e executar os testes manualmente.

<<<<<<< HEAD
4. Estrutura do Projeto
=======
### 4. Estrutura do Projeto
>>>>>>> 10faa69cc61fde4f7fb85a53dd5aee843da98628
cypress/integration/: Contém os arquivos de teste em Gherkin (.feature) usando o Cucumber.
cypress/pages/: Contém os arquivos PageObjects, que encapsulam a lógica de interação com as páginas.
cypress/support/: Contém configurações e customizações do Cypress, como as definições dos steps do Cucumber.

<<<<<<< HEAD
5. Executar um teste específico
Caso queira rodar um teste específico, você pode indicar o caminho para o arquivo de testes usando:
npx cypress run --spec "cypress/integration/path-to-your-test.feature"

6. Alterações no Cypress config
As configurações do Cypress foram ajustadas conforme as necessidades do projeto, mas essas modificações são transparentes para o usuário que deseja apenas rodar os testes.

7. Informações adicionais
Este projeto utiliza o Cucumber para definir cenários de teste de maneira mais legível, no formato Gherkin.
O padrão PageObjects foi implementado para tornar o código de teste mais reutilizável e organizado.

8. Contato
Caso encontre algum problema ou tenha dúvidas, entre em contato através do e-mail: seu-email@example.com.
=======
### 5. Executar um teste específico
Caso queira rodar um teste específico, você pode indicar o caminho para o arquivo de testes usando:
npx cypress run --spec "cypress/integration/path-to-your-test.feature"

### 6. Alterações no Cypress config
As configurações do Cypress foram ajustadas conforme as necessidades do projeto, mas essas modificações são transparentes para o usuário que deseja apenas rodar os testes.

### 7. Informações adicionais
Este projeto utiliza o Cucumber para definir cenários de teste de maneira mais legível, no formato Gherkin.
O padrão PageObjects foi implementado para tornar o código de teste mais reutilizável e organizado.

### 8. Contato
Caso encontre algum problema ou tenha dúvidas, entre em contato através do e-mail: Vinicius.malachiasti@gmail.com
ou 11989669903
>>>>>>> 10faa69cc61fde4f7fb85a53dd5aee843da98628


### Explicação do conteúdo:

- **Pré-requisitos**: Informações sobre o que o usuário precisa ter instalado (Node.js, Git).
- **Passos para clonar e rodar o projeto**: Instruções simples para clonar o repositório, instalar dependências, e executar os testes.
- **Estrutura do projeto**: Uma visão geral dos diretórios principais, como onde ficam os arquivos **PageObjects** e os testes em **Cucumber**.
- **Cypress config**: Indica que as alterações no arquivo de configuração são irrelevantes para a execução dos testes.
- **Contato**: Uma seção para os usuários entrarem em contato caso precisem de ajuda.

