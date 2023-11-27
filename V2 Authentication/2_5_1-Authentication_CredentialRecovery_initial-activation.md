# V2.5 Credential Recovery

## ASVS: 2.5.1

## ASVS Requirement description

Verify that a system generated initial activation or recovery
secret is not sent in clear text to the user.

## User Story

**Feature_Name**: Secure Initial Activation

**Story**:
As a Security Engineer\
I want to provide secure initial user accounts\
So we can minimize the risk of unauthorized access or data breaches.

## Scenario

**Scenario_name**: Verifying Secure Delivery of Initial Activation Secrets

**Gherkin syntax**:

```gherkin
Given our system that generates initial activation or recovery secrets
When a secret is sent to a user
Then it should not be sent in clear text
And it should be encrypted or hashed to ensure its security during transit
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
<https://cwe.mitre.org/data/definitions/916> \
<https://pages.nist.gov/800-63-3/sp800-63b.html> 5.1.1.2

