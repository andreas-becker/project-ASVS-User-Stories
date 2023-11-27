# V7.3 Log Protection

## ASVS: 7.3.4

## ASVS Requirement description

Verify that time sources are synchronized to the correct time and
time zone. Strongly consider logging only in UTC if systems are
global to assist with post-incident forensic analysis.
([C9](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Secure Log Time Synchronization

**Story**:\
As a Security Engineer\
I want the application to synchronize time sources to the correct time and time zone\
So that we can ensure accurate timestamps in our logs and assist with post-incident forensic
analysis

## Scenario

**Scenario_name**: Verifying Secure Log Time Synchronization

**Gherkin syntax**:

```gherkin
Given our application's logging system
When I review the security logs
Then it should show that time sources are synchronized to the correct time and time zone
And it should consider logging only in UTC if systems are global
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
<https://cheatsheetseries.owasp.org/cheatsheets/Logging_Vocabulary_Cheat_Sheet.html>