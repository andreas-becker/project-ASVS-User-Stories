# V3.5 Token-based Session Management

## ASVS: 3.5.1

## ASVS Requirement description
Verify the application allows users to revoke OAuth tokens that
form trust relationships with linked applications.

## User Story

**Feature_Name**: OAuth Token Revocation

**Story**:\
As a Security Engineer\
I want to ensure that users can revoke OAuth tokens that establish trust relationships with linked
applications\
So that we can maintain the security of our user accounts and prevent unauthorized access

## Scenario

**Scenario_name**: Verifying user ability to revoke OAuth tokens

**Gherkin syntax**:

```gherkin
Given a user with active OAuth tokens linked to other applications
When the user chooses to revoke these OAuth tokens
Then the application should allow the revocation process
And the trust relationships with the linked applications should be terminated
```

## External links

<https://cwe.mitre.org/data/definitions/290>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 7.1.2