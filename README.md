# LinkrFront

Design de um aplicativo de mídia social! Com direito a cadastro, login, comentar, curtir, postar, buscar usuários, filtrar por hashtags e muito mais!

<img src="./src/styles/gif.gif" />

Experimente agora [aqui](https://linkr-iota.vercel.app) <br/>
Confira o back-end também [aqui](https://github.com/taisoliva/linkrAPI)

## Sobre

Este é o front-end do aplicativo web full-stack Linkr! É responsivo e tem persistência de dados, fique à vontade para usar e abusar dele!

Abaixo estão os recursos implementados:

- Sign Up
- Login
- LogOut
- Pesquisar por user by name
- Filtar posts por hashtag
- Follow/Unfollow user
- Delete seu post
- Editar seu post
- Muito mais !
  
Ao usar este aplicativo qualquer usuário pode compartilhar um link na internet e comentar sobre ele!

## Technologies
As seguintes ferramentas e frameworks foram utilizados na construção do projeto, você encontra a lista completa no package.json:<br>
<p>
  <img style='margin: 5px;' src='https://img.shields.io/badge/styled-components%20-%2320232a.svg?&style=for-the-badge&color=b8679e&logo=styled-components&logoColor=%3a3a3a'>
  <img style='margin: 5px;' src='https://img.shields.io/badge/axios%20-%2320232a.svg?&style=for-the-badge&color=informational'>
  <img style='margin: 5px;' src="https://img.shields.io/badge/react-app%20-%2320232a.svg?&style=for-the-badge&color=60ddf9&logo=react&logoColor=%2361DAFB"/>
  <img style='margin: 5px;' src="https://img.shields.io/badge/react_route%20-%2320232a.svg?&style=for-the-badge&logo=react&logoColor=%2361DAFB"/>
  <img style='margin: 5px;' src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"/>
  <img style='margin: 5px;' src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
  <img style='margin: 5px;' src="https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white"/>
  <img style='margin: 5px;' src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white"/>
  <img style='margin: 5px;' src="https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white"/>
  <img style='margin: 5px;' src="https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black"/>
  <img style='margin: 5px;' src="https://img.shields.io/badge/Vercel-000000.svg?style=for-the-badge&logo=Vercel&logoColor=white"/>
  <img style='margin: 5px;' src="https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white"/>
  <img style='margin: 5px;' src="https://img.shields.io/badge/Prettier-F7B93E.svg?style=for-the-badge&logo=Prettier&logoColor=black"/>
  
</p>

## Como rodar

1. Clone este repositorio 
2. Instale as dependências
```bash
npm i
```
3. Crie um arquivo .env na raiz do projeto com a seguinte variável nele
```bash
REACT_APP_API_URL=https://yourBackEndLink:PORT
```
4. Rode o front-end com
```bash
npm start
```
5. Opcionalmente, você pode construir o projeto em execução
```bash
npm run build
```
6. Por fim acesse http://localhost:3000 no seu navegador preferido (a menos que seja o Internet Explorer. Neste caso, reveja suas decisões de vida)
