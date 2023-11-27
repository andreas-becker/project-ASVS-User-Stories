# V2.7 Out of Band Verifier

## ASVS: 2.7.3

## ASVS Requirement description

Verify that the out of band verifier authentication requests,
codes, or tokens are only usable once, and only for the original
authentication request.

## User Story

**Feature_Name**: Single-Use Out of Band Verifier

**Story**:
As a Security Engineer\
I want to ensure that the out of band verifier authentication requests, codes,
or tokens are only usable once and they are only usable for the original 
authentication request\
So that we can prevent unauthorized access and ensure the integrity and security
of our system.

## Scenario

**Scenario_name**: Verifying Single-Use Out of Band Verifie

**Gherkin syntax**:

```gherkin
Given our system's out of band authentication process
When a user initiates the authentication process
Then the system should generate a request, code, or token for the user
And this should be usable only once
And it should be usable only for the original authentication request
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
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.3.2

