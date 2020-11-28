# Como podemos criar um assistente virtual para a educação, que se comporte de maneira humanizada? 


> **SE** existisse um robô *chat based* que pudesse responder perguntas sobre educação

> **ENTÃO** poderíamos torná-lo um assistente de Secretarias e Diretorias de ensino

> **ASSIM** conseguiríamos distribuir informativos, formação de professores e políticas públicas

## Contexto

Existe uma grande falta de articulação entre Secretarias, Diretorias e os professores que estão na sala de aula. Ferramentas de comunicação como circulares e e-mails não são efetivas, não informam o emissor se a mensagem foi recebida e tampouco possuem o alcance desejado. Por outro lado, no Brasil, ferramentas de chat como Whatsapp e Telegram figuram entre as mais utilizadas, tanto em dispositivos Android quanto iPhone. 

## Restrições 

Atualmente, existem alguns gargalos: 

- WhatsApp possui uma API paga e restritiva
- Telegram não é uma ferramenta amplamente conhecida

## A ideia 

Criar um robô que seja agnóstico em termos de conteúdo, mas que possa servir como ponte entre órgãos de gestão e seus equipamentos coordenados, como Secretarias/Diretorias e Escolas. 

## Arquitetura

![Arquitetura do projeto Maritaca](https://github.com/msbhv-club/awe-inspiring/blob/main/images/maritaca_arch.jpg?raw=true)

## Tecnologias 

---
**NodeJS**

Javascript que roda no servidor. Simples assim.

https://nodejs.org/

---
**Sequelize**

ORM para bancos relacionais.

https://sequelize.org/

---
**Mongoose**

ODM para MongoDB.

https://mongoosejs.com/

---
**Redis**

*Cache e Session storage in memory* que é rápido e funcional.

https://redis.io/

---
**Postgres**

Banco de dados realacional focado em performance e aplicações de larga escala.

https://www.postgresql.org/

---
**MongoDB**

Banco de dados não-realacional simples e rápido.

https://www.mongodb.com/

---


— metadatada —

```
Autor: @msoledade
Data: 28-nov-20
```



