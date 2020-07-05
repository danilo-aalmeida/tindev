# TinDev :fire:

| [<img src="https://simpleicons.org/icons/node-dot-js.svg" width=115><br><sub>NodeJs</sub>](https://nodejs.org) |  [<img src="https://simpleicons.org/icons/react.svg" width=115><br><sub>React</sub>](reactjs.org) |  [<img src="https://simpleicons.org/icons/react.svg" width=115><br><sub>React Native</sub>](https://reactnative.dev) |
| :---: | :---: | :---: 

> Status do Projeto: Concluído :heavy_check_mark:

## Tópicos
  - [Descrição do Projeto](#descrição-do-projeto)
  - [Funcionalidades](#funcionalidades)
  - [Layout da Aplicação](#layout-da-aplicação)
  - [Como Rodar a Aplicação](#como-rodar-a-aplicação)
  - [Linguagens, Dependências e Libs Utilizadas](#linguagens-dependências-e-libs-utilizadas)
  - [Licença](#licença)


## Descrição do Projeto

<p align="justify">Projeto desenvolvido a partir do curso OmniStack 8 da Rocketseat :rocket: utilizando a stack Node.Js, React e React Native</p>

<p align="justify">A idéia é reproduzir um "Tinder" para desenvolvedores, onde o usuário informa o seu usuário do GitHub e para ele é apresentado uma lista já cadastrada de outros desenvolvedores nos quais podem ser atribuidos Likes :heart: ou Dislikes :x:. Quando houver uma combinação a aplicação informa aos usuários em tempo real sobre o "Match".</p>

## Funcionalidades

- :heavy_check_mark: Cadastrar usuário do GitHub (Ao logar-se na aplicação).
- :heavy_check_mark: Listar usuários cadastrados.
- :heavy_check_mark: Dar like ou dislike nos usuários.
- :heavy_check_mark: Informar Match aos usuários em caso de combinação.

## Layout da Aplicação

### Aplicação Web

![Tela Login](https://user-images.githubusercontent.com/34552353/86504297-3d050900-bd8d-11ea-9d99-febd5f5eaa9b.png)

![Tela Principal](https://user-images.githubusercontent.com/34552353/86504300-42faea00-bd8d-11ea-99fe-081954e993ed.png)

![Match](https://user-images.githubusercontent.com/34552353/86504303-45f5da80-bd8d-11ea-921b-8c1c03eff09a.png)

### Aplicação Mobile

| ![Tela Login](https://user-images.githubusercontent.com/34552353/86504315-6b82e400-bd8d-11ea-9f14-2a1c8c1789bd.png) | ![Tela Principal](https://user-images.githubusercontent.com/34552353/86504316-6d4ca780-bd8d-11ea-90f6-8cb1e4a5f012.png) | ![Match](https://user-images.githubusercontent.com/34552353/86504318-6f166b00-bd8d-11ea-96ff-b332d7cda35e.png) |
| :---: | :---: | :---: 

## Como Rodar a Aplicação

No terminal, clone o projeto:

```
git clone git@github.com:danilo-aalmeida/tindev.git
```
ou
```
git clone https://github.com/danilo-aalmeida/tindev.git
```

### Backend:

Após ter feito o clone do projeto, navegue até o diretório do backend:

```
cd caminho/tindev/backend
```

Instale as dependências:

```
yarn install
```
ou
```
npm install
```

Inicie o backend através do comando:

```
yarn dev
```
ou
```
npm dev
```

## Frontend

Após ter feito o clone do projeto, navegue até o diretório do frontend:

```
cd caminho/tindev/frontend
```

Instale as dependências:

```
yarn install
```
ou
```
npm install
```

Inicie o frontend através do comando:

```
yarn start
```
ou
```
npm start
```

### Mobile

Após ter feito o clone do projeto, navegue até o diretório do mobile:

```
cd caminho/tindev/mobile
```

Instale as dependências:

```
yarn install
```
ou
```
npm install
```
Certifique-se que esteja com o emulador rodando no exemplo abaixo foi utilizado um emulador de android.

Com o emulador ligado, siga os passos abaixo 
Inicie o mobile através do comando:

```
yarn start
```
ou
```
npm start
```
No terminal do editor ou no do próprio sistema operacional execute o comando abaixo para configurar o emulador para que ele consiga acessar o localhost das rotas utilizadas no desenvolvimento.

```
adb reverse tcp:3333 tcp:3333
```

Instale o aplicativo no emulador através dos comandos abaixo de acordo com o sistema mobile:

```
yarn android
```
ou
```
npm android
```


# Linguagens, Dependências e Libs Utilizadas

![Badge](https://img.shields.io/static/v1?label=Node.js&message=backend&color=brightgreen&style=for-the-badge&logo=node-dot-js)

  - Dependências:
    - Axios
    - Cors
    - Express
    - Mongoose
    - socket. io

![Badge](https://img.shields.io/static/v1?label=react&message=frontend&color=blue&style=for-the-badge&logo=react)

  - Dependências:
    - Axios
    - React
    - React-Dom
    - React-Router-Dom
    - socket.io-client

![Badge](https://img.shields.io/static/v1?label=react-native&message=mobile&color=blue&style=for-the-badge&logo=react)

  - Dependências:
    - @react-native-community/async-storage
    - Axios
    - React
    - React Native
    - React-Native-Gesture-Handler
    - React-Native-Reanimated
    - React Navigation
    - socket.io-client

## Licença 

The [MIT License](https://github.com/danilo-aalmeida/tindev/blob/master/LICENSE) (MIT)

Copyright :copyright: 2020 - TinDev
