# V1.6 Cryptographic Architecture

## ASVS: 1.6.3

## ASVS Requirement description

Verify that all keys and passwords are replaceable and are part
of a well-defined process to re-encrypt sensitive data.

## User Story

**Feature_Name**: Cryptographic Key Protection

**Story**:
As a Security Engineer\
I want to ensure that all keys and passwords are replaceable and are part of a well-defined process
to re-encrypt sensitive data\
So that we can maintain the security and integrity of our cryptographic keys and secrets

## Scenario

**Scenario_name**: Implementing a process for cryptographic key and password replacement

**Gherkin syntax**:

```gherkin
Given our application's cryptographic services
When I implement a well-defined process for replacing keys and passwords
And re-encrypt sensitive data using the replaced keys and passwords
Then the security and integrity of our cryptographic keys and secrets are maintained
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