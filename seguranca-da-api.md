---
description: >-
  Esta seção descreve alguns aspectos relacionados a segurança do ambiente  e da
  plataforma SoluCX.
---

# Segurança da API

**Segurança do ambiente**

Todos os sistemas da SoluCX ficam hospedados na Cloud do Google, de forma que esteja sempre disponível e escalável.

**Segurança nas integrações**

Todas as integrações somente são permitidas por meio da passagem de um api-key e user-token no cabeçalho de cada requisição.&#x20;

**Segurança dos dados**

A SoluCX está totalmente _Compliance_ com as novas regras de LGPD e com base nisto, cuida com muito rigor da segurança dos dados de seus clientes.

Toda informação trafegada é criptografada através de SSL e armazenada em bases seguras dentro da infraestrutura do Google.

Todas as requisições são estabelecidas com base em api-key e user-token que deve ser informado no cabeçalho de cada _request_ .
