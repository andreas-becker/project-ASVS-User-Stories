# V3.3 Session Termination

## ASVS: 3.3.3

## ASVS Requirement description
Verify that the application gives the option to terminate all
other active sessions after a successful password change
(including change via password reset/recovery), and that this is
effective across the application, federated login (if present)
and any relying parties.

## User Story

**Feature_Name**: Active Session Termination

**Story**:\
As a Security Engineer\
I want to ensure that the application provides an option to terminate all other active sessions 
after a successful password change\
So that we can prevent unauthorized access and maintain the security of our user accounts

## Scenario

**Scenario_name**: Verifying termination of active sessions after password change

**Gherkin syntax**:

```gherkin
Given a user has successfully changed their password
When I review the active sessions of the user
Then all other active sessions should be terminated
And this should be effective across the application, federated login (if present), and any relying
parties
```

## External links

<https://cwe.mitre.org/data/definitions/613>