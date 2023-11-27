# V8.1 General Data Protection

## ASVS: 8.1.1

## ASVS Requirement description

Verify the application protects sensitive data from being cached
in server components such as load balancers and application caches.

## User Story

**Feature_Name**: Prevent Data Caching

**Story**:\
As a Security Engineer\
I want the application to protect sensitive data from being cached in server components\
So that we can ensure the confidentiality and integrity of our data

## Scenario

**Scenario_name**: Verifying Data Caching Protection

**Gherkin syntax**:

```gherkin
Given our application's data handling system
When I review the data caching policies
Then it should show that sensitive data is not cached in server components such as load balancers 
and application caches
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/524>
