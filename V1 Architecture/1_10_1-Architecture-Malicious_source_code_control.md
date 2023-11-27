# V1.10 Malicious Software Architecture

## ASVS: 1.10.1

## ASVS Requirement description

Verify that a source code control system is in use, with
procedures to ensure that check-ins are accompanied by issues or
change tickets. The source code control system should have access
control and identifiable users to allow traceability of any changes.

## User Story

**Feature_Name**: Secure Source Code Control

**Story**:
As a Security Engineer\
I want to ensure that a source code control system is in use, with procedures to ensure that 
check-ins are accompanied by issues or change tickets\
So that we can maintain traceability of any changes and enhance the security of our source code

## Scenario

**Scenario_name**: Implementing secure source code control

**Gherkin syntax**:

```gherkin
Given our application's source code control system
When I implement procedures to ensure that check-ins are accompanied by issues or change tickets
Then traceability of any changes is maintained
And the security of our source code is enhanced
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