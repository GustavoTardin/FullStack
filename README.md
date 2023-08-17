Inicialização
Para executar o projeto, utilize as ferramentas descritas na sessão Ferramentas.

Ferramentas
NPM - Gerenciador de pacotes padrão para execução do JavaScript Node.js
Docker - Conjunto de produtos de plataforma como serviço que usam virtualização de nível de sistema operacional.
Docker Compose - Ferramenta usada para definir e executar aplicativos de vários contêineres do Docker
# Faça o clone
$ git clone git@github.com:sergioruza/beer-delivery-app.git

# Acesse a pasta
$ cd beer-delivery-app

# Rode a aplicação frontend
$ cd ./front-end
$ npm i
$ npm start
# frontend logs
#You can now view frontend in the browser.
#  Local:            http://localhost:300?

# Rode a aplicação back-end
$ cd ./back-end
$ npm i
$ npm run dev
# [nodemon] starting `node .`
# Api rodando na porta 3001

# Suba o contêiner do mongoDB
$ docker-compose up -d

# Vá até a pasta backend e popule o banco
$ cd ./back-end
$ npm run db:reset
beer-delivery-app
Introdução
Este projeto possui o objetivo principal de criar uma aplicação completa de delivery de cerveja, incluindo frontend e backend, com os objetivos gerais de firmar conhecimentos em nodeJS com Sequelize, React, MySQL e desenvolvimento em time.

Análise técnica
Descrição do ambiente técnico
O sistema é composto de um backend. Linguagem, frameworks e bibliotecas principais utilizadas para a criação:

Back-End
javascript nodejs express sequelize mysql

Front-End
javascript react MUI axios

Requisitos Funcionais
Respeitando a proposta, o sistema deverá atender os seguintes requisitos:

RF1 - Ter acesso via login;
RF2 - Fazer a comunicação entre clientes e pessoas vendedoras;
RF3 - Se a pessoa cliente faz o pedido, o mesmo deve aparecer para a pessoa vendedora em seu dash de pedidos após a atualização da página.
Finais
📝 Objetivos de Aprendizado

Construir uma aplicação completa com frontend e backend;

Trabalhar em equipe;

Metodologias ágeis;

Colocar em prática todas as stacks já aprendidas até hoje;
