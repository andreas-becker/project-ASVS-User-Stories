# V8.1 General Data Protection

## ASVS: 8.1.2

## ASVS Requirement description

Verify that all cached or temporary copies of sensitive data
stored on the server are protected from unauthorized access or
purged/invalidated after the authorized user accesses the
sensitive data.

## User Story

**Feature_Name**: Prevent Unauthorized Data Caching

**Story**:\
As a Security Engineer\
I want the application to protect all cached or temporary copies of sensitive data stored on the
server\
So that we can prevent unauthorized access and ensure data is purged or invalidated after the
authorized user accesses it

## Scenario

**Scenario_name**: Verifying Protection of Cached Data

**Gherkin syntax**:

```gherkin
Given our application's data handling system
When I review the data caching policies
Then it should show that all cached or temporary copies of sensitive data are protected from
unauthorized access
And it should ensure data is purged or invalidated after the authorized user accesses it
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
