# V1.4 Access Control Architecture

## ASVS: 1.4.5

## ASVS Requirement description

Verify that attribute or feature-based access control is used
whereby the code checks the user's authorization for a feature/
data item rather than just their role. Permissions should still
be allocated using roles.
([C7](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Attribute or Feature-Based Access Control

**Story**:
As a Security Engineer\
I want to ensure that attribute or feature-based access control is used, whereby the code checks
the user's authorization for a feature/data item rather than just their role\
So that we can maintain a granular level of access control while still allocating permissions 
using roles

## Scenario

**Scenario_name**: Implementing attribute or feature-based access control

**Gherkin syntax**:

```gherkin
Given our system's access control mechanism
When I implement attribute or feature-based access control
Then the user's authorization for a feature/data item is checked rather than just their role
And permissions are still allocated using roles
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
<https://cwe.mitre.org/data/definitions/275>