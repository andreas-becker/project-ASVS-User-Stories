# V2.5 Credential Recovery

## ASVS: 2.5.3

## ASVS Requirement description

Verify password credential recovery does not reveal the current
password in any way.

## User Story

**Feature_Name**: Secure Password Recovery

**Story**:
As a Security Engineer\
I want users to reset a new password\
So that the user doesn't lose access to their account

## Scenario

**Scenario_name**: Verifying Secure Password Recovery

**Gherkin syntax**:

```gherkin
Given our application's password recovery process
When a user attempts to recover their password
Then the process should not reveal the current password in any way
And it should allow the user to reset their password securely
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
<https://cwe.mitre.org/data/definitions/916> \
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.1.2

