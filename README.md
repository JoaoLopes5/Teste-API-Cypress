🚀 Teste de API com Cypress

Projeto de automação de testes de API utilizando Cypress, com foco na validação de endpoints, autenticação e cenários positivos e negativos.

📌 Sobre o projeto

Este repositório contém testes automatizados desenvolvidos com Cypress para validar o comportamento de uma API REST.

O objetivo do projeto é garantir:

✔️ Integridade das respostas da API
✔️ Validação de status codes
✔️ Testes de autenticação
✔️ Cobertura de cenários positivos e negativos
🧰 Tecnologias utilizadas
Cypress
JavaScript
Node.js
📂 Estrutura do projeto

cypress/
├── e2e/ → Testes automatizados
├── fixtures/ → Massa de dados
├── support/ → Configurações e comandos customizados
cypress.config.js → Configuração do Cypress
package.json → Dependências do projeto

⚙️ Pré-requisitos

Antes de começar, você precisa ter instalado:

Node.js (versão 16 ou superior)
npm ou yarn
🚀 Como executar o projeto
1. Clone o repositório

git clone https://github.com/JoaoLopes5/Teste-API-Cypress.git

2. Acesse a pasta do projeto

cd Teste-API-Cypress

3. Instale as dependências

npm install

4. Execute os testes

Modo interativo:
npx cypress open

Modo headless:
npx cypress run

🧪 Exemplos de testes realizados
🔐 Autenticação com token
📥 Requisições GET
📤 Requisições POST
✏️ Requisições PUT/PATCH
❌ Validação de erros (status 4xx e 5xx)
🔄 Encadeamento de requisições
📊 Boas práticas aplicadas
Uso de fixtures para dados reutilizáveis
Separação de responsabilidades
Testes independentes
Validação de status e corpo da resposta
Organização com describe e it
🎯 Objetivo profissional

Este projeto foi desenvolvido com o objetivo de aprimorar habilidades em:

Automação de testes de API
Uso do Cypress para testes backend
Escrita de testes escaláveis
Boas práticas de QA
📌 Possíveis melhorias
Integração com CI/CD (GitHub Actions)
Geração de relatórios (Allure ou Mochawesome)
Testes parametrizados
Mock de dados
👨‍💻 Autor

João Lopes
GitHub: https://github.com/JoaoLopes5

📄 Licença

Este projeto está sob a licença MIT.
