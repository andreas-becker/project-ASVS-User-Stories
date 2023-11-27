# V9.2 Server Communication Security

## ASVS: 9.2.3

## ASVS Requirement description

Verify that all encrypted connections to external systems that
involve sensitive information or functions are authenticated.

## User Story

**Feature_Name**: Encrypted Communications Authentication

**Story**:\
As a Security Engineer\
I want all encrypted connections to external systems that involve sensitive information or 
functions to be authenticated\
So that we can ensure secure communication

## Scenario

**Scenario_name**: Verifying Authentication of Encrypted Communications

**Gherkin syntax**:

```gherkin
Given our server's configuration
When I review the connections to external systems
Then all encrypted connections involving sensitive information or functions should be authenticated
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cheatsheetseries.owasp.org/cheatsheets/TLS_Cipher_String_Cheat_Sheet.html> \
<https://cheatsheetseries.owasp.org/cheatsheets/Pinning_Cheat_Sheet.html> \
<https://cwe.mitre.org/data/definitions/287>
