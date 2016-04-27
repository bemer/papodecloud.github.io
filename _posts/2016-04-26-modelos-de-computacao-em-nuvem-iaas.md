---
layout: post
title: Modelos de computação em nuvem - IaaS
description: "Introdução a um dos mais populares modelos de computação em nuvem"
modified: 2016-04-26
category: [IaaS, Introdução]
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


Inicialmente, podemos dividir a computação em nuvem em três modelos de serviço, de acordo com os diferentes níveis de controle, flexibilidade e gerenciamento que cada um deles oferece. 

![Piramide]({{ site.url }}/images/posts/nuvem-piramide.jpg)


>Aqui, trataremos apenas da base da pirâmide: Infraestrutura como Serviço (do inglês Infrastructure as a Service), ou IaaS, como nos referiremos de agora em diante.

À medida que a popularidade dos serviços foi aumentando, novos modelos e estratégias de implantação e oferta de recursos surgiram para atender a necessidades específicas de diferentes tipos de usuários. Esses modelos serão abordados em outros textos.

### Definição

É um modelo de serviços de nuvem onde o provedor de serviços fornece aos consumidores recursos básicos de, normalmente virtualizados, que normalmente compõe a infraestrutura de TI: servidores, espaço para armazenamento de dados e recursos de conectividade. Tais recursos são fornecidos sob demanda, através de um portal de autoatendimento.

Nele, o consumidor é capaz de executar, em teoria, qualquer sistema operacional ou aplicação.
Oferecer recursos facilmente escaláveis e que podem ser ajustados sob demanda torna o IaaS um modelo extremamente atraente para aplicações temporárias, de caráter experimental ou que tem suas necessidades de recursos alteradas de forma inesperada.

Os recursos são pagos conforme seu uso, tipicamente por hora, semana ou mês. Alguns provedores também aplicam cobranças com base na quantidade de recursos alocados, mesmo que não utilizados.

### Responsabilidades

No IaaS, o provedor de serviços é reponsável por parte dos componentes que compoem a infraestrutura: instalações físicas, equipamentos de rede, servidores físicos, storages e o hypervisor.

Todo o restante, a partir do sistema operacional (incluindo o próprio), é de responsabilidade do cliente: bases de dados, frameworks e aplicações, por exemplo.

![Responsabilidade-IaaS]({{ site.url }}/images/posts/responsabilidade-iaas.png)


### Benefícios

- Mais eficiência – os recursos disponibilizados aos consumidores são, comumente, virtualizados e agrupados, garantindo que sua infraestrutura física seja usada no máximo de sua capacidade.
- Mais agilidade – os recursos podem ser provisionados sob demanda e devolvidos ao pool de recursos com a mesma facilidade.
- Rápida escalabilidade – recursos adicionais podem ser alocados instantaneamente para atender às demandas de negócios devido aos momentos de pico e ao crescimento ou declínio da empresa.
- Redução de custos – o uso do modelo de "pagamento conforme o uso" evita despedício de recursos.
- Mais produtividade da equipe de TI – o provisionamento de recursos é automatizado por meio de um portal de autoatendimento.

