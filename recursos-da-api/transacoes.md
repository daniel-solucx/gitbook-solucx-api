# Transações



{% swagger src="https://bitbucket.org/!api/2.0/snippets/solucxteam/GMzg45/files/solucx.yaml" path="/transaction" method="post" %}
[https://bitbucket.org/!api/2.0/snippets/solucxteam/GMzg45/files/solucx.yaml](https://bitbucket.org/!api/2.0/snippets/solucxteam/GMzg45/files/solucx.yaml)
{% endswagger %}



{% swagger src="https://bitbucket.org/!api/2.0/snippets/solucxteam/GMzg45/files/solucx.yaml" path="/transaction/{id}" method="get" %}
[https://bitbucket.org/!api/2.0/snippets/solucxteam/GMzg45/files/solucx.yaml](https://bitbucket.org/!api/2.0/snippets/solucxteam/GMzg45/files/solucx.yaml)
{% endswagger %}

{% swagger src="https://bitbucket.org/!api/2.0/snippets/solucxteam/GMzg45/files/solucx.yaml" path="/transaction" method="delete" %}
[https://bitbucket.org/!api/2.0/snippets/solucxteam/GMzg45/files/solucx.yaml](https://bitbucket.org/!api/2.0/snippets/solucxteam/GMzg45/files/solucx.yaml)
{% endswagger %}

{% swagger src="https://bitbucket.org/!api/2.0/snippets/solucxteam/GMzg45/files/solucx.yaml" path="/transaction/{id}" method="delete" %}
[https://bitbucket.org/!api/2.0/snippets/solucxteam/GMzg45/files/solucx.yaml](https://bitbucket.org/!api/2.0/snippets/solucxteam/GMzg45/files/solucx.yaml)
{% endswagger %}

{% swagger src="https://bitbucket.org/!api/2.0/snippets/solucxteam/GMzg45/files/solucx.yaml" path="/transaction" method="get" %}
[https://bitbucket.org/!api/2.0/snippets/solucxteam/GMzg45/files/solucx.yaml](https://bitbucket.org/!api/2.0/snippets/solucxteam/GMzg45/files/solucx.yaml)
{% endswagger %}

## Usando `transaction_id` para consultas assertivas:

Para a Infraestrutura atual, consultas que somam transações em períodos longos são grande ofensores, pois sobrecarrega nossos servidores e geram lentidão tanto na consulta em questão quanto nas próximas, portanto orienta-se:&#x20;

* Consultas que fazem uma varredura quantitativa (**count**) ou **search** dentro de um intervalo de tempo, que seja usado como parâmetro de busca o **`transaction_id:`**\
  `curl --request GET \`\
  `--url 'https://api.solucx.com.br/public/transaction?`**`token=1&date_to=2024-04-31&date_from=2024-04-01&transactionId=123`**`' \`\
  `--header 'Content-Type: application/json' \`\
  `--header 'x-solucx-api-key:x-solucx-api-key'`
