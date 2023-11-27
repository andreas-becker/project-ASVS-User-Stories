# V6.2 Algorithms

## ASVS: 6.2.8

## ASVS Requirement description

Verify that all cryptographic operations are constant-time, with no
'shortcircuit' operations in comparisons, calculations, or returns,
to avoid leaking information.

## User Story

**Feature_Name**: Constant-Time Cryptographic Operations

**Story**:\
As a Security Engineer\
I want to ensure that all our cryptographic operations are constant-time,
with no 'short-circuit' operations in comparisons, calculations or returns\
So that we can prevent information leakage and maintain the security
of our data

## Scenario

**Scenario_name**: Implementing Constant-Time Cryptographic Operations

**Gherkin syntax**:

```gherkin
Given our application's cryptographic operations
When they are being executed
Then they should be constant-time, with no 'short-circuit' operations in comparisons, calculations, or returns
And any potential information leakage should be prevented
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cheatsheetseries.owasp.org/cheatsheets/Cryptographic_Storage_Cheat_Sheet.html> \
<https://cwe.mitre.org/data/definitions/385>
