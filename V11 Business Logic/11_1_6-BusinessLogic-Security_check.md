# V11.1 Business Logic Security

## ASVS: 11.1.6

## ASVS Requirement description

Verify that the application does not suffer from "Time Of Check
to Time Of Use" (TOCTOU) issues or other race conditions for
sensitive operations.

## User Story

**Feature_Name**: Business Logic Security Check

**Story**:\
As a Security Engineer\
I want to ensure that our application is free from "Time Of Check to Time Of Use" (TOCTOU) issues
and other race conditions\
So that we can maintain the security and integrity of our application operations

## Scenario

**Scenario_name**: Verifying Absence of TOCTOU Issues and Race Conditions

**Gherkin syntax**:

```gherkin
Given our application's operations
When I review the application's handling of sensitive operations
Then it should not suffer from "Time Of Check to Time Of Use" (TOCTOU) issues
And it should not have other race conditions
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/367>
