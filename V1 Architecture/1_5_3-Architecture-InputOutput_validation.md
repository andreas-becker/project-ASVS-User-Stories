# V1.5 Input and Output Architecture

## ASVS: 1.5.3

## ASVS Requirement description

Verify that input validation is enforced on a trusted service
layer.
([C5](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Enforced Input Validation

**Story**:
As a Security Engineer\
I want to ensure that input validation is enforced on a trusted service layer\
So that we can maintain the integrity and security of our system by preventing invalid or malicious
data from being processed

## Scenario

**Scenario_name**: Enforcing input validation on a trusted service layer

**Gherkin syntax**:

```gherkin
Given our system's trusted service layer
When I enforce input validation
Then invalid or malicious data is prevented from being processed
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
<https://cwe.mitre.org/data/definitions/602>