# V3.6 Federated Re-authentication

## ASVS: 3.6.1

## ASVS Requirement description
Verify that Relying Parties (RPs) specify the maximum authentication
time to Credential Service Providers (CSPs) and that CSPs
reauthenticate the user if they haven't used a session within that
period.

## User Story

**Feature_Name**: Session Reauthentication

**Story**:\
As a Security Engineer\
I want to ensure that Relying Parties (RPs) specify the maximum 
authentication time to Credential Service Providers (CSPs)\
So that CSPs can reauthenticate the user if they haven't used a
session within that period, enhancing our system's security

## Scenario

**Scenario_name**: Implementing Session Reauthentication

**Gherkin syntax**:

```gherkin
Given a user with an active session
When the maximum authentication time specified by the RP to the CSP has passed
Then the CSP should reauthenticate the user
```

## External links

<https://cwe.mitre.org/data/definitions/613>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 7.2.1