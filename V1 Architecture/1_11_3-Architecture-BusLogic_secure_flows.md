# V1.11 Business Logic Architecture

## ASVS: 1.11.3

## ASVS Requirement description

Verify that all high-value business logic flows, including 
authentication, session management and access control are 
thread safe and resistant to time-of-check and time-of-use 
race conditions.

## User Story

**Feature_Name**: Secure Business Logic Flows

**Story**:
As a Security Engineer\
I want to ensure that our application's key operations are secure and reliable\
So that our users can trust our application and we can prevent any potential security issues

## Scenario

**Scenario_name**: Ensuring Security in Key Operations

**Gherkin syntax**:

```gherkin
Given our application's key operations
When I review their implementation
Then they should be secure and reliable
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