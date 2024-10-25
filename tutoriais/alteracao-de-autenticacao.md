# Alteração de autenticação

Para atualizar a autenticação para forma mais segura é necessário apenas uma mudança. Todas os objetos, recursos e respostas são os mesmos:

* Obrigatório informar o **token** de usuário na header das requisição como `x-solucx-user-token` conforme descrito em [Orientações gerais de uso](../orientacoes-gerais-de-uso.md#passos-para-integracao)

{% hint style="info" %}
Não é mais necessário e é desaconselhado informar o **token** por url (query string)&#x20;
{% endhint %}
