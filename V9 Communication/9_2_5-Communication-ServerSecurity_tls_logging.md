# V9.2 Server Communication Security

## ASVS: 9.2.5

## ASVS Requirement description

Verify that backend TLS connection failures are logged.

## User Story

**Feature_Name**: Backend TLS Connection Logging

**Story**:\
As a Security Engineer\
I want to ensure that all backend TLS connection failures are logged\
So that we can identify and troubleshoot any potential issues 
in our secure communication

## Scenario

**Scenario_name**: Logging Backend TLS Connection Failures

**Gherkin syntax**:

```gherkin
Given our backend server's TLS configuration
When a TLS connection failure occurs
Then the failure should be logged for further investigation
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
<https://cwe.mitre.org/data/definitions/544>
