# V2.2 General Authenticator Security

## ASVS: 2.2.7

## ASVS Requirement description

Verify intent to authenticate by requiring the entry of an OTP
token or user-initiated action such as a button press on a FIDO
hardware key.

## User Story

**Feature_Name**: Intent Verification

**Story**:
As a Security Engineer\
I want to verify the intent to authenticate by requiring the entry
of an OTP token or a user-initiated action\
So that we can ensure the authenticity of the user and protect our
system from unauthorized access

## Scenario

**Scenario_name**: Implementing Intent Verification

**Gherkin syntax**:

```gherkin
Given a user attempts to authenticate
When they provide their credentials
Then they should be required to enter an OTP token or initiate an action such as a button press
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
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.2.9
