# V2.6 Look-up Secret Verifier

## ASVS: 2.6.2

## ASVS Requirement description

Verify that lookup secrets have sufficient randomness (112 bits
of entropy), or if less than 112 bits of entropy, salted with a
unique and random 32-bit salt and hashed with an approved one-way
hash.

## User Story

**Feature_Name**: Lookup Secret Randomness

**Story**:
As a Security Engineer\
I want to ensure that lookup secrets have sufficient randomness (112 bits of entropy), or if less 
than 112 bits of entropy, are salted with a unique and random 32-bit salt and hashed with an 
approved one-way hash\
So that we can maintain the security and integrity of our lookup secrets

## Scenario

**Scenario_name**: Verifying randomness of lookup secrets

**Gherkin syntax**:

```gherkin
Given our system's lookup secrets
When I review the randomness of these secrets
Then they should have at least 112 bits of entropy
Or if they have less than 112 bits of entropy, they should be salted with a unique and random 
32-bit salt and hashed with an approved one-way hash
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
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.2.2

