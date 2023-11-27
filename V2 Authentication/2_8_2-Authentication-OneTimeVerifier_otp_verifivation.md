# V2.8 One Time Verifier

## ASVS: 2.8.2

## ASVS Requirement description

Verify that symmetric keys used to verify submitted OTPs are
highly protected, such as by using a hardware security module
or secure operating system based key storage.

## User Story

**Feature_Name**: Secure OTP Verification

**Story**:
As a Security Engineer\
I want to ensure that symmetric keys used for verifying one-time passwords (OTPs) are highly 
protected\
So that we can maintain the security of our authentication process and prevent misuse of OTPs

## Scenario

**Scenario_name**: Verifying protection of symmetric keys used for OTPs

**Gherkin syntax**:

```gherkin
Given our system's OTP verification process
When I review the protection of symmetric keys used for OTPs
Then they should be highly protected, such as by using a hardware security module or secure 
operating system based key storage
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
<https://cwe.mitre.org/data/definitions/320>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.4.2 / 5.1.5.2

