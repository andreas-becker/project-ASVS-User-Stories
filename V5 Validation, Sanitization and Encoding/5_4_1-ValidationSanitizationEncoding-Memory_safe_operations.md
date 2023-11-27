# V5.4 Memory, String, and Unmanaged Code

## ASVS: 5.4.1

## ASVS Requirement description

Verify that the application uses memory-safe string, safer memory
copy and pointer arithmetic to detect or prevent stack, buffer or
heap overflows.

## User Story

**Feature_Name**: Memory-Safe Operations

**Story**:\
As a Security Engineer\
I want the application to use memory-safe string operations, safer memory copy and pointer
arithmetic\
So that we can detect or prevent stack, buffer, or heap overflows

## Scenario

**Scenario_name**: Verifying use of memory-safe operations

**Gherkin syntax**:

```gherkin
Given our application's operations involving strings, memory copy and pointer arithmetic
When I review these operations
Then they should be memory-safe
And they should be capable of detecting or preventing stack, buffer, or heap overflows
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/120>
