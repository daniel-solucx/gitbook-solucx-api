---
description: Orientações de uso gerais sobre o consumo da API SoluCX.
---

# Orientações gerais de uso

### **Acesso e autorização:**

Para consumir a API SoluCX, são necessárias duas informações a saber:

* API Key da instância (x-solucx-api-key)
* Token de acesso da API. (x-solucx-user-token).

O ambos são chaves que deverão ser informada no header para autorização de cada chamada.

### Passos para integração

1- Necessário obter uma chave de conexão (**x-solucx-api-key**) e token (**x-solucx-user-token**) ao aplicativo com a equipe técnica da SoluCX.

{% hint style="warning" %}
**`x-solucx-api-key`**e **`x-solucx-user-token`** são obrigatórios em todas as chamadas
{% endhint %}

2- Criar unidades de referência que serão avaliadas pelo cliente.\
Ex: Lojas de uma rede, setores de departamento, áreas de uma empresa.

3- Criar colaboradores que participam ou participaram da experiência do cliente.\
Ex: Vendedor de uma loja de uma rede, Médico de um hospital, atendente de call center\
Obs: em caso de não ter colaboradores, criar um genérico para informar na experiência

4- Criar o cliente que avaliará a experiência\
Ex: Cliente atendido em uma unidade por um vendedor de uma loja, Paciente de hospital atendido por um médico, Cliente solicitando ajuda em call center a um atendente.

5- Criar a transação ou experiência, juntando todas as entidades criadas anteriormente
