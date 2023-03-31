<h1 align="center"> Habits </h1>
<p align="center">
  <img src="https://raw.githubusercontent.com/marlonakio/NLW-Habits-Ignite/c3131242559f377a1f3be5ecd218e45f49c12368/.github/nlw/logo.svg" alt="Logo do Projeto" width="300"/>
</p>
<h3 align="center">
Você no controle da sua rotina!
</h3>

<p align="center">
  <a href="#-sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-funcionalidades">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-Para-Devs">Para Devs</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-autor">Autor</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

<br><br>
## 🛈 Sobre

<p align="justify">
A Next Level Week (NLW) é um evento exclusivo e gratuito promovido pela Rocketseat, este evento totalmente online e gratuito oferece uma experiência prática com desafios e muito código para ensino de tecnologias WEB.<br/>
<p align="center">
  <img src="https://github.com/marlonakio/NLW-Habits-Ignite/blob/main/.github/nlw/nlw.jpg?raw=true" alt="Next Level Week" width="100%"/>
<br>

## 🔍 Funcionalidades
<p align="center">
  <img alt="projeto Habits" src="https://github.com/marlonakio/NLW-Habits-Ignite/blob/main/.github/nlw/nlw_ignite.png?raw=true" width="100%">
</p>

O Habits é um aplicativo para controlar seus hábitos diários auxiliando os usuários a rastrear suas atividades realizadas e não realizadas, funcionando como um diário de hábitos saudáveis.

Este aplicativo é bem intuitivo, o usuário deve adicionar o nome do hábito e em quais dias da semana deseja realizar o mesmo. Ao clicar no dia atual será mostrado uma lista dos hábitos que o usuário cadastrou para realizar neste dia. A tela possui um histórico dos dias anteriores conforme o usuário for marcando seus hábitos concluídos a cor irá mudar, ajudando na visualização de quais dias a quantidade de hábitos foram cumpridos.

Foi desenvolvido um aplicativo para desktop (para acesso web) e uma versão mobile para o usuário poder escolher por qual dispositivo deseja realizar as marcações diárias. Este aplicativo foi otimizado para dispositivos desktop e mobile, e suas marcações no mobile estarão atualizadas no desktop e vice-versa.

- <h3> Aplicação Web - Desktop </h3>

Ao acessar a aplicação o usuário irá quadrados cinza que representam os dias, neste momento deverá clicar em `Novo hábito` para adicionar um novo hábito na rotina. Os quadrados cinza são clicáveis e ao clicar em um quadrado ele será apresentado uma lista dos hábitos listados para serem realizados no dia, ao marcar como concluído a barra de progresso irá subir conforme a porcentagem de hábitos concluídos.

Conforme for realizando os hábitos indicamos que o usuário marque para que não se esqueça!
<p align="center">
  <img src="https://github.com/marlonakio/NLW-Habits-Ignite/blob/main/.github/web/web1.png?raw=true" alt="Exemplo da aplicação web" width="100%"/>

<p align="center">
  <img src="https://github.com/marlonakio/NLW-Habits-Ignite/blob/main/.github/web/web2.png?raw=true" alt="Exemplo da aplicação web" width="100%"/>

Abaixo temos um exemplo da aplicação na versão desktop funcionando. Note que a barra de progresso calcula de forma automática a porcentagem de hábitos concluídos, e cada cor tem um indicativo diferente:

- Cinza: nenhum hábito foi concluído no dia;
- Roxo escuro: poucos hábitos concluídos no dia; 
- Roxo claro: muitos hábitos concluídos no dia;
- Cinza com opacidade: dias futuros não disponíveis para preenchimanto.

<p align="center">
  <img src="https://github.com/marlonakio/NLW-Habits-Ignite/blob/main/.github/web/web-demo.gif?raw=true" alt="gif da aplicação web" width="100%"/>

- <h3> Aplicação Web - Mobile </h3>
A versão mobile é bem similar a versão de desktop, também possui um painel dos dias para o usuário visualizar seu progresso, o botão `Novo hábito` se mantém no canto superior direito e é representado pelo botão `Novo`.

|                           Tela de loading                           |                              Home sem progresso                               |                       Home com progresso                        |
| :---------------------------------------------------------------: | :-------------------------------------------------------------------: | :-------------------------------------------------------------: |
| <img src="https://github.com/marlonakio/NLW-Habits-Ignite/blob/main/.github/mobile/mobile-screen-loading.png?raw=true" width="250" /> | <img src="https://github.com/marlonakio/NLW-Habits-Ignite/blob/main/.github/mobile/mobile-first-day-homepage.png?raw=true" width="250" /> | <img src="https://github.com/marlonakio/NLW-Habits-Ignite/blob/main/.github/mobile/mobile-homepage.png?raw=true" width="250" /> |

Diferentemente da versão desktop, no mobile ao clicarmos no dia ele irá conduzir o usuário a uma nova página que detalhará o dia e seus respectivos habitos.

