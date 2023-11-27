# V3.6 Federated Re-authentication

## ASVS: 3.6.2

## ASVS Requirement description
Verify that Credential Service Providers (CSPs) inform Relying Parties
(RPs) of the last authentication event, to allow RPs to determine if
they need to re-authenticate the user.

## User Story

**Feature_Name**: Authentication Event Tracking

**Story**:\
As a Security Engineer\
I want to ensure that Credential Service Providers (CSPs) inform Relying 
Parties (RPs) of the last authentication event\
So that RPs can determine if they need to re-authenticate the user,
enhancing our system's security

## Scenario

**Scenario_name**: Implementing Authentication Event Tracking

**Gherkin syntax**:

```gherkin
Given a user with an active session
When the user performs an authentication event
Then the CSP should inform the RP of this event
And the RP should determine if they need to re-authenticate the user
```

## External links

<https://cwe.mitre.org/data/definitions/613>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 7.2.1