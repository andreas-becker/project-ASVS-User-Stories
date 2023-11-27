# V3.4 Cookie-based Session Management

## ASVS: 3.4.3

## ASVS Requirement description
Verify that cookie-based session tokens utilize the 'SameSite'
attribute to limit exposure to cross-site request forgery
attacks.

## User Story

**Feature_Name**: Secure session cookie

**Story**:\
As a Security Engineer\
I want to mitigate the risk of cross-origin information leakage\
So that the cookie is not sent on cross-site requests

## Scenario

**Scenario_name**: Verifying 'SameSite' Attribute in Session Cookies

**Gherkin syntax**:

```gherkin
Given our application's session management system
When a cookie-based session token is issued
Then the 'SameSite' attribute of the token should be set
And it should limit the cookie from being sent on cross-site requests
```

_NOTE to add 2 scenarios: overall session time and multi-factor authentication_
## External links

<https://cwe.mitre.org/data/definitions/613> \
<https://pages.nist.gov/800-63-3/sp800-63b.html> 7.1.1