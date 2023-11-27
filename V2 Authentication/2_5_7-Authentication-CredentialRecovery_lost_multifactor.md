# V2.5 Credential Recovery

## ASVS: 2.5.7

## ASVS Requirement description

Verify that if OTP or multi-factor authentication factors are
lost, that evidence of identity proofing is performed at the same
level as during enrollment.

## User Story

**Feature_Name**: Multi-factor Authentication Recovery

**Story**:
As a Security Engineer\
I want to ensure that if OTP or multi-factor authentication factors are lost, the user is required
to provide evidence of identity at the same level as during enrollment\
So that we can maintain the security of our user accounts

## Scenario

**Scenario_name**: Verifying identity proofing for lost multi-factor authentication factors

**Gherkin syntax**:

```gherkin
Given a user has lost their OTP or multi-factor authentication factors
When the user attempts to recover their account
Then they should be required to provide evidence of identity
And this evidence should be at the same level as during their initial enrollment
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
<https://pages.nist.gov/800-63-3/sp800-63b.html> 6.1.2.3

