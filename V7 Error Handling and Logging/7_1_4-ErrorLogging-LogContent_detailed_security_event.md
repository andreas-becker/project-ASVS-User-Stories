# V7.1 Log Content

## ASVS: 7.1.4

## ASVS Requirement description

Verify that each log event includes necessary information that
would allow for a detailed investigation of the timeline when an
event happens.
([C9](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Detailed Security Event Logging

**Story**:\
As a Security Engineer\
I want the application to log all necessary information for each security-relevant event\
So that I can conduct a detailed investigation of the timeline when an event occurs

## Scenario

**Scenario_name**: Verifying detailed logging of security-relevant events

**Gherkin syntax**:

```gherkin
Given our application's logging system
When I review the logged events
Then each event should include necessary information
And this information should allow for a detailed investigation of the timeline when an event happens
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
