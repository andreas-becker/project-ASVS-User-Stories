# V3.4 Cookie-based Session Management

## ASVS: 3.4.4

## ASVS Requirement description
Verify that cookie-based session tokens use the "__Host-"
prefix so cookies are only sent to the host that initially
set the cookie.

## User Story

**Feature_Name**: Host-Specific Session Cookies

**Story**:\
As a Security Engineer\
I want to ensure that our session cookies use the "__Host-" prefix\
So that cookies are only sent to the host that initially set the cookie,
enhancing our application's security.

## Scenario

**Scenario_name**: Verifying "__Host-" Prefix in Session Cookies

**Gherkin syntax**:

```gherkin
Given our application's session management system
When a cookie-based session token is issued
Then the token should use the "__Host-" prefix
And it should ensure that the cookie is only sent to the host that initially set the cookie
```

_NOTE to add 2 scenarios: overall session time and multi-factor authentication_
## External links

<https://cwe.mitre.org/data/definitions/613> \
<https://pages.nist.gov/800-63-3/sp800-63b.html> 7.1.1