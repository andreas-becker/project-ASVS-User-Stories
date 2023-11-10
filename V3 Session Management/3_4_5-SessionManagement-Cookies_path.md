# V3.4 Cookie-based Session Management

## ASVS: 3.4.5

## ASVS Requirement description
Verify that if the application is published under a domain name with
other applications that set or use session cookies that might disclose
the session cookies, set the path attribute in cookie-based session
tokens using the most precise path possible.

## User Story

**Feature_Name**: Secure session cookie

**Story**:\
As a Security Engineer\
I want to use other applications on the same domain\
So i'll set the path attribute in the cookie

## Scenario

**Scenario_name**: TBD

**Gherkin syntax**:

```gherkin
TBD
```

# NOTE to add 2 scenarios: overall session time and multi-factor authentication
## External links

<https://cwe.mitre.org/data/definitions/613>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 7.1.1