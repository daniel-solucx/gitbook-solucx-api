---
description: >-
  Aiming to provide modern and secure integration, we recommend using the Solucx
  API as the integration method.
---

# Introduction (english)

**Requests and Responses**

All requests are made via the HTTPS protocol and secured through the use of security headers.

API responses strictly follow web standards, returning status codes according to the type of request.

**URL Base**: [https://api.solucx.com.br/public](https://api.solucx.com.br/public)

All requests must be made using the Base URL along with the resource endpoint to be accessed, or more precisely, the URI.

{% content-ref url="seguranca-da-api-1.md" %}
[seguranca-da-api-1.md](seguranca-da-api-1.md)
{% endcontent-ref %}

{% content-ref url="orientacoes-gerais-de-uso-1.md" %}
[orientacoes-gerais-de-uso-1.md](orientacoes-gerais-de-uso-1.md)
{% endcontent-ref %}

![SoluCX API Integration Flows](.gitbook/assets/api-integration.png)

**Glossário**

{% content-ref url="terminologias-comuns-1.md" %}
[terminologias-comuns-1.md](terminologias-comuns-1.md)
{% endcontent-ref %}

#### Allow Method

| Method     | Description                                                    |
| ---------- | -------------------------------------------------------------- |
| **POST**   | Create a new object on the platform.                           |
| **GET**    | Retrieve an object or a list of objects from the platform.     |
| **PUT**    | Update an existing object on the platform using an identifier. |
| **DELETE** | Remove an object from the platform using an identifier.        |

For simplicity, all API calls are made through the base URL [https://api.solucx.com.br/public](https://api.solucx.com.br/public)
