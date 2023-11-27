# V8.3 Sensitive Private Data

## ASVS: 8.3.5

## ASVS Requirement description

Verify accessing sensitive data is audited (without logging the
sensitive data itself), if the data is collected under relevant 
data protection directives or where logging of access is required.

## User Story

**Feature_Name**: Sensitive Data Management

**Story**:\
As a Security Engineer\
I want to identify and manage all sensitive data in the application\
So that we can ensure a secure and standardized approach to sensitive data

## Scenario

**Scenario_name**: Auditing Access to Sensitive Data

**Gherkin syntax**:

```gherkin
Given our application's data handling system
When I review the access logs
Then it should show that access to sensitive data is audited
But it should not log the sensitive data itself
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/532>
