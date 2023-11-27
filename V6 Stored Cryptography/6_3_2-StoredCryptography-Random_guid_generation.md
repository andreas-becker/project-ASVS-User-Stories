# V6.3 Random Values

## ASVS: 6.3.2

## ASVS Requirement description

Verify that random GUIDs are created using the GUID v4 algorithm,
and a Cryptographically-secure Pseudo-random Number Generator
(CSPRNG). GUIDs created using other pseudo-random number
generators may be predictable.

## User Story

**Feature_Name**: Secure GUID Generation

**Story**:\
As a Security Engineer\
I want to ensure that all random GUIDs are created using the GUID v4 algorithm and a
Cryptographically-secure Pseudo-random Number Generator (CSPRNG)\
So that these GUIDs are not predictable by an attacker

## Scenario

**Scenario_name**: Verifying secure generation of random GUIDs

**Gherkin syntax**:

```gherkin
Given our application's generation of random GUIDs
When I review the GUID generation method
Then it should use the GUID v4 algorithm
And it should use a Cryptographically-secure Pseudo-random Number Generator (CSPRNG)
And the generated GUIDs should not be predictable by an attacker
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/338>
