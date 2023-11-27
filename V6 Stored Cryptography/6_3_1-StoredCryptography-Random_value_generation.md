# V6.3 Random Values

## ASVS: 6.3.1

## ASVS Requirement description

Verify that all random numbers, random file names, random GUIDs,
and random strings are generated using the cryptographic module's
approved cryptographically secure random number generator when
these random values are intended to be not guessable by an 
attacker.

## User Story

**Feature_Name**: Secure Random Value Generation

**Story**:\
As a Security Engineer\
I want to ensure that all random values such as numbers, file names, GUIDs, and strings are
generated using the approved cryptographically secure random number generator\
So that these random values are not guessable by an attacker

## Scenario

**Scenario_name**: Verifying secure generation of random values

**Gherkin syntax**:

```gherkin
Given our application's generation of random values
When I review the random number generator used
Then it should be an approved cryptographically secure random number generator
And the generated random values should not be guessable by an attacker
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
