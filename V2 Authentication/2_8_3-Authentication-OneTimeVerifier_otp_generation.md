# V2.8 One Time Verifier

## ASVS: 2.8.3

## ASVS Requirement description

Verify that approved cryptographic algorithms are used in the
generation, seeding, and verification of OTPs.

## User Story

**Feature_Name**: Secure OTP Generation

**Story**:
As a Security Engineer\
I want to ensure that approved cryptographic algorithms are used in the generation, seeding, and 
verification of one-time passwords (OTPs)\
So that we can maintain the security and integrity of our OTPs

## Scenario

**Scenario_name**: Verifying use of approved cryptographic algorithms in OTPs 

**Gherkin syntax**:

```gherkin
Given our system's OTP generation, seeding, and verification process
When I review the cryptographic algorithms used
Then they should be approved and secure
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
<https://cwe.mitre.org/data/definitions/326>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.4.2 / 5.1.5.2

