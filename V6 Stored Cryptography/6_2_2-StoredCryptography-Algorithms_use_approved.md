# V6.2 Algorithms

## ASVS: 6.2.2

## ASVS Requirement description

Verify that industry proven or government approved cryptographic
algorithms, modes, and libraries are used, instead of custom coded
cryptography.
([C8](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Use of Approved Cryptographic Algorithms

**Story**:\
As a Security Engineer\
I want to ensure that our application uses industry-proven or government-approved cryptographic
algorithms, modes, and libraries\
So that we can maintain the security and integrity of our data and avoid the risks associated
with custom-coded cryptography

## Scenario

**Scenario_name**: Verifying use of approved cryptographic algorithms

**Gherkin syntax**:

```gherkin
Given our application's cryptographic operations
When I review the algorithms, modes, and libraries used
Then they should be industry-proven or government-approved
And custom-coded cryptography should not be used
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cheatsheetseries.owasp.org/cheatsheets/Cryptographic_Storage_Cheat_Sheet.html> \
<https://cwe.mitre.org/data/definitions/327>
