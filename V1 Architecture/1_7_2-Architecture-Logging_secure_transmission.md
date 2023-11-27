# V1.7 Errors, Logging and Auditing Architecture

## ASVS: 1.7.2

## ASVS Requirement description

Verify that logs are securely transmitted to a preferably remote
system for analysis, detection, alerting, and escalation.
([C9](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Secure Log Transmission

**Story**:
As a Security Engineer\
I want to ensure that logs are securely transmitted to a preferably remote system for analysis,
detection, alerting, and escalation\
So that we can maintain the security and integrity of our system logs.

## Scenario

**Scenario_name**: Implementing secure transmission of logs

**Gherkin syntax**:

```gherkin
Given our system's logging processes
When I implement secure transmission of logs to a remote system
Then the security and integrity of our system logs are maintained
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links