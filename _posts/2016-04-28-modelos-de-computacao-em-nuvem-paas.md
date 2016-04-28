---
layout: post
title: Modelos de computação em nuvem - PaaS
description: "Modelo de computação em nuvem ideal para desenvolvedores"
modified: 2016-04-26
category: [PaaS, Introdução]
tags: [introdução, artigos]
imagefeature:
comments: true
share: true
featured: false
writer: 
  name: Gilmar Machado
  avatar: writers/gilmarmachado.png
  email: 
  website: gmts.me
  description: Analista de infraestrutura na Universidade de São Paulo e co-criador do Papo de Cloud. Acredita que a melhor solução é a que resolve o problema, estuda tudo o que encontra sobre web-scale IT e assiste a qualquer modalidade de esporte, apesar de não praticar nenhum.
  # Contato
  twitter: gilmarmts
  linkedin: gilmarmts
  facebook: gilmarmts

---

Aqui, será abordado o modelo que fica entre o SaaS (que será tratado em outra oportunidade) e IaaS: o PaaS – Platform as a Service (em português, Plataforma como Serviço):

![Piramide]({{ site.url }}/images/posts/nuvem-piramide.jpg)

###Definição

É um modelo que fornece plataformas e ambientes utilizados no desenvolvimento de aplicações e serviços que serão distribuídos pela internet. Novamente, os serviços oferecidos nesse modelo são hospedados pelo provedor de serviços e acessados pelos usuários pela internet, comumente através de um navegador.


###Responsabilidades

Nesse modelo, além dos componentes básicos que compoe a infraestrutura (instalações físicas, equipamentos de rede, servidores físicos, storages, hypervisors), o provedor de serviços também é responsável pelas plataformas e ambientes utilizados no desenvolvimento e hospedagem de aplicações, incluindo itens como sistemas operacionais, ambientes de scripting server-side, sistemas de gerenciamento de bancos de dados, ferramentas de hospedagem de aplicações, entre outros.

O consumidor do serviço, aqui, é responsável apenas pelas aplicações desenvolvidas por ele utilizando as ferramentas fornecidas.

![Responsabilidade-PaaS]({{ site.url }}/images/posts/responsabilidade-paas.png)

###Benefícios

Abaixo, alguns dos benefícios do modelo PaaS para desenvolvedores de aplicações.


- Sem necessidade de investimento em infraestrutura física; ser capaz de “alugar” infraestrutura virtual tem benefícios financeiros e práticos. Não existe a necessidade de comprar ou sequer gerenciar hardware, permitindo que os clientes foquem-se somente no desenvolvimento de aplicações.
- Torna o desenvolvimento de aplicações mais “simples”; algumas ofertas de PaaS simplificam e facilitam o desenvolvimento e a implementação de aplicações utilizando automações e funções “one-click”, permitindo que mesmo clientes menos experientes sejam capazes de utilizar os serviços fornecidos.
- Flexibilidade e adaptabilidade; os clientes podem escolher as ferramentas que desejam utilizar e criar ambientes personalizados para as necessidades específicas de cada aplicação, além de alterá-las se as circunstâncias exigirem.
- Colaboração em tempo real; normalmente, uma conexão à Internet e um navegador são tudo o que um cliente precisa para utilizar os serviços fornecidos, e clientes ao redor do mundo podem facilmente trabalhar juntos

