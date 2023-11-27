# V1.4 Access Control Architecture

## ASVS: 1.4.4

## ASVS Requirement description

Verify the application uses a single and well-vetted access
control mechanism for accessing protected data and resources.
All requests must pass through this single mechanism to avoid
copy and paste or insecure alternative paths.
([C7](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Single Access Control Mechanism

**Story**:
As a Security Engineer\
I want to ensure that the application uses a single and well-vetted access control mechanism for
accessing protected data and resources\
So that we can avoid insecure alternative paths and maintain the integrity and security of our
system

## Scenario

**Scenario_name**: Enforcing a single access control mechanism

**Gherkin syntax**:

```gherkin
Given our application's access control mechanism
When I enforce this single and well-vetted access control mechanism
Then all requests pass through this single mechanism
And the integrity and security of our system is maintained
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
<https://cwe.mitre.org/data/definitions/284>