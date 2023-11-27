# V1.9 Communications Architecture

## ASVS: 1.9.2

## ASVS Requirement description

Verify that application components verify the authenticity of
each side in a communication link to prevent person-in-the-middle
attacks. For example, application components should validate TLS
certificates and chains.

## User Story

**Feature_Name**: Authenticity Verification in Inter-Component Communication

**Story**:
As a Security Engineer\
I want to ensure that application components verify the authenticity of each side in a 
communication link\
So that we can prevent person-in-the-middle attacks and maintain the security of our inter-
component communications

## Scenario

**Scenario_name**: Implementing authenticity verification in inter-component communication

**Gherkin syntax**:

```gherkin
Given our application's inter-component communication processes
When I implement authenticity verification for each side in a communication link
Then person-in-the-middle attacks are prevented
And the security of our inter-component communications is maintained
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
<https://cwe.mitre.org/data/definitions/295>