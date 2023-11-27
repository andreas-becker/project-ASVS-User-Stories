# V5.4 Memory, String, and Unmanaged Code

## ASVS: 5.4.3

## ASVS Requirement description

Verify that sign, range, and input validation techniques are used
to prevent integer overflows.

## User Story

**Feature_Name**: Integer Overflow Prevention

**Story**:\
As a Security Engineer\
I want the application to use sign, range, and input validation techniques\
So that we can prevent integer overflows

## Scenario

**Scenario_name**: Verifying prevention of integer overflows

**Gherkin syntax**:

```gherkin
Given our application's operations that involve integers
When I review these operations
Then they should use sign, range, and input validation techniques
And these techniques should effectively prevent integer overflows
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/190>
