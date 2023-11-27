# V2.2 General Authenticator Security

## ASVS: 2.2.2

## ASVS Requirement description

Verify that the use of weak authenticators (such as SMS and
email) is limited to secondary verification and transaction
approval and not as a replacement for more secure
authentication methods. Verify that stronger methods are
offered before weak methods, users are aware of the risks, or
that proper measures are in place to limit the risks of account
compromise.

## User Story

**Feature_Name**: User notifications on authentication detail changes

**Story**:
As a Security Engineer\
I want to send users secure notifications when authentication details change\
So that they are made aware of any changes to the security of their accounts

## Scenario

**Scenario_name**: Verifying Limited Use of Weak Authenticators

**Gherkin syntax**:

```gherkin
Given our application's authentication system
When a user attempts to authenticate
Then the application should offer stronger methods before weak methods
And it should limit the use of weak authenticators such as SMS and email to secondary verification and transaction approval
And it should ensure users are aware of the risks
And it should have proper measures in place to limit the risks of account compromise
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html> \
<https://cwe.mitre.org/data/definitions/521> \
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.2.10
