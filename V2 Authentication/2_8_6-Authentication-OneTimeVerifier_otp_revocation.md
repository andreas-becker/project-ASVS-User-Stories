# V2.8 One Time Verifier

## ASVS: 2.8.6

## ASVS Requirement description

Verify physical single-factor OTP generator can be revoked in
case of theft or other loss. Ensure that revocation is
immediately effective across logged in sessions, regardless of
location.

## User Story

**Feature_Name**: OTP Generator Revocation

**Story**:
As a Security Engineer\
I want to ensure that a physical single-factor OTP generator can be revoked in case of theft or 
other loss and that this revocation is immediately effective across all logged in sessions,
regardless of location\
So that we can maintain the security of our system and prevent unauthorized access

## Scenario

**Scenario_name**: Verifying revocation of physical single-factor OTP generator

**Gherkin syntax**:

```gherkin
Given our system's physical single-factor OTP generator
When the generator is reported as stolen or lost
Then it should be immediately revoked
And this revocation should be effective across all logged in sessions, regardless of location
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
<https://cwe.mitre.org/data/definitions/613>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.2.1

