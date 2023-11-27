# V7.1 Log Content

## ASVS: 7.1.3

## ASVS Requirement description

Verify that the application logs security relevant events
including successful and failed authentication events, access
control failures, deserialization failures and input validation
failures.
([C5, C7](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Security Event Logging

**Story**:\
As a Security Engineer\
I want the application to log all security-relevant events, including successful and failed 
authentication attempts, access control failures, deserialization failures and input validation 
failures\
So that we can monitor and respond to potential security incidents effectively

## Scenario

**Scenario_name**: Verifying logging of security-relevant events

**Gherkin syntax**:

```gherkin
Given our application's logging system
When I review the logged events
Then it should include successful and failed authentication attempts
And it should include access control failures
And it should include deserialization failures
And it should include input validation failures
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
