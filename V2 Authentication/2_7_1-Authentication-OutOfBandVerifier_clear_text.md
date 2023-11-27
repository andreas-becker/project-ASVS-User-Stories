# V2.7 Out of Band Verifier

## ASVS: 2.7.1

## ASVS Requirement description

Verify that clear text out of band (NIST "restricted")
authenticators, such as SMS or PSTN, are not offered by default,
and stronger alternatives such as push notifications are offered
first.

## User Story

**Feature_Name**: Prioritizing Secure Authenticators

**Story**:
As a Security Engineer\
I want to ensure that our system does not offer clear text out of band authenticators by default
and instead, it should prioritize stronger alternatives such as push notifications\
So that we can enhance the security of our user authentication process

## Scenario

**Scenario_name**: Prioritizing Secure Authenticators

**Gherkin syntax**:

```gherkin
Given our system's authentication process
When a user attempts to authenticate
Then the system should not offer clear text out of band authenticators by default
And it should prioritize stronger alternatives such as push notifications
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
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.3.2

