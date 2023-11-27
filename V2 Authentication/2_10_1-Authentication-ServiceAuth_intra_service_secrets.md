# V2.10 Service Authentication

## ASVS: 2.10.1

## ASVS Requirement description

Verify that intra-service secrets do not rely on unchanging
credentials such as passwords, API keys or shared accounts with
privileged access.\
_The use of an HSM is recommended for password storage_

## User Story

**Feature_Name**: Secure Intra-Service Secrets

**Story**:
As a Security Engineer\
I want to ensure that intra-service secrets do not rely on static credentials such as passwords,
API keys, or shared accounts with privileged access\
So that we can maintain the security and integrity of our system

## Scenario

**Scenario_name**: Verifying secure handling of intra-service secrets

**Gherkin syntax**:

```gherkin
Given our system's intra-service secrets
When I review their dependency on credentials
Then they should not rely on static credentials such as passwords, API keys, or shared accounts
with privileged access
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
<https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html> \
<https://cwe.mitre.org/data/definitions/287>
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.1.1

