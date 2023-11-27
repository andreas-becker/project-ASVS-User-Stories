## V13.4 GraphQL

## ASVS: 13.4.2

## ASVS Requirement description

Verify that GraphQL or other data layer authorization logic
should be implemented at the business logic layer instead of the
GraphQL layer.

## User Story

**Feature_Name**: Business Logic Layer Authorization

**Story**:\
As a Security Engineer\
I want to ensure that our GraphQL service implements authorization logic at the business logic
layer\
So that we can maintain a secure and efficient data access control

## Scenario

**Scenario_name**: Implementing Authorization Logic at Business Logic Layer

**Gherkin syntax**:

```gherkin
Given our application's GraphQL service
When a query is received
Then the application should implement authorization logic at the business logic layer
And not at the GraphQL layer
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
<https://cwe.mitre.org/data/definitions/285>
