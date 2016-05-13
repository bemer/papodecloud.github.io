---
layout: post
title: Modelos de computação em nuvem - SaaS
description: "O mais difundido modelo de computação em nuvem"
modified: 2016-05-13
category: [SaaS, Introdução]
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

Após abordarmos os modelos IaaS e PaaS, falaremos agora sobre o topo da pirâmide, de maior participação no mercado de computação em nuvem e também o de maior taxa de crescimento: o SaaS - Software as a Service (Software como Serviço, em português).

![Piramide]({{ site.url }}/images/posts/nuvem-piramide.jpg)

### Definiçao

Nesse modelo, aplicações gerenciadas pelos provedores de computação em nuvem são entregues aos consumidores via web. A maioria das aplicações entregues no modelo SaaS podem ser executadas diretamente de um navegador web, sem necessidade de downloads ou instalações.

### Responsabilidades


Aqui, o provedor de serviços é responsável por todas as camadas que compõe a aplicação. Instalações elétricas, hardware, SOs, hypevisors, bases de dados, interface de usuário, etc. 

Ao consumidor só basta utilizar a aplicação - e pagar por ela, claro.


![Responsabilidade-SaaS]({{ site.url }}/images/posts/responsabilidade-saas.png)


### Benefícios

Devido ao modelo de entrega de aplicações pela Internet, o modelo SaaS elimina a necessidade dos consumidores de instalar, gerenciar e executar as aplicações em servidores próprios (ou mesmo utilizando o modelo IaaS). 

Não ter que gerenciar todas as camadas que compõe as aplicações torna os processos de manutenção e suporte dos consumidores extremamente simplificado.

Outros benefícios do modelo são:

- Pagamento simplificado - Ao invés de ter que comprar licenças de instalação e suporte de software e hardware, os consumidores precisam apenas se inscrever para utilizar as aplicações. O modelo SaaS segue a mesma forma de cobrança comum aos serviços de computação em nuvem, onde o consumidor paga apenas pelo que consome - comumente em cobranças mensais. Além disso, é possível encerrar a assinatura e deixar de utilizar e pagar pela aplicação a qualquer momento.
- Escalabilidade - Assim como outros modelos, aplicações fornecidas no modelo SaaS oferecem alta escalabilidade, permitindo aos consumidores utilizarem mais ou menos recursos e características de acordo com a demanda.
- Atualizações automáticas - Não há a necessidade de comprar novas versões das aplicações. O provedor de serviços é responsável por implementá-las e disponibilizá-las a todos os consumidores.
- Acessibilidade - Por serem disponibilizadas via Internet e demandar somente um navegador web (normalmente), os clientes podem utilizar as aplicações de qualquer lugar, utilizando qualquer dispositivo com acesso à Internet.


### Desvantagens

Como nem tudo é perfeito, o modelo também apresenta desvantagens. Nele, os consumidores são obrigados a confiar nos fornecedores para manter as aplicações disponívels e atualizadas, calcular os custos dos recursos consumidos com precisão e manter as informações dos clientes num ambiente seguro e livre de falhas.

Provedores de serviços, aliás, que estão sempre suscetíveis a interrupções ou mudanças nos serviços oferecidos, vazamento de dados, falhas de segurança ou qualquer outra questão que impeça os consumidores de utilizar os serviços contratados.

Cabe aos consumidores avaliarem os benefícios e os riscos que o modelo (ou qualquer outro) traz, ficarem atentos aos aos contratos e SLAs e garantir que sejam cumpridos.


