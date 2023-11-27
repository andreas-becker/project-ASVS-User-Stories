# V3.5 Token-based Session Management

## ASVS: 3.5.3

## ASVS Requirement description
Verify that stateless session tokens use digital signatures,
encryption, and other countermeasures to protect against
tampering, enveloping, replay, null cipher, and key substitution
attacks.

## User Story

**Feature_Name**: Stateless Session Token Security

**Story**:\
As a Security Engineer\
I want to ensure that stateless session tokens use digital signatures, encryption, and other 
countermeasures\
So that we can protect against tampering, enveloping, replay, null cipher, and key substitution 
attacks

## Scenario

**Scenario_name**: Verifying security measures of stateless session tokens

**Gherkin syntax**:

```gherkin
Given our application's stateless session tokens
When I review their security measures
Then they should use digital signatures and encryption
And they should have countermeasures against tampering, enveloping, replay, null cipher, and key 
substitution attacks
```

## External links

<https://cwe.mitre.org/data/definitions/345>