# V6.2 Algorithms

## ASVS: 6.2.4

## ASVS Requirement description

Verify that random number, encryption or hashing algorithms, key
lengths, rounds, ciphers or modes, can be reconfigured, upgraded,
or swapped at any time, to protect against cryptographic breaks.
([C8](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Cryptographic Flexibility 

**Story**:\
As a Security Engineer\
I want to ensure that our application's cryptographic components such as random number, encryption
or hashing algorithms, key lengths, rounds, ciphers or modes, can be reconfigured, upgraded or 
swapped at any time\
So that we can maintain the security and integrity of our data and protect against cryptographic
breaks

## Scenario

**Scenario_name**: Verifying flexibility of cryptographic operations

**Gherkin syntax**:

```gherkin
Given our application's cryptographic operations
When I review the components such as random number, encryption or hashing algorithms, key lengths, rounds, ciphers or modes
Then they should be capable of being reconfigured, upgraded, or swapped at any time
This is to ensure protection against cryptographic breaks
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
<https://cwe.mitre.org/data/definitions/326>
