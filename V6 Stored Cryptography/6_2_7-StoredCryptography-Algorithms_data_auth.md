# V6.2 Algorithms

## ASVS: 6.2.7

## ASVS Requirement description

Verify that encrypted data is authenticated via signatures, authenticated
cipher modes or HMAC to ensure that ciphertext is not altered by an
unauthorized party.

## User Story

**Feature_Name**: Data Authentication

**Story**:\
As a Security Engineer\
I want to ensure that our encrypted data is authenticated via signatures, 
authenticated cipher modes, or HMAC\
So that we can prevent unauthorized alterations to our ciphertext and 
maintain the integrity of our data

## Scenario

**Scenario_name**: Implementing Data Authentication

**Gherkin syntax**:

```gherkin
Given our application's encrypted data
When it is being accessed or used
Then it should be authenticated via signatures, authenticated cipher modes, or HMAC
And any unauthorized alterations to the ciphertext should be prevented
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
