# V1.2 Authentication Architecture

## ASVS: 1.2.2

## ASVS Requirement description

Verify that communications between application components,
including APIs, middleware and data layers, are authenticated.
Components should have the least necessary privileges needed.
([C3](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Authenticated Inter-Component Communication

**Story**:
As a Security Engineer\
I want to ensure that all communications between application components, including APIs, middleware,
and data layers, are authenticated\
So that we can maintain the integrity and confidentiality of our data and services

## Scenario

**Scenario_name**: Implementing authenticated communication between application components

**Gherkin syntax**:

```gherkin
Given our application components, services, and servers
When I implement authentication for all inter-component communications
Then the integrity and confidentiality of our data and services are maintained
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
<https://cwe.mitre.org/data/definitions/306>