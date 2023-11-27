# V1.5 Input and Output Architecture

## ASVS: 1.5.4

## ASVS Requirement description

Verify that output encoding occurs close to or by the interpreter
for which it is intended.
([C4](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Secure Output Encoding

**Story**:
As a Security Engineer\
I want to ensure that output encoding occurs close to or by the interpreter for which it is
intended\
So that we can prevent injection attacks and maintain the integrity and confidentiality of our
data

## Scenario

**Scenario_name**: Implementing secure output encoding

**Gherkin syntax**:

```gherkin
Given our application's output processes
When I implement encoding close to or by the interpreter for which it is intended
Then injection attacks are prevented
And the integrity and confidentiality of our data is maintained
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
<https://cwe.mitre.org/data/definitions/116>