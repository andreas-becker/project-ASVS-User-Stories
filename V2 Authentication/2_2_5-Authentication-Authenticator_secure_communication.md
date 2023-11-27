# V2.2 General Authenticator Security

## ASVS: 2.2.5

## ASVS Requirement description

Verify that where a Credential Service Provider (CSP) and the
application verifying authentication are separated, mutually
authenticated TLS is in place between the two endpoints.

## User Story

**Feature_Name**: Secure Communication

**Story**:
As a Security Engineer\
I want to ensure that the communication between our Credential
Service Provider (CSP) and the application is secure\
So that we can prevent unauthorized access and protect our user data

## Scenario

**Scenario_name**: Implementing Mutually Authenticated TLS

**Gherkin syntax**:

```gherkin
Given a Credential Service Provider (CSP) and the application verifying authentication are separated
When they communicate
Then a mutually authenticated TLS should be in place between the two endpoints
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
<https://cwe.mitre.org/data/definitions/319> \
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.2.6
