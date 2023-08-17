---
layout: post
title: "Be The Hero: Onde ONGs encontram seus heróis."
description: Be The Hero é uma aplicação web/mobile que conecta ONGs a pessoas interessadas em contribuir com causas.
date: 2023-08-07 17:00:00 -0300
image: "/images/BETHEHERO.png"
image_square: "/images/BETHEHERO_SQUARE.png"
tags: [project, fullstack, nodejs, react, reactnative, sqlite]
tags_color: "#b25642"
techs:
  - { label: "Node.js", name: "nodejs", color: "#43853d" }
  - { label: "React", name: "react", color: "#45b8d8" }
  - { label: "React Native", name: "reactnative", color: "#764ABC" }
  - { label: "SQLite", name: "sqlite", color: "#003B57" }
---

## Começando com o projeto

<p><iframe src="https://dms.licdn.com/playlist/vid/C4E05AQGe_rXl0-7LwA/mp4-720p-30fp-crf28/0/1622201780704?e=1692298800&v=beta&t=rLJQrkYi4lpyXuC2w3MmkVNREKg4law-tN4EIs4gZfE" loading="lazy" width="640" height="360" frameborder="0" allowfullscreen></iframe></p>

### **Arquitetura**

1. **CORE**: backend, em Node.js e SQLite;
2. **GUI**: interface web, em React;
3. **NGUI**: interfaces nativas para Android e iOS, em React Native.

### **Pré-requisitos para execução**

- É necessário ter **[Node.js v16.10.1](https://nodejs.org/en/)** instalado na máquina;
- Além disso, é necessário ter um package manager como **[NPM](https://www.npmjs.com/)** ou **[Yarn](https://yarnpkg.com/)**;
- Por fim, é essencial ter o **[Expo](https://expo.io/)** instalado globalmente na máquina.

1. Clonando o projeto:

```sh
   git clone https://github.com/amintasvrp/be-the-hero.git
```

2. Executando a aplicação:

```sh
  # Instalando dependências do servidor e criando base de dados
  cd core
  yarn
  yarn migrations
  yarn start


  # Instalando dependências e rodando aplicação web
  cd gui
  yarn
  yarn start

  # Instalando dependências e rodando aplicação mobile
  cd ngui
  yarn
  yarn start
```

## Contribuições

Faça um PR e deixe claro quais alterações foram feitas e quais bugs persistem. Não introduza bugs, seja proativo!

## Licenças

- **MIT License** - [_Ver detalhes_](./LICENSE.txt)
