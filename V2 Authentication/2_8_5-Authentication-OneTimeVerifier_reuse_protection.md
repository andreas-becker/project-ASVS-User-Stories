# V2.8 One Time Verifier

## ASVS: 2.8.5

## ASVS Requirement description

Verify that if a time-based multi-factor OTP token is re-used
during the validity period, it is logged and rejected with secure
notifications being sent to the holder of the device.

## User Story

**Feature_Name**: OTP Reuse Protection

**Story**:
As a Security Engineer\
I want to ensure that if a time-based multi-factor OTP token is re-used during its validity period,
it is logged and rejected, with secure notifications being sent to the holder of the device\
So that we can prevent unauthorized re-use and enhance the security of our system

## Scenario

**Scenario_name**: Verifying protection against OTP reuse

**Gherkin syntax**:

```gherkin
Given our system's time-based multi-factor OTP token
When the OTP token is re-used within its validity period
Then it should be logged and rejected
And secure notifications should be sent to the holder of the device
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
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.5.2

