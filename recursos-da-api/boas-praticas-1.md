---
description: Best Practices Manual for API Usage
---

# Best Practices

Passive APIs are essential for integration and communication between systems and services. This manual aims to establish clear guidelines and best practices for the proper and efficient use of passive APIs, ensuring security, reliability, and performance across all integrated systems.

## 1. Understanding the API

* Before using a passive API, it is crucial to review its official documentation, including available endpoints, authentication methods, rate limits, request parameters, and response formats.

## 2. Authentication and Authorization

* Always use appropriate authentication methods such as API keys or access tokens, as specified in the API documentation.
* Keep authentication credentials secure and avoid unnecessary sharing.

To consume the SoluCX API, two credentials are required:

* Instance API Key (`x-solucx-api-key`)
* API Access Token (`x-solucx-user-token`)

Both must be included in the header for authorization on each request.

### Integration Steps:

* &#x20;Obtain a connection key (`x-solucx-api-key`) and access token (`x-solucx-user-token`) from the SoluCX technical team.
* x-solucx-api-key and x-solucx-user-token, are required for every request.
* &#x20;Create reference stores that will be evaluated by the customer. _E.g.: Retail stores, departments, or business units._
* &#x20;Register employees who participate or have participated in the customer experience. _E.g.: Salesperson, hospital doctor, call center agent._ Note: If there are no specific employees, create a generic employee to associate with the experience.
* Register the customer who will respond to the survey. _E.g.: A customer served by a store employee, a hospital patient assisted by a doctor, a call center customer._
* Create the transaction or experience by linking all the entities created above.

## 3. Respecting Query Limits:



* Be aware of the API’s rate limits to avoid overloading the server. If queries made through the integration exceed a healthy threshold, our team will contact you to help optimize usage.
* Implement mechanisms to gracefully handle rate limit errors.

Due to the current infrastructure, queries that involve long time periods of transactions can severely impact performance. This may cause slow responses for current and subsequent queries. We recommend using the `transaction_id` field, detailed in the transactions section.

## 4. Data Handling:

* Always validate input data before sending requests to the passive API.
* Process and interpret API responses properly, considering both success and error scenarios.

## 5. Monitoring and Logging:

* Implement monitoring systems to track the performance and reliability of API calls.
* Log all interactions with the API appropriately to facilitate debugging and issue resolution.

## 6. Security:

* Use secure connections (HTTPS) for all communication with the API.
* Consider implementing additional security practices such as encryption of sensitive data and message signing.

## 7. Maintenance and Updates:

* Stay up to date with API changes by regularly checking for updates and new versions.
* Be prepared to handle deprecated features and necessary behavior adjustments.

## 8. Internal Documentation:

* Maintain detailed internal documentation on the API integration, including code samples, configuration steps, and troubleshooting procedures

## Conclusion:

Responsible and efficient use of passive APIs is key to ensuring system interoperability and successful service delivery. By following the best practices outlined in this manual, you contribute to the stability, security, and performance of your passive API integrations.

\
