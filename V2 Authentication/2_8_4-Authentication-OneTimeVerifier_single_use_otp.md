# V2.8 One Time Verifier

## ASVS: 2.8.4

## ASVS Requirement description

Verify that time-based OTP can be used only once within the
validity period.

## User Story

**Feature_Name**: Single-Use OTP

**Story**:
As a Security Engineer\
I want to ensure that a time-based one-time password (OTP) can be used only once within its 
validity period\
So that we can prevent unauthorized re-use and enhance the security of our system

## Scenario

**Scenario_name**: Verifying single-use property of time-based OTPs

**Gherkin syntax**:

```gherkin
Given our system's time-based OTP
When the OTP is used within its validity period
Then it should be invalidated and not be usable again
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
<https://cwe.mitre.org/data/definitions/287>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.4.2 / 5.1.5.2

