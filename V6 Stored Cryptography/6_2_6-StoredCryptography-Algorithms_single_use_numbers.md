# V6.2 Algorithms

## ASVS: 6.2.6

## ASVS Requirement description

Verify that nonces, initialization vectors, and other single use
numbers must not be used more than once with a given encryption
key. The method of generation must be appropriate for the
algorithm being used.

## User Story

**Feature_Name**: Secure Single-Use Numbers in Cryptography

**Story**:\
As a Security Engineer\
I want to ensure that nonces, initialization vectors, and other single-use numbers are not used
more than once with a given encryption key, And that their method of generation is appropriate for
the algorithm being used\
So that we can maintain the security and integrity of our cryptographic operations

## Scenario

**Scenario_name**: Verifying secure usage of single-use numbers in cryptography

**Gherkin syntax**:

```gherkin
Given our application's cryptographic operations
When I review the usage of nonces, initialization vectors, and other single-use numbers
Then they should not be used more than once with a given encryption key
And their method of generation should be appropriate for the algorithm being used
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
