# V2.5 Credential Recovery

## ASVS: 2.5.6

## ASVS Requirement description

Verify forgotten password, and other recovery paths use a secure
recovery mechanism, such as time-based OTP (TOTP) or other soft
token, mobile push, or another offline recovery mechanism.

## User Story

**Feature_Name**: Secure Credential Recovery

**Story**:
As a Security Engineer\
I want to make sure that only the user regain access to his account\
So unauthorized access is prevented.

## Scenario

**Scenario_name**: Implementing Secure Credential Recovery

**Gherkin syntax**:

```gherkin
Given our application's password recovery process
When a user initiates the password recovery process
Then the application should use a secure recovery mechanism such as time-based OTP (TOTP), other soft token, mobile push, or another offline recovery mechanism
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

