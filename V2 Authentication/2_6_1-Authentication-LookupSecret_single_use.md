# V2.6 Look-up Secret Verifier

## ASVS: 2.6.1

## ASVS Requirement description

Verify that lookup secrets can be used only once.

## User Story

**Feature_Name**: Single-Use Lookup Secrets

**Story**:
As a Security Engineer\
I want to ensure that lookup secrets can be used only once\
So that we can prevent unauthorized re-use and enhance the security of our system

## Scenario

**Scenario_name**: Verifying single-use property of lookup secrets

**Gherkin syntax**:

```gherkin
Given our system's lookup secrets
When a lookup secret is used
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
<https://cwe.mitre.org/data/definitions/308>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.2.2

