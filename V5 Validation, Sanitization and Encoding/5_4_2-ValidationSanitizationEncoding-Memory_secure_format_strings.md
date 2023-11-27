# V5.4 Memory, String, and Unmanaged Code

## ASVS: 5.4.2

## ASVS Requirement description

Verify that format strings do not take potentially hostile input
and are constant.

## User Story

**Feature_Name**: Secure Format Strings

**Story**:\
As a Security Engineer\
I want to ensure that format strings do not accept potentially harmful input and remain constant\
So that we can prevent potential security vulnerabilities

## Scenario

**Scenario_name**: Verifying security of format strings

**Gherkin syntax**:

```gherkin
Given our application's operations involving format strings
When I review these operations
Then the format strings should not accept potentially harmful input
And they should remain constant
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/134>
