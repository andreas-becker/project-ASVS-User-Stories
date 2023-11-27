# V2.7 Out of Band Verifier

## ASVS: 2.7.5

## ASVS Requirement description

Verify that the out of band verifier retains only a hashed version
of the authentication code.

## User Story

**Feature_Name**: Secure Authentication Code Storage

**Story**:
As a Security Engineer\
I want to ensure that the out of band verifier retains only a hashed version of the authentication
code\
So that we can prevent unauthorized access and maintain the security of our authentication process

## Scenario

**Scenario_name**: Verifying secure storage of authentication code in out of band verifier

**Gherkin syntax**:

```gherkin
Given our system's out of band verifier
When I review the storage of the authentication code
Then it should retain only a hashed version of the authentication code
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
<https://cwe.mitre.org/data/definitions/256>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.3.2

