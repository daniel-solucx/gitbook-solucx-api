---
description: General usage guidelines for consuming the SoluCX API.
---

# General Usage Guidelines

### Access and Authorization:

To consume the SoluCX API, two pieces of information are required:

* Instance API Key (`x-solucx-api-key`)
* API Access Token (`x-solucx-user-token`)

Both are keys that must be included in the request header for authorization on each call.

### Integration Steps:

1- You must obtain a connection key (`x-solucx-api-key`) and a token (`x-solucx-user-token`) for the application from the SoluCX technical team.

{% hint style="warning" %}
Note:**`x-solucx-api-key`**&#x61;nd **`x-solucx-user-token`** are mandatory for all requests
{% endhint %}

2- Create reference stores that will be evaluated by the customer.\
Ex: Stores in a retail chain, department sectors, company divisions.

3- Create employees who are or were involved in the customer experience.\
Ex: Store salesperson, hospital doctor, call center agent.\
Note: If there are no employees to register, create a generic one to associate with the experience.

4- Create the customer who will evaluate the experience.\
Examples: A customer assisted by a store employee, a hospital patient seen by a doctor, a customer supported by a call center agent.

5- Create the transaction or experience, linking all previously created entities.
