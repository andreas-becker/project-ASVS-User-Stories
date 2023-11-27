# V3.5 Token-based Session Management

## ASVS: 3.5.2

## ASVS Requirement description
Verify the application uses session tokens rather than static API
secrets and keys, except with legacy implementations.

## User Story

**Feature_Name**: Session Token Usage

**Story**:\
As a Security Engineer\
I want to ensure that the application uses session tokens instead of static API secrets and keys,
except in the case of legacy implementations\
So that we can enhance the security of our application and prevent unauthorized access

## Scenario

**Scenario_name**: Verifying usage of session tokens over static API secrets and keys

**Gherkin syntax**:

```gherkin
Given our application's authentication process
When I review the type of tokens used
Then they should be session tokens instead of static API secrets and keys
Except in the case of legacy implementations
```

## External links

<https://cwe.mitre.org/data/definitions/798>