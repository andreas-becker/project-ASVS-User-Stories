# V3.4 Cookie-based Session Management

## ASVS: 3.4.2

## ASVS Requirement description
Verify that cookie-based session tokens have the 'HttpOnly'
attribute set.

## User Story

**Feature_Name**: Secure session cookie

**Story**:\
As a Security Engineer\
I want to disable script access to session cookies\
So that we can prevent malicious scripts from reading the session cookie

## Scenario

**Scenario_name**: Verifying 'HttpOnly' Attribute in Session Cookies

**Gherkin syntax**:

```gherkin
Given our application's session management system
When a cookie-based session token is issued
Then the 'HttpOnly' attribute of the token should be set
And it should prevent the cookie from being accessed by client-side scripts
```

_NOTE to add 2 scenarios: overall session time and multi-factor authentication_
## External links

<https://cwe.mitre.org/data/definitions/613> \
<https://pages.nist.gov/800-63-3/sp800-63b.html> 7.1.1