# V1.6 Cryptographic Architecture

## ASVS: 1.6.2

## ASVS Requirement description

Verify that consumers of cryptographic services protect key
material and other secrets by using key vaults or API based
alternatives.

## User Story

**Feature_Name**: Cryptographic Key Protection

**Story**:
As a Security Engineer\
I want to ensure that consumers of cryptographic services protect key material and other secrets 
by using key vaults or API based alternatives\
So that we can maintain the security and integrity of our cryptographic keys and secrets

## Scenario

**Scenario_name**: Implementing protection for cryptographic key material and secrets

**Gherkin syntax**:

```gherkin
Given our application's cryptographic services
When I implement protection for key material and other secrets using key vaults or API based
alternatives
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