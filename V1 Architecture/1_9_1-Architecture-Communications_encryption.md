# V1.9 Communications Architecture

## ASVS: 1.9.1

## ASVS Requirement description

Verify the application encrypts communications between components,
particularly when these components are in different containers,
systems, sites, or cloud providers.
([C3](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Secure Inter-Component Communication

**Story**:
As a Security Engineer\
I want to ensure that the application encrypts communications between components, especially when
these components are in different containers, systems, sites, or cloud providers\
So that we can maintain the confidentiality and integrity of our data during transit

## Scenario

**Scenario_name**: Implementing secure inter-component communication

**Gherkin syntax**:

```gherkin
Given our application's inter-component communication processes
When I implement encryption for communications between components
Then the confidentiality and integrity of our data during transit are maintained
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
<https://cwe.mitre.org/data/definitions/319>