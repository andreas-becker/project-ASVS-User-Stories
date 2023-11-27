# V2.5 Credential Recovery

## ASVS: 2.5.4

## ASVS Requirement description

Verify shared or default accounts are not present (e.g. "root",
"admin", or "sa").

## User Story

**Feature_Name**: No Default Accounts

**Story**:
As a Security Engineer\
I want to disable default accounts \
So attacking the system is more difficult.

## Scenario

**Scenario_name**: Verifying Absence of Default Accounts

**Gherkin syntax**:

```gherkin
Given our system's user accounts
When I review the list of user accounts
Then it should not contain shared or default accounts such as "root", "admin", or "sa"
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
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.1.2 / A.3

