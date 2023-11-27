# V2.9 Cryptographic Verifier

## ASVS: 2.9.2

## ASVS Requirement description

Verify that the challenge nonce is at least 64 bits in length
and statistically unique or unique over the lifetime of the
cryptographic device.

## User Story

**Feature_Name**: Unique Challenge Nonce

**Story**:
As a Security Engineer\
I want to ensure that the challenge nonce is at least 64 bits in length and statistically unique or
unique over the lifetime of the cryptographic device\
So that we can maintain the security and integrity of our cryptographic operations

## Scenario

**Scenario_name**: Verifying uniqueness and length of challenge nonce

**Gherkin syntax**:

```gherkin
Given our system's cryptographic device
When I review the challenge nonce
Then it should be at least 64 bits in length
And it should be statistically unique or unique over the lifetime of the cryptographic device
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
<https://cwe.mitre.org/data/definitions/330>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.7.2

