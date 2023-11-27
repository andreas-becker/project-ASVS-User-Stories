# V2.8 One Time Verifier

## ASVS: 2.8.7

## ASVS Requirement description

Verify that biometric authenticators are limited to use only as
secondary factors in conjunction with either something you have
and something you know.

## User Story

**Feature_Name**: Biometric Authenticator Limitation

**Story**:
As a Security Engineer\
I want to ensure that biometric authenticators are used only as secondary factors in conjunction
with something the user has and something the user knows\
So that we can enhance the security of our authentication process

## Scenario

**Scenario_name**: Verifying limitation of biometric authenticators

**Gherkin syntax**:

```gherkin
Given our system's biometric authenticators
When I review their usage in the authentication process
Then they should be used only as secondary factors
And they should be used in conjunction with something the user has and something the user knows
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
<https://cwe.mitre.org/data/definitions/308>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.2.3

