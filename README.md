# Finance Tracker API

O Finance Tracker API é um projeto desenvolvido em NestJS para atender às necessidades de comerciantes que desejam controlar seu fluxo de caixa diário e obter um relatório consolidado do saldo diário. O projeto inclui recursos de autenticação de usuário para garantir a segurança das informações financeiras.

## Requisitos de Negócio

- Serviço que faça o controle de lançamentos
- Serviço do consolidado diário
- Autenticação de usuário

## Funcionalidades

- Registro de lançamentos financeiros, incluindo débitos e créditos.
- Cálculo do saldo diário consolidado com base nos lançamentos registrados.
- Geração de relatórios de saldo diário consolidado.
- Autenticação de usuário com recursos de registro, login e gerenciamento de tokens de acesso.

## Instalação

1. Clone este repositório em sua máquina local.
2. Certifique-se de ter o [Node.js](https://nodejs.org/) e o [npm](https://www.npmjs.com/) instalados.
3. Execute o comando `npm install` para instalar as dependências.
4. Configure as variáveis de ambiente no arquivo `.env` com as informações necessárias, como as credenciais do banco de dados e as configurações de autenticação.
5. Execute o aplicativo usando o comando `npm run start`.
6. Acesse a API em `http://localhost:3000`.

## Uso

1. Faça o registro de um novo usuário usando a rota `/auth/register`.
2. Efetue o login do usuário usando a rota `/auth/login` para obter um token de acesso.
3. Utilize o token de acesso nas requisições que exigem autenticação, incluindo as rotas de controle de lançamentos e relatórios.
4. Registre os lançamentos financeiros através das rotas apropriadas, fornecendo as informações necessárias.
5. Acesse as rotas de relatórios para visualizar o saldo diário consolidado e outras informações relevantes.

## Contribuição

- Para contribuir com melhorias, abra uma issue descrevendo sua proposta ou entre em contato com os mantenedores do projeto.
- Faça um fork deste repositório, faça suas alterações e envie um pull request.
- Siga as diretrizes de estilo de código do projeto e escreva testes para suas alterações.

## Licença

Este projeto é licenciado sob a [MIT License](LICENSE).
