# V2.7 Out of Band Verifier

## ASVS: 2.7.4

## ASVS Requirement description

Verify that the out of band authenticator and verifier
communicates over a secure independent channel.

## User Story

**Feature_Name**: Verification of secure communication in out of band authentication

**Story**:
As a Security Engineer\
I want to ensure that the out of band authenticator and verifier communicates over a 
secure independent channel\
So that we can maintain the confidentiality and integrity of our authentication process.

## Scenario

**Scenario_name**: Verifying Secure Communication in Out of Band Authentication

**Gherkin syntax**:

```gherkin
Given our system's out of band authentication process
When a user initiates the authentication process
Then the out of band authenticator and verifier should communicate over a secure independent channel
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

