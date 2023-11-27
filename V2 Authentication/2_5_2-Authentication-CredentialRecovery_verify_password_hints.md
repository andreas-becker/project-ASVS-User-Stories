# V2.5 Credential Recovery

## ASVS: 2.5.2

## ASVS Requirement description

Verify password hints or knowledge-based authentication (so-
called "secret questions") are not present.

## User Story

**Feature_Name**: No Password Hints or Secret Questions

**Story**:
As a Security Engineer\
I'm aware that user information might be spread all over the internet\
So i don't allow secret questions or password hints to be used as a recovery mechanism.

## Scenario

**Scenario_name**: Verifying Absence of Password Hints and Secret Questions

**Gherkin syntax**:

```gherkin
Given our application's authentication system
When a user attempts to recover their password
Then the application should not provide password hints or secret questions
And it should use a more secure method for password recovery
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

