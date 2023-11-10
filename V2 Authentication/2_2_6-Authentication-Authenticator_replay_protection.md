# V2.2 General Authenticator Security

## ASVS: 2.2.6

## ASVS Requirement description

Verify replay resistance through the mandated use of One-time
Passwords (OTP) devices, cryptographic authenticators, or
lookup codes.

## User Story

**Feature_Name**: replay resistance for authenticated transactions

**Story**:
As a Security Engineer\
I want to check that protocols used have resistance against replay attacks\
So that an impostor can't replay credentials on a different channel

## Scenario

**Scenario_name**: verify replay resistance

**Gherkin syntax**:

```gherkin
Given an authenticated transaction
When the transaction traffic is replayed
Then I verify the nonce or challenge in the challenge-response authentication protocol
And I don't process the request if the nonce or challenge is repeated
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
<https://cwe.mitre.org/data/definitions/308.html>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.2.8
