# V1.6 Cryptographic Architecture

## ASVS: 1.6.4

## ASVS Requirement description

Verify that the architecture treats client-side secrets -such as
symmetric keys, passwords or API tokens- as insecure and never
uses them to protect or access sensitive data.

## User Story

**Feature_Name**: Client-Side Secrets Protection

**Story**:
As a Security Engineer\
I want to ensure that the architecture treats client-side secrets -such as symmetric keys,
passwords, or API tokens- as insecure and never uses them to protect or access sensitive data\
So that we can maintain the security and integrity of our system and data

## Scenario

**Scenario_name**: Implementing protection for client-side secrets

**Gherkin syntax**:

```gherkin
Given our application's client-side secrets
When I treat these secrets as insecure
And ensure they are never used to protect or access sensitive data
Then the security and integrity of our system and data are maintained
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
<https://cwe.mitre.org/data/definitions/320>