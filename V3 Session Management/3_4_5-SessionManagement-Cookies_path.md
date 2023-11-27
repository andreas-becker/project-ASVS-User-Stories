# V3.4 Cookie-based Session Management

## ASVS: 3.4.5

## ASVS Requirement description
Verify that if the application is published under a domain
name with other applications that set or use session cookies
that might disclose the session cookies, set the path attribute
in cookie-based session tokens using the most precise path
possible.

## User Story

**Feature_Name**: Precise Path for Session Cookies

**Story**:\
As a Security Engineer\
I want to set the path attribute in cookie-based session tokens using the most precise path
possible\
So that we can prevent session cookies from being disclosed when our application is published 
under a domain name with other applications

## Scenario

**Scenario_name**: Setting Precise Path in Session Cookies

**Gherkin syntax**:

```gherkin
Given our application that is published under a domain name with other applications
When a cookie-based session token is issued
Then the path attribute of the token should be set using the most precise path possible
And it should prevent the session cookies from being disclosed to other applications on the same domain
```

# NOTE to add 2 scenarios: overall session time and multi-factor authentication
## External links

<https://cwe.mitre.org/data/definitions/613> \
<https://pages.nist.gov/800-63-3/sp800-63b.html> 7.1.1