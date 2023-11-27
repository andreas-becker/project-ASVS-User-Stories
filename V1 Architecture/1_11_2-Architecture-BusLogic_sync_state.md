# V1.11 Business Logic Architecture

## ASVS: 1.11.2

## ASVS Requirement description

Verify that all high-value business logic flows, including
authentication, session management and access control, do not
share unsynchronized state.

## User Story

**Feature_Name**: Synchronized State Management

**Story**:
As a Security Engineer\
I want to ensure that high-value business logic flows, such as authentication, session management,
and access control, do not share unsynchronized state\
So that we can maintain the integrity and security of our application

## Scenario

**Scenario_name**: Verifying synchronized state in business logic flows

**Gherkin syntax**:

```gherkin
Given our application's high-value business logic flows
When I review their state management
Then they should not share an unsynchronized state
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
<https://cwe.mitre.org/data/definitions/362>