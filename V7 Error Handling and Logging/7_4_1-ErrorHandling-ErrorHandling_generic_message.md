# V7.4 Error Handling

## ASVS: 7.4.1

## ASVS Requirement description

Verify that a generic message is shown when an unexpected or security
sensitive error occurs, potentially with a unique ID which support personnel
can use to investigate.

## User Story

**Feature_Name**: Error Handling and Investigation Support

**Story**:\
As a Security Engineer\
I want to ensure that errors show a generic message with a unique ID\
So that we can maintain the security of our system and provide support

## Scenario

**Scenario_name**: Unexpected Input / security sensitive error

**Gherkin syntax**:

```gherkin
GIVEN an application receives unexpected input
WHEN an error occurs
THEN log event with a unique ID for support personnel to investigate
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cheatsheetseries.owasp.org/cheatsheets/Error_Handling_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html> \
<https://cwe.mitre.org/data/definitions/210>
