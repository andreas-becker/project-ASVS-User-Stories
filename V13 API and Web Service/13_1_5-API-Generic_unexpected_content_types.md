# V13.1 Generic Web Service Security

## ASVS: 13.1.5

## ASVS Requirement description

Verify that requests containing unexpected or missing content
types are rejected with appropriate headers (HTTP response
status 406 Unacceptable or 415 Unsupported Media Type).

## User Story

**Feature_Name**: Handling Unexpected Content Types

**Story**:\
As a Security Engineer\
I want the application to reject requests with unexpected or missing content types\
So that we can maintain the integrity and security of our application data

## Scenario

**Scenario_name**: Rejecting Requests with Unexpected Content Types

**Gherkin syntax**:

```gherkin
Given our application's request handling system
When a request is received
Then the application should check the content type of the request
And reject the request if the content type is unexpected or missing
And respond with appropriate headers (HTTP response status 406 Unacceptable or 415 Unsupported Media Type)
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cheatsheetseries.owasp.org/cheatsheets/Web_Service_Security_Cheat_Sheet.html>
<https://cheatsheetseries.owasp.org/cheatsheets/Server_Side_Request_Forgery_Prevention_Cheat_Sheet.html>
<https://cwe.mitre.org/data/definitions/434>
