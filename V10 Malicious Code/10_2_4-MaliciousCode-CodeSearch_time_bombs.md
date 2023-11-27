# V10.2 Malicious Code Search

## ASVS: 10.2.4

## ASVS Requirement description

Verify that the application source code and third party
libraries do not contain time bombs by searching for
date and time related functions.

## User Story

**Feature_Name**: Time Bomb Detection

**Story**:\
As a Security Engineer\
I want to ensure that the application source code and third-party
libraries do not contain time bombs by searching for date and time
related functions\
So that we can prevent any hidden functionality that could be used
maliciously if discovered

## Scenario

**Scenario_name**: Checking for Time Bombs in Code

**Gherkin syntax**:

```gherkin
Given our application's source code and third-party libraries
When I review the code
Then it should not contain any time bombs by searching for date and time related functions
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/511>
