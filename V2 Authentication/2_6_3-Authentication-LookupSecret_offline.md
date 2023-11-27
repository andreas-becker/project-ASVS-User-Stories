# V2.6 Look-up Secret Verifier

## ASVS: 2.6.3

## ASVS Requirement description

Verify that lookup secrets are resistant to offline attacks, such
as predictable values.

## User Story

**Feature_Name**: Resistance to Offline Attacks

**Story**:
As a Security Engineer\
I want to ensure that lookup secrets are resistant to offline attacks, such as predictable values\
So that we can maintain the security and integrity of our system

## Scenario

**Scenario_name**: Verifying resistance of lookup secrets to offline attacks

**Gherkin syntax**:

```gherkin
Given our system's lookup secrets
When I review their resistance to offline attacks
Then they should not have predictable values
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
<https://cwe.mitre.org/data/definitions/310>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.2.2

