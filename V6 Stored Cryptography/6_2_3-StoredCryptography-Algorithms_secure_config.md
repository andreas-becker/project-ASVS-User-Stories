# V6.2 Algorithms

## ASVS: 6.2.3

## ASVS Requirement description

Verify that encryption initialization vector, cipher
configuration, and block modes are configured securely using the
latest advice.

## User Story

**Feature_Name**: Secure Cryptographic Configuration

**Story**:\
As a Security Engineer\
I want to ensure that the encryption initialization vector, cipher configuration, and block modes
are configured securely following the latest advice\
So that we can maintain the security and integrity of our cryptographic operations

## Scenario

**Scenario_name**: Verifying secure configuration of cryptographic operations

**Gherkin syntax**:

```gherkin
Given our application's cryptographic operations
When I review the encryption initialization vector, cipher configuration, and block modes
Then they should be configured securely following the latest advice
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cheatsheetseries.owasp.org/cheatsheets/Cryptographic_Storage_Cheat_Sheet.html> \
<https://cwe.mitre.org/data/definitions/326>