|                               Dia sem hábito cadastrado                                |                            Dia com hábitos marcados                            
| :--------------------------------------------------------------------------: | :------------------------------------------------------------------------------: |
| <img src="https://github.com/marlonakio/NLW-Habits-Ignite/blob/main/.github/mobile/mobile-first-acess.png?raw=true" width="250" /> | <img src="https://github.com/marlonakio/NLW-Habits-Ignite/blob/main/.github/mobile/mobile-check-habit-day.png?raw=true" width="250" /> 

Por se tratar da versão mobile não ser 100% idêntica ao web, com essa nova tela que não existe na de desktop, visando a UX foi adicionado um botão `cadastre um` que ao ser clicado irá redirecionar a tela de cadastro de um novo hábito(este botão só aparece se não houver nenhum hábito disponível neste dia).

|                                 Criação de novo hábito                                 |
| :------------------------------------------------------------------------: |
| <img src="https://github.com/marlonakio/NLW-Habits-Ignite/blob/main/.github/mobile/mobile-create-new-habit.png?raw=true" width="250" /> |

Abaixo temos um exemplo da aplicação na versão mobile funcionando passando por todas as telas demonstrando o fluxo do funcionamento do app. Houve um cuidado para versão mobile ser extremamente similar a versão desktop, deixando o usuário mais confortável para utilizar a aplicação.

<p align="center">
  <img src="https://github.com/marlonakio/NLW-Habits-Ignite/blob/main/.github/mobile/mobile-demo.gif?raw=true" alt="gif da aplicação mobile" width="250"/>

## 👨‍💻 Para Devs
### Instalação

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/) no computador e [Expo](https://expo.dev/) no celular ([Android](https://play.google.com/store/apps/details?id=host.exp.exponent&hl=pt_BR&gl=US), [IOS](https://apps.apple.com/us/app/expo-go/id982107779)).
Além disso é bom ter um editor de código-fonte para trabalhar com o código como [VSCode](https://code.visualstudio.com/).

> ⚠ Antes de executar o frontend e mobile verificar o IP da máquina que irá rodar o backend (pasta server) e configurar no arquivo de setup do axios presente na pasta lib dos respectivos projetos

- Rodando o Back End (servidor)

```bash
# Clone este repositório.
$ git clone git@github.com:marlonakio/NLW-Habits-Ignite.git

# Acesse a pasta do projeto no terminal.
$ cd NLW-Habits-Ignite

# Vá para a pasta server.
$ cd server

# Instale as dependências.
$ npm install

# Execute a aplicação em modo de desenvolvimento.
$ npm run dev


# O servidor inciará na porta 3333 - acesse <http://localhost:3333>
```

- Rodando o FrontEnd (Web)

```bash
# Em outro terminal acesse a pasta do projeto.
$ cd nlw-setup

# Vá para a pasta web.
$ cd web

# Instale as dependências.
$ npm install

# Execute a aplicação em modo de desenvolvimento.
$ npm run dev


# O servidor inciará na porta 5173 - acesse <http://localhost:5173>
```

- Rodando o App (Mobile)

```bash
# Em outro terminal acesse a pasta do projeto.
$ cd nlw-setup

# Vá para a pasta mobile.
$ cd mobile

# Instale as dependências
$ npm install

# Execute a aplicação
$ npx expo start

# Será aberto no terminal o menu do Expo onde poderá scanear o QR Code para executar o app diretamente no seu celular ou as opções de executar no emulador android ou iOS
```
### Banco de Dados
Abaixo temos a representação do bando de dados relacional criado para que a aplicação funcione.
<p align="center">
  <img src="https://github.com/marlonakio/NLW-Habits-Ignite/blob/main/.github/db/erd.png?raw=true" alt="Exemplo da aplicação web" width="70%"/>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- HTML e CSS
- Figma
- Fastify
- JavaScript
- Typescript
- NodeJS
- ReactJS
- React Native
- Vite
- Tailwind CSS
- Expo
- Prisma
- SQLite
- Git e Github
  
[![My Skills](https://skillicons.dev/icons?i=html,css,figma,js,ts,nodejs,react,vite,tailwind,prisma,sqlite,git,github)](https://skillicons.dev)

## 🎨 Layout

Você pode visualizar o layout do projeto através [DESSE LINK](https://www.figma.com/file/https://www.figma.com/community/file/1195326661124171197). É necessário ter conta no [Figma](https://figma.com) para acessá-lo.

## :memo: Licença

Esse projeto está sob a licença MIT.

## 🤵 Autor
<div align="center">
<img src=https://images.weserv.nl/?url=avatars.githubusercontent.com/u/55859290?v=4&h=100&w=100&fit=cover&mask=circle&maxage=7d>
<h1>Marlon Akio Tochiro</h1>
<strong>Student Developer ⓒ 2023</strong>
<br/>
<br/>

<a href="https://www.linkedin.com/in/marlon-akio-ba1763134/" target="_blank">
<img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/marlonakio" target="_blank">
<img alt="GitHub" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="mailto:marlon.akto@gmail.com" target="_blank">
<img alt="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<a href="https://wa.me/5511977769829?text=Ol%C3%A1%21" target="_blank">
<img alt="WhatsApp" src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
</a>


<br/>
<br/>
</div>
