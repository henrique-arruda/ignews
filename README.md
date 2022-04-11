# ignews

<h1 align="center">
<br>
  <img src="./public/images/logo.svg" alt="Ignews" width="250">
<br>
<br>
</h1>

<p align="center">Portal de notícias com CMS e meio de pagamento integrado</p> 
 <p align="center">Aplicação desenvolvida no curso IGNITE da <a href="https://www.rocketseat.com.br/">@rocketseat</a> </p>

<p align="center">
  <a href="https://github.com/FelipenKniess/ignews/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License MIT">
  </a>  
</p>

## 🎯 Sobre

<p>O ignews é um portal de notícias no qual os usuários pagam para ter acesso. o usuário só tem acesso das postagens caso ele tenha uma inscrição ativa no Stripe. 
  caso o usuário não seja inscrito, poderá ler apenas um resumo das postagens.
</p>
<p>
  Os meios de pagamento da aplicação são integrados com a API do Stripe, juntamente do FaunaDB para armazenar as informações dos usuários. as postagens são administradas através do CMS Prismic.io 
 </p>
 <p>A aplicação é construída com modelo <strong>Serveless</strong>, sem necessidade de criar uma API externa para manipular os dados 🚀</p>

## 🚀 Tecnologias utilizadas
- [NextJS](https://nextjs.org/)
- [Typescript](https://www.typescriptlang.org/)
- [Sass](https://sass-lang.com/)
- [FaunaDB](https://fauna.com/)
- [Stripe](https://stripe.com/docs/payments)
- [Prismic.io](https://prismic.io/)


## :eyes: Demonstração da aplicação
## :framed_picture: Imagens ##

![Captura de Tela (24)](https://user-images.githubusercontent.com/72982326/162753307-9cbdc095-7460-4d72-af3b-ed4fcd98847a.png)


## :octocat: Execução da aplicação em desenvolvimento
- Requisítos: Instalar [Git](https://git-scm.com/), [Node](https://nodejs.org/en/), [Yarn](https://yarnpkg.com/)
```
- baixar as dependências do projeto e executar o projeto:
```bash
$ yarn
$ yarn dev
