# V3.4 Cookie-based Session Management

## ASVS: 3.4.1

## ASVS Requirement description
Verify that cookie-based session tokens have the 'Secure'
attribute set.

## User Story

**Feature_Name**: Secure session cookie

**Story**:\
As a Security Engineer\
I want to prevent sending cookies in clear text\
So that they can't be observed by unauthorized parties

## Scenario

**Scenario_name**: Verifying 'Secure' Attribute in Session Cookies

**Gherkin syntax**:

```gherkin
Given our application's session management system
When a cookie-based session token is issued
Then the 'Secure' attribute of the token should be set
And it should prevent the cookie from being sent in clear text
```

_NOTE to add 2 scenarios: overall session time and multi-factor authentication_
## External links

<https://cwe.mitre.org/data/definitions/613> \
<https://pages.nist.gov/800-63-3/sp800-63b.html> 7.1.1