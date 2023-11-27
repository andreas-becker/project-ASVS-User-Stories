# V2.9 Cryptographic Verifier

## ASVS: 2.9.3

## ASVS Requirement description

Verify that approved cryptographic algorithms are used in the
generation, seeding, and verification.

## User Story

**Feature_Name**: Approved Cryptographic Algorithms Usage

**Story**:
As a Security Engineer\
I want to ensure that approved cryptographic algorithms are used in the generation, seeding and
verification\
So that we can maintain the security and integrity of our cryptographic operations

## Scenario

**Scenario_name**: Verifying the use of approved cryptographic algorithms

**Gherkin syntax**:

```gherkin
Given our system's cryptographic operations
When I review the algorithms used in generation, seeding, and verification
Then they should be approved and secure
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
<https://cwe.mitre.org/data/definitions/327>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.7.2

