# V10.2 Malicious Code Search

## ASVS: 10.2.6

## ASVS Requirement description

Verify that the application source code and third party
libraries do not contain Easter eggs or any other
potentially unwanted functionality.

## User Story

**Feature_Name**: No Unwanted Functionality in Code

**Story**:\
As a Security Engineer\
I want to ensure that the application source code and third-party 
libraries do not contain Easter eggs or any other potentially 
unwanted functionality\
So that we can maintain the integrity of our application and 
protect it from potential threats

## Scenario

**Scenario_name**: Checking for Unwanted Functionality in Code

**Gherkin syntax**:

```gherkin
Given our application's source code and third-party libraries
When I review the code
Then it should not contain any Easter eggs or any other potentially unwanted functionality
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/507>
