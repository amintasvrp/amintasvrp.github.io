---
layout: post
title: "OpenStack: Implantação em uma cloud privada."
description: Utilizando o OpenStack para realizar o deploy de uma aplicação web/mobile.
date: 2023-08-07 17:30:00 -0300
image: "/images/OPENSTACK.png"
image_square: "/images/OPENSTACK_SQUARE.png"
tags: [project, sysadmin, openstack, docker, nodejs, react]
tags_color: "#b25642"
techs:
  - { label: "OpenStack", name: "openstack", color: "#ED1944" }
  - { label: "Docker", name: "docker", color: "#46a2f1" }
  - { label: "Node.js", name: "nodejs", color: "#43853d" }
  - { label: "React", name: "react", color: "#45b8d8" }
---

## Começando com a atividade

<p><iframe src="https://dms.licdn.com/playlist/vid/C4E05AQEk2--ALPe6Gg/mp4-720p-30fp-crf28/0/1622385706187?e=1692370800&v=beta&t=uXuEE99ptqxvSr-FYGPgruQ7v3b9oHTnXiTdhWGhJWA" loading="lazy" width="640" height="360" frameborder="0" allowfullscreen></iframe></p>

Foi realizado o deploy de uma aplicação anteriormente desenvolvida por mim. Utilizou-se o modelo de cloud privada OpenStack, porém o mesmo planejamento se aplica a outros provedores, como a Azure ou a AWS.

### Sobre a aplicação

A aplicação implantada é o Be The Hero: uma plataforma web que conecta ONGs a pessoas interessadas em contribuir com causas.

## Serviços OpenStack

Para o deploy, foram utilizados os serviços:

- **Nova** e **Glance**, para subir uma máquina virtual _Debian 10_, a qual vai hospedar os contêineres _Docker_ referentes aos módulos da aplicação;
- **Cinder**, para adicionar à VM um volume para persistência de dados;
- **Neutron**, para criar uma subrede com roteador, garantindo acesso à VM pela web de forma restrita.

## Contribuições

O resultado final pode ser observado no vídeo acima, e sugestões de melhorias são bem-vindas.

## Licenças

- **MIT License** - [_Ver detalhes_](./LICENSE.txt)
