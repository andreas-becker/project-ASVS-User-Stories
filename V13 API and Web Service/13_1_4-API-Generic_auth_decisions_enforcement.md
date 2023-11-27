# V13.1 Generic Web Service Security

## ASVS: 13.1.4

## ASVS Requirement description

Verify that authorization decisions are made at both the URI,
enforced by programmatic or declarative security at the controller
or router, and at the resource level, enforced by model-based
permissions.

## User Story

**Feature_Name**: Authorization Decisions Enforcement

**Story**:\
As a Security Engineer\
I want to ensure that authorization decisions are made at both the URI and resource level\
So that we can maintain a secure access control in our application

## Scenario

**Scenario_name**: Enforcing Authorization Decisions

**Gherkin syntax**:

```gherkin
Given our application's access control mechanisms
When a user attempts to access a resource
Then the application should make authorization decisions at the URI level
And also at the resource level
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
<https://cwe.mitre.org/data/definitions/285>
