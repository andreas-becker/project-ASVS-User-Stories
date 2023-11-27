# V7.2 Log Processing

## ASVS: 7.2.1

## ASVS Requirement description

Verify that all authentication decisions are logged, without
storing sensitive session tokens or passwords. This should include
requests with relevant metadata needed for security investigations.

## User Story

**Feature_Name**: Secure Authentication Logging

**Story**:\
As a Security Engineer\
I want the application to log all security-relevant events\
So that we can monitor and respond to potential security incidents effectively

## Scenario

**Scenario_name**: Verifying Secure Authentication Logging

**Gherkin syntax**:

```gherkin
Given our application's logging system
When I review the authentication logs
Then it should include all decisions made during user authentication
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
<https://cwe.mitre.org/data/definitions/778>
