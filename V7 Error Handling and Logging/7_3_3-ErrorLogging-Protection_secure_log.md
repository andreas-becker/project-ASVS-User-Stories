# V7.3 Log Protection

## ASVS: 7.3.3

## ASVS Requirement description

Verify that security logs are protected from unauthorized access
and modification.
([C9](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Secure Log Protection

**Story**:\
As a Security Engineer\
I want the application to protect security logs from unauthorized access and modification\
So that we can ensure the integrity and confidentiality of our logs

## Scenario

**Scenario_name**: Verifying Secure Log Protection

**Gherkin syntax**:

```gherkin
Given our application's logging system
When I review the security logs
Then it should show that logs are protected from unauthorized access and modification
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
<https://cwe.mitre.org/data/definitions/200>
