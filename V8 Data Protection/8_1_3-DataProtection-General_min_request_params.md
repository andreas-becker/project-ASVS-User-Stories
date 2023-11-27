# V8.1 General Data Protection

## ASVS: 8.1.3

## ASVS Requirement description

Verify the application minimizes the number of parameters in a
request, such as hidden fields Ajax variables, cookies and header
values.

## User Story

**Feature_Name**: Minimize Request Parameters

**Story**:\
As a Security Engineer\
I want the application to minimize the number of parameters in a request\
So that we can reduce the attack surface and enhance the application's security

## Scenario

**Scenario_name**: Verifying Minimization of Request Parameters

**Gherkin syntax**:

```gherkin
Given our application's request handling system
When I review the request parameters
Then it should show that the number of parameters such as hidden fields, Ajax variables, cookies
and header values are minimized
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/233>
