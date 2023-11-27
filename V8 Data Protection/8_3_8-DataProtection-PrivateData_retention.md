# V8.3 Sensitive Private Data

## ASVS: 8.3.7

## ASVS Requirement description

Verify that sensitive personal information is subject to data
retention classification, such that old or out of date data is
deleted automatically, on a schedule, or as the situation requires.

## User Story

**Feature_Name**: Sensitive Data Retention

**Story**:\
As a Security Engineer\
I want sensitive personal information to be subject to data retention classification\
So that old or out of date data is deleted automatically, on a schedule, or as the situation
requires

## Scenario

**Scenario_name**: Verifying Data Retention Policies

**Gherkin syntax**:

```gherkin
Given our application's data handling system
When I review the data retention policies
Then it should show that sensitive personal information is subject to data retention classification
And it should ensure that old or out of date data is deleted automatically, on a schedule, or as 
the situation requires
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/285>
