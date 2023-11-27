# V2.9 Cryptographic Verifier

## ASVS: 2.9.1

## ASVS Requirement description

Verify that cryptographic keys used in verification are stored
securely and protected against disclosure, such as using a
Trusted Platform Module (TPM) or Hardware Security Module (HSM),
or an OS service that can use this secure storage.

## User Story

**Feature_Name**: Secure Cryptographic Key Storage

**Story**:
As a Security Engineer\
I want to ensure that cryptographic keys used in verification are stored securely and protected
against disclosure\
So that we can maintain the integrity and confidentiality of our cryptographic operations

## Scenario

**Scenario_name**: Verifying secure storage of cryptographic keys

**Gherkin syntax**:

```gherkin
Given our system's cryptographic keys used in verification
When I review their storage method
Then they should be stored securely and protected against disclosure
And this could be achieved using a Trusted Platform Module (TPM), Hardware Security Module (HSM),
or an OS service that can use this secure storage
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html> \
<https://cwe.mitre.org/data/definitions/320>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.7.2

