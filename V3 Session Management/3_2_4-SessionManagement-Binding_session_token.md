# V3.2 Session Binding

## ASVS: 3.2.4

## ASVS Requirement description

Verify that session tokens are generated using approved
cryptographic algorithms.
([C6](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Secure Session Token Generation

**Story**:\
As a Security Engineer\
I want to ensure that session tokens are generated using approved cryptographic algorithms\
So that we can maintain the security and integrity of our user sessions

## Scenario

**Scenario_name**: Verifying secure generation of session tokens

**Gherkin syntax**:

```gherkin
Given our application's session token generation process
When I review the cryptographic algorithms used
Then they should be approved and secure
```

## External links

https://cheatsheetseries.owasp.org/cheatsheets/Session_Management_Cheat_Sheet.html
<https://cwe.mitre.org/data/definitions/331>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 7.1