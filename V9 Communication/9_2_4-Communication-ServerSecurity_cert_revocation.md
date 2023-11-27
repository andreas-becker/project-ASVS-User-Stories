# V9.2 Server Communication Security

## ASVS: 9.2.4

## ASVS Requirement description

Verify that proper certification revocation, such as Online
Certificate Status Protocol (OCSP) Stapling, is enabled and
configured.

## User Story

**Feature_Name**: Certification Revocation

**Story**:\
As a Security Engineer\
I want to ensure that proper certification revocation, such as Online Certificate Status Protocol
(OCSP) Stapling, is enabled and configured\
So that we can maintain the integrity and trust of our certificates

## Scenario

**Scenario_name**: Verifying Certification Revocation

**Gherkin syntax**:

```gherkin
Given our server's configuration
When I review the certificate settings
Then it should show that OCSP Stapling is enabled and configured
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
<https://cwe.mitre.org/data/definitions/299>
