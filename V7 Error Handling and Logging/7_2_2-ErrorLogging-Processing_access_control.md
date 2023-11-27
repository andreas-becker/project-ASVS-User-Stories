# V7.2 Log Processing

## ASVS: 7.2.2

## ASVS Requirement description

Verify that all access control decisions can be logged and all
failed decisions are logged. This should include requests with
relevant metadata needed for security investigations.

## User Story

**Feature_Name**: Secure Access Control Logging

**Story**:\
As a Security Engineer\
I want the application to log all access control decisions\
So that we can monitor and respond to potential security incidents effectively

## Scenario

**Scenario_name**: Verifying Secure Access Control Logging

**Gherkin syntax**:

```gherkin
Given our application's logging system
When I review the access control logs
Then it should include all decisions made during access control
And it should log all failed decisions
But it should not include sensitive information like session tokens or passwords
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cheatsheetseries.owasp.org/cheatsheets/Logging_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/Logging_Vocabulary_Cheat_Sheet.html> \
<https://cwe.mitre.org/data/definitions/285>
