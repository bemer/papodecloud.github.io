---
layout: post
title: Tipos de nuvem
description: "Quais são os tipos de nuvem existentes."
modified: 2016-04-20
category: [Artigos, Introdução]
tags: [introdução, artigos]
imagefeature: posts/modelos_de_cloud.jpg
comments: true
share: true
featured: true
writer:
  name: Bruno Emer
  avatar: writers/brunoemer.png
  email: brunoemer@gmail.com
  website: www.brunoemer.com.br
  # Use the coder's toolbox at http://coderstoolbox.net/string/#!encoding=xml&action=encode&charset=us_ascii to encode your description into XML string
  description: Cofundador da Omnize e idealizador do Papo de Cloud. Fascinado por tecnologia, música e fotografia. Adora viajar e conhecer novas culturas, culinárias e idiomas. Gosta de futebol americano e torce para os Denver Broncos.
  # Social networking links used in footer. Update and remove as you like.
  twitter: emerbruno
  linkedin: brunoemer
  facebook: brunoemer.5
  instagram: brunoemer_




---



No post anterior, foi possível ter uma visão bem clara a respeito de o que é e para que serve a computação em nuvem. Porém, quando falamos em nuvem, é necessário entender que estamos falando em um conceito que segue algumas regras básicas, baseadas em elasticidade, autoatendimento, acessibilidade, entre outras.

Quando juntamos todas estas regras e pensamos em empresas utilizando estes recursos, podemos ter uma clara visão de que nem todas estas empresas irão se beneficiar da utilização da computação em nuvem da mesma forma, já que para uma empresa de um determinado segmento a utilização de tecnologias específicas faz mais sentido do que para outra. Sendo assim, podemos nos fazer a seguinte pergunta: Como empresas de diferentes segmentos podem, então, se beneficiar dos conceitos e das vantagens que a nuvem oferece? E a resposta para esta pergunta, apesar de parecer complexa, é relativamente simples: existem diferentes modelos de computação nuvem.

Quando falamos em "modelos", estamos nos referindo a diferentes implementações dos recursos que entregarão os serviços e benefícios da nuvem. A seguir, vamos começar listando estes modelos e definindo seu funcionamento e suas principais características.


##Nuvem Pública (Public Cloud)

O conceito de Nuvem Pública é o mais difundido e utilizado atualmente. Uma nuvem pública é basicamente aquela em que os serviços são entregues por um provedor - chamado de Cloud Provider - e todos podem realizar a contratação dos serviços e utilização destes recursos. Um bom exemplo para maior entendimento do conceito de Nuvem Pública é a utilização do provedor de e-mails Gmail. O Gmail é uma aplicação executada nos servidores da Google, e acessível por todos os seus usuários, (inclusive eu) através da internet. Basicamente qualquer pessoa pode realizar a contratação deste serviço e utilizar os recursos computacionais dos datacenters da Google para realizar o envio e o recebimento de e-mails sem se preocupar com a estrutura necessária para isto, uma vez que esta preocupação é apenas da Google. Neste caso, a Google é o nosso Cloud Provider.

Um ponto importante a ser observado no conceito de nuvem pública, é que todas as ferramentas e recursos entregues por um Cloud Provider são padronizados e devem atender a todos os usuários e empresas da mesma maneira: todos os recursos que eu tenho disponíveis no meu Gmail você tem no seu, e todas as atualizações na plataforma atendem a todos os usuários.

Além disto, o modelo de nuvem pública deve sempre levar em conta a separação lógica dos dados dos clientes. O nome dado para o conceito desta separação dos dados baseada em clientes é multi-tenancy. Isto significa que mesmo utilizando os mesmos servidores que você para acessar, enviar, receber e armazenar meus e-mails, eu não conseguirei de forma nenhuma visualizar uma mensagem enviada para ou por você. Todos os provedores de nuvem pública devem possuir este conceito.


##Nuvem Privada (Private Cloud)

Ok Bruno! Eu entendi o conceito de nuvem pública. Mas e se eu trabalhar em uma empresa com 5 mil funcionários e não quiser minha plataforma de e- mails nos servidores do Google, mas ainda assim, quiser disponibilizar recursos elásticos para meus usuários através de uma plataforma web onde eles mesmos poderão criar suas contas e gerenciar as propriedades de suas caixas postais sem que minha equipe de help-desk precise intervir?

Essa pode parecer uma pergunta um tanto quanto incomum, uma vez que existem soluções públicas para praticamente todos os tipos de serviços, porém não é! E, justamente para responder este questionamento e endereçar esta necessidade, existe o modelo de Nuvem Privada.

Uma Nuvem Privada deve ter os mesmos aspectos de uma nuvem pública, em relação a elasticidade, autossuficiência e acessibilidade, porém, toda a gestão de seus recursos (servidores, rede, armazenamento, segurança lógica e física) deve ser executada pela própria empresa que a possui, sendo que seus recursos serão utilizados apenas por seus funcionários.

Basicamente, é como se uma determinada empresa pudesse criar máquinas virtuais em seu datacenter para sua equipe de desenvolvimento da mesma forma que a AWS.


##Nuvem Comunitária (Community Cloud)

A nuvem comunitária é um modelo muito específico de nuvem, que tem o propósito de atingir apenas a um determinado conjunto de organizações em um determinado segmento.

Em um exemplo prático:

Imagine que no Brasil temos 5 mil lojas de calçados, e que todas estas lojas utilizam um mesmo sistema que informa todas as medidas de cada numeração de sapato em todos os países. Este sistema é instalado em um servidor dentro das lojas, e cada loja deve possuir um servidor com sistema instalado.

A ideia da criação de uma nuvem comunitária é justamente instalar este sistema em um único ambiente (que pode até estar dentro de uma destas lojas) e permitir que todas as 5 mil lojas acessem este serviço através da internet.

Obviamente este é um exemplo fictício, mas que nos ajuda a entender o conceito de uma nuvem comunitária: uma estrutura que atende os interesses de um determinado grupo ou segmento no mercado.


##Nuvem híbrida (Hybrid Cloud)

Mas, e quando uma empresa deseja realizar a utilização de mais de um dos modelos anteriores em sua estrutura?

Imagine que uma determinada empresa de calçados que possui uma estrutura de nuvem privada deseja armazenar os backups de sua aplicação em um serviço de armazenamento externo como, por exemplo, o S3 da Amazon.

O que temos neste caso, é o conceito de nuvem híbrida, onde uma empresa realiza a utilização de dois diferentes modelos de nuvem - privada para a criação de seus servidores e pública para o armazenamento de seus backups - em uma estrutura unificada através de diferentes tecnologias que permitem a troca de informações entre os diferentes ambientes.
