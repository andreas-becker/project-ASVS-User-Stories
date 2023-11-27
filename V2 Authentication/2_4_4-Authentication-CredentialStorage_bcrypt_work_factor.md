# V2.4 Credential Storage

## ASVS: 2.4.4

## ASVS Requirement description

Verify that if bcrypt is used, the work factor SHOULD be as large
as verification server performance will allow, with a minimum of 
10.

## User Story

**Feature_Name**: Secure implementation of bcrypt

**Story**:
As a Security Engineer\
I want to ensure that when I use bcrypt I define a large work factor\
So that I can ensure the stored hashes are securely randomised to 
decrease chances of collisions and disclosure

## Scenario

**Scenario_name**: Verify PBKDF2 implementation

**Gherkin syntax**:

```gherkin
Given a password change or password setting event
And I'm using bcrypt derivation functions
When I store the password
Then I add a random salt of at least 32 bits generated randomly
And I set a work factor of at least 13
And I store a unique salt value and the resulting hash
Then I store it in a secure location with strong access control measures
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
<https://cwe.mitre.org/data/definitions/916>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.1.2

