# V11.1 Business Logic Security

## ASVS: 11.1.7

## ASVS Requirement description

Verify that the application monitors for unusual events or
activity from a business logic perspective. For example, attempts
to perform actions out of order or actions which a normal user
would never attempt.
([C9](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Monitoring Unusual Activity

**Story**:\
As a Security Engineer\
I want the application to monitor for unusual events or activities\
So that we can identify and prevent potential security threats

## Scenario

**Scenario_name**: Verifying Monitoring of Unusual Activities

**Gherkin syntax**:

```gherkin
Given our application's operations
When I review the application's monitoring capabilities
Then it should be able to detect unusual events or activities
And it should alert the appropriate personnel when such events or activities are detected
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/754>
