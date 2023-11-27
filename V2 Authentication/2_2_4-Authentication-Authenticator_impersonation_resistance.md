# V2.2 General Authenticator Security

## ASVS: 2.2.4

## ASVS Requirement description

Verify impersonation resistance against phishing, such as the 
use of multi-factor authentication, cryptographic devices with
intent (such as connected keys with a push to authenticate),
or at higher AAL levels, client-side certificates.

## User Story

**Feature_Name**: Impersonation Resistance

**Story**:
As a Security Engineer\
I want to implement measures against phishing\
So that our system and user data remain secure and trustworthy

## Scenario

**Scenario_name**: Implementing Multi-Factor Authentication

**Gherkin syntax**:

```gherkin
Given a user attempts to log in
When they provide their primary credentials
Then they should be prompted for a second factor of authentication
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
<https://cwe.mitre.org/data/definitions/308> \
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.2.5
