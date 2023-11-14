# V5.5 Deserialization Prevention

## ASVS: 5.5.2

## ASVS Requirement description

Verify that the application correctly restricts XML parsers to only use the most
restrictive configuration possible and to ensure that unsafe features such as
resolving external entities are disabled to prevent XML eXternal Entity (XXE)
attacks.

## User Story

**Feature_Name**: Protecting Against XML and XPath Injection Attacks

**Story**:\
As a Security Engineer\
I want to  ensure that the application uses the most restrictive settings for XML
parsers to protect against XML and XPath injection attacks\
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
<https://cwe.mitre.org/data/definitions/611>
