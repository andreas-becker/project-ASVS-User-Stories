# V2.8 One Time Verifier

## ASVS: 2.8.1

## ASVS Requirement description

Verify that time-based OTPs have a defined lifetime before
expiring.

## User Story

**Feature_Name**: Time-based OTP Lifetime

**Story**:
As a Security Engineer\
I want to ensure that time-based one-time passwords (OTPs) have a defined
lifetime before they expire\
So that we can maintain the security of our authentication process and
prevent misuse of OTPs.

## Scenario

**Scenario_name**: Verifying Time-based OTP Lifetime

**Gherkin syntax**:

```gherkin
Given our system's OTP generation process
When a time-based OTP is generated
Then it should have a defined lifetime before it expires
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
<https://cwe.mitre.org/data/definitions/613> \
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.4.2 / 5.1.5.2

