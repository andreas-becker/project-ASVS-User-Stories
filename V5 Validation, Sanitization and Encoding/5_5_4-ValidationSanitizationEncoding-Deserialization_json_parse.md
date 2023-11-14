# V5.5 Deserialization Prevention

## ASVS: 5.5.4

## ASVS Requirement description

Verify that when parsing JSON in browsers or JavaScript-based backends,
JSON.parse is used to parse the JSON document. Do not use eval() to parse
JSON.

## User Story

**Feature_Name**: Safely Parsing JSON

**Story**:\
As a Security Engineer\
I want to ensure that JSON.parse is used to parse JSON documents in browsers
or JavaScript-based backends\
So that we can prevent unauthorized changes to our data

## Scenario

**Scenario_name**: TBD

**Gherkin syntax**:

```gherkin
TBD
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cheatsheetseries.owasp.org/cheatsheets/Deserialization_Cheat_Sheet.html> \
<https://cwe.mitre.org/data/definitions/95>
