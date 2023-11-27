## V13.4 GraphQL

## ASVS: 13.4.1

## ASVS Requirement description

Verify that a query allow list or a combination of depth limiting
and amount limiting is used to prevent GraphQL or data layer
expression Denial of Service (DoS) as a result of expensive,
nested queries. For more advanced scenarios, query cost analysis
should be used.

## User Story

**Feature_Name**: Preventing GraphQL DoS Attacks

**Story**:\
As a Security Engineer\
I want to implement measures to prevent Denial of Service (DoS) attacks on our GraphQL service\
So that our application remains available and responsive to legitimate users

## Scenario

**Scenario_name**: Preventing Expensive, Nested Queries

**Gherkin syntax**:

```gherkin
Given our application's GraphQL service
When a query is received
Then the application should check if the query is on the allow list
And limit the depth and amount of the query
And use query cost analysis for more complex scenarios
And reject the query if it could result in a Denial of Service (DoS) attack
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cheatsheetseries.owasp.org/cheatsheets/GraphQL_Cheat_Sheet.html>\
<https://cheatsheetseries.owasp.org/cheatsheets/REST_Assessment_Cheat_Sheet.html>\
<https://cheatsheetseries.owasp.org/cheatsheets/REST_Security_Cheat_Sheet.html>\
<https://cwe.mitre.org/data/definitions/770>
