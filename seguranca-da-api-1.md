---
description: >-
  This section outlines key aspects related to the security of the SoluCX
  environment and platform.
---

# API Security

**Environment Security**

All SoluCX systems are hosted on Google Cloud, ensuring high availability and scalability at all times.

**Integration Security**

All integrations are strictly authorized via the use of an API-KEY and USER-TOKEN, both of which must be included in the header of each request.

**Data Security**

SoluCX is fully _Compliance_ with LGPD (Brazilian General Data Protection Law) and, based on that, enforces strict control over the security of customer data.

All data in transit is encrypted via SSL and stored in secure databases within Google’s infrastructure.

All requests are authenticated using the API-KEY and USER-TOKEN, which must be included in the header of every _request_.
