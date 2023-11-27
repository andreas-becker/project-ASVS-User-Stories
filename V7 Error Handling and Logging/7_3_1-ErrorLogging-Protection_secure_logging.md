# V7.3 Log Protection

## ASVS: 7.3.1

## ASVS Requirement description

Verify that all logging components appropriately encode data to
prevent log injection.
([C9](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Secure Logging

**Story**:\
As a Security Engineer\
I want the application to appropriately encode data in logs\
So that we can prevent log injection attacks

## Scenario

**Scenario_name**: Verifying Secure Logging

**Gherkin syntax**:

```gherkin
Given our application's logging system
When I review the application logs
Then it should show that all data is appropriately encoded
And it should prevent any log injection attacks
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
<https://cwe.mitre.org/data/definitions/117>
