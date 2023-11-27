# V2.4 Credential Storage

## ASVS: 2.4.5

## ASVS Requirement description

Verify that an additional iteration of a key derivation function
is performed, using a salt value that is secret and known only to
the verifier. Generate the salt value using an approved random bit
generator [SP 800-90Ar1] and provide at least the minimum security
strength specified in the latest revision of SP 800-131A. The
secret salt value SHALL be stored separately from the hashed
passwords (e.g., in a specialized device like a hardware security
module).

## User Story

**Feature_Name**: Enhanced Key Derivation Security

**Story**:
As a Security Engineer\
I want to ensure that an additional iteration of a key derivation function is performed with a 
secret salt value\
So that we can enhance the security of our hashed passwords

## Scenario

**Scenario_name**: Verifying secure implementation of key derivation function

**Gherkin syntax**:

```gherkin
Given a password change or password setting event
When I perform an additional iteration of a key derivation function
Then I should use a secret salt value known only to the verifier
And the salt value should be generated using an approved random bit generator
And it should provide at least the minimum security strength specified in the latest revision of 
SP 800-131A
And the secret salt value should be stored separately from the hashed passwords, preferably in a 
specialized device like a hardware security module
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

