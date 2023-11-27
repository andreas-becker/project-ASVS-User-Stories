# V2.5 Credential Recovery

## ASVS: 2.5.5

## ASVS Requirement description

Verify that if an authentication factor is changed or replaced,
that the user is notified of this event.

## User Story

**Feature_Name**: User Notification of Authentication Changes

**Story**:
As a Security Engineer\
I want to inform the user when an authentication factor is changed or replaced\
So the user will notice unauthorized changes to their account.

## Scenario

**Scenario_name**: Notifying Users on Authentication Changes

**Gherkin syntax**:

```gherkin
Given our application's user accounts
When an authentication factor is changed or replaced
Then the user associated with the account should be notified of this event
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
<https://pages.nist.gov/800-63-3/sp800-63b.html> 6.1.2.3

