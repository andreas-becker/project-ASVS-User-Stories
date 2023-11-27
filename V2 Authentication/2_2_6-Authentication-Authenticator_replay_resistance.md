# V2.2 General Authenticator Security

## ASVS: 2.2.6

## ASVS Requirement description

Verify replay resistance through the mandated use of One-time
Passwords (OTP) devices, cryptographic authenticators, or
lookup codes.

## User Story

**Feature_Name**: Replay Resistance

**Story**:
As a Security Engineer\
I want to ensure that our authentication system is resistant
to replay attacks\
So that we can prevent unauthorized access and protect our user data

## Scenario

**Scenario_name**: Implementing One-Time Passwords (OTP)

**Gherkin syntax**:

```gherkin
Given a user attempts to authenticate
When they provide their credentials
Then they should be prompted for a One-Time Password (OTP)
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
<https://cwe.mitre.org/data/definitions/308> \
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.2.8
