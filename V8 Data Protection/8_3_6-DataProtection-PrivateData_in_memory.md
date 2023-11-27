# V8.3 Sensitive Private Data

## ASVS: 8.3.6

## ASVS Requirement description

Verify that sensitive information contained in memory is
overwritten as soon as it is no longer required to mitigate
memory dumping attacks, using zeroes or random data.

## User Story

**Feature_Name**: Overriding Sensitive Data in Memory

**Story**:\
As a Security Engineer\
I want sensitive information in memory to be overwritten as soon as it is no longer required\
So that we can mitigate memory dumping attacks

## Scenario

**Scenario_name**: Verifying Overwriting of Sensitive Data in Memory

**Gherkin syntax**:

```gherkin
Given our application's data handling system
When I review the memory management
Then it should show that sensitive information is overwritten as soon as it is no longer required
And it should use zeroes or random data for overwriting
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/226>
