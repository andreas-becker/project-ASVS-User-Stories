# V14.2 Dependency

## ASVS: 14.2.4

## ASVS Requirement description

Verify that third party components come from pre-defined, trusted
and continually maintained repositories.
([C2](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Trusted Third-Party Components

**Story**:
As a Security Engineer\
I want to ensure that all third-party components used in our application come from pre-defined,
trusted, and continually maintained repositories\
So that we can maintain the integrity and security of our application

## Scenario

**Scenario_name**: Verifying Source of Third-Party Components

**Gherkin syntax**:

```gherkin
Given our application that uses third-party components
When a new component is added to the application
Then it should be downloaded from a pre-defined, trusted, and continually maintained repository
And the integrity of the downloaded component should be verified
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/829>
