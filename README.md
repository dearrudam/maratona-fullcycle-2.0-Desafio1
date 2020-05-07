<p align="center">
  <img src="https://raw.githubusercontent.com/dearrudam/maratona-fullcycle-2.0-Desafio1/master/maratona-fullcycle-2.0-logo.png"/>
</p>

# Minha solução para o Desafio 1

Minha solução foi desenvolvida utilizando o framework [Nestjs](https://github.com/nestjs/nest).


## Descrição do Desafio 1:

### Instalação e preparação do ambiente

O primeiro passo para que você consiga acompanhar muito bem a Maratona é ter o seu ambiente de desenvolvimento pronto para conseguir simular tudo que te apresentaremos nos próximos vídeos. Nesse ponto o que você deve fazer como desafio será:

1. Instalar o Node.js em seu computador
2. Criar um webserver que escuta na porta 3000
3. Ao acessar o webserver, a seguinte mesagem deverá aparecer: "Maratona Full Cycle 2.0"
4. Instalar o Docker em seu computador
5. Gerar uma imagem Docker dessa aplicação a partir da imagem node:14.1-alpine.
6. Publicar a imagem no Dockerhub
7. Quando executarmos: docker run -p 3000:3000 seu-login-docker/nome-da-sua-imagem deveremos ver a mensagem na porta 3000 de nosso browser
8. Postar nos comentários do vídeo a URL da sua imagem para que possamos executar

## Construir o projeto

```bash
$ npm install
```

## Executando o projeto

```bash
# development mode
$ npm run start

# watch mode (util para desenvolvimento (hot-reload))
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Executar os testes 

```bash
# unit tests (testes unitários)
$ npm run test

# e2e tests (testes de integração)
$ npm run test:e2e

# test coverage (cobertura de testes)
$ npm run test:cov
```

