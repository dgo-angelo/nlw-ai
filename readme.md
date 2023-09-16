<p align="left">
  <img src="https://img.shields.io/static/v1?label=REACT&message=BIBLIOTECA&color=blue&style=for-the-badge&logo=REACT"/>

  <img src="https://img.shields.io/static/v1?label=TYPESCRIPT&message=language&color=red&style=for-the-badge&logo=TYPESCRIPT"/>
<img src="https://img.shields.io/static/v1?label=NODEJS&message=SERVER&color=green&style=for-the-badge&logo=nodedotjs"/>

<img src="https://img.shields.io/static/v1?label=OPENAI&message=SERVER&color=green&style=for-the-badge&logo=OPENAI"/>

<img src="https://img.shields.io/static/v1?label=prisma&message=SERVER&color=green&style=for-the-badge&logo=prisma"/>
<img src="https://img.shields.io/static/v1?label=sqlite&message=DATABASE&color=cyan&style=for-the-badge&logo=sqlite"/>


<img src="https://img.shields.io/static/v1?label=TAILWINDCSS&message=STYLE&color=purple&style=for-the-badge&logo=TAILWINDCSS"/>
  <img src="https://img.shields.io/static/v1?label=chrome&message=plataform&color=yellow&style=for-the-badge&logo=google-chrome"/>
</p>


### Tópicos 

:small_blue_diamond: [Sobre o Projeto](#star-sobre-o-projeto)

:small_blue_diamond: [Objetivo](#dart-objetivo)

:small_blue_diamond: [Imagens](#sunrise_over_mountains-imagens)

:small_blue_diamond: [Pré-requisitos](#warning-pré-requisitos)

:small_blue_diamond: [Como rodar a aplicação](#arrow_forward-como-rodar-a-aplicação)

## :star: Sobre o Projeto 

 Projeto desenvolvido durante o NLW IA, um evento online grauito, organizado pela [Rocketseat](https://lp.rocketseat.com.br/nlw). 



## :dart: Objetivo

:trophy: A NLW-AI é uma aplicação que permite a geração de títulos e descrições de videos utilizando inteligência artifical, via integração com a api do OpenAI. 


## :sunrise_over_mountains: Imagens

### :computer: Web
![](/images/nlw-ai.png)


## :arrow_forward: Como rodar a aplicação 

#### :warning: Pré-Requisitos

- [Git](https://git-scm.com/)

#### :heavy_check_mark: Clonando o Projeto

No terminal, clone o projeto: 

```
https://github.com/dgo-angelo/nlw-ai.git
```

### :station: Server

#### :warning: Pré-Requisitos

- :link: [NodeJs e NPM](https://nodejs.org/en/)


#### :arrow_forward: Executando a aplicação

1) Acessar a pasta ```server``` do projeto
2) Instalar as dependencias
```
npm install
```
3) Renomer o arquivo .env.example para .env, e preencher as variáveis abaixo:

```
DATABASE_URL="file:./dev.db"
OPENAI_KEY="informar-aqui-sua-chave-de-api-do-openai"
```

3) Executar o comando abaixo, que disponibilizará a api no endereço http://localhost:3333

```
npm run dev
```

4) Acessar a api no endereço http://localhost:3333

### :computer: Web

#### :warning: Pré-Requisitos

- [Vite](https://vitejs.dev/)

#### :arrow_forward: Executando a aplicação

1) Acessar a pasta ```web``` do projeto
2) Instalar as dependencias

```
npm install
```

3) Executar o comando abaixo

```
npm run dev
```

4) Acessar o link que será exibido no terminal

<hr/>
