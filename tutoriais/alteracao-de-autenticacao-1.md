# Authentication Update

To upgrade to a more secure authentication method, only one change is required. All objects, resources, and responses remain the same:

* It is **mandatory** to provide the user token in the request header as `x-solucx-user-token`, as described in the **General Usage Guidelines**.

{% hint style="info" %}
It is **no longer necessary** — and **strongly discouraged** — to pass the token via URL (query string).
{% endhint %}
