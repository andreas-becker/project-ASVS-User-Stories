# V14.2 Dependency

## ASVS: 14.2.6

## ASVS Requirement description

Verify that the attack surface is reduced by sandboxing or
encapsulating third party libraries to expose only the required
behaviour into the application.
([C2](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Reducing Attack Surface

**Story**:
As a Security Engineer\
I want to ensure that third-party libraries used in our application are sandboxed or encapsulated\
So that only the required behavior is exposed, reducing the attack surface of our application

## Scenario

**Scenario_name**: Verifying Sandboxing of Third-Party Libraries

**Gherkin syntax**:

```gherkin
Given our application that uses third-party libraries
When a new library is added to the application
Then it should be sandboxed or encapsulated
And only the required behavior should be exposed to the application
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/265>
