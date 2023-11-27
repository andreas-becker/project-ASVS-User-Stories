# V3.3 Session Termination

## ASVS: 3.3.4

## ASVS Requirement description
Verify that users are able to view and (having re-entered login
credentials) log out of any or all currently active sessions and
devices.

## User Story

**Feature_Name**: User Session Management

**Story**:\
As a Security Engineer\
I want to ensure that users are able to view and, after re-entering their login credentials, log 
out of any or all currently active sessions and devices\
So that we can maintain the security of our user accounts and prevent unauthorized access

## Scenario

**Scenario_name**: Verifying user ability to manage active sessions

**Gherkin syntax**:

```gherkin
Given a user with active sessions on multiple devices
When the user chooses to view their active sessions
Then they should be able to see all their currently active sessions and devices
And when they re-enter their login credentials
They should be able to log out of any or all of these active sessions
```

## External links

<https://cwe.mitre.org/data/definitions/613>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 7.1