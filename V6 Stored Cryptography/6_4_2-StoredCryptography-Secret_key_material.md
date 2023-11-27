# V6.4 Secret Management

## ASVS: 6.4.2

## ASVS Requirement description

Verify that key material is not exposed to the application but
instead uses an isolated security module like a vault for
cryptographic operations.
([C8](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Secure Handling of Key Material

**Story**:\
As a Security Engineer\
I want to ensure that key material is not exposed to the application, instead, it should use an
isolated security module like a vault for cryptographic operations\
So that we can maintain the security and integrity of our cryptographic operations

## Scenario

**Scenario_name**: Verifying secure handling of key material

**Gherkin syntax**:

```gherkin
Given our application's handling of key material
When I review the handling method
Then the key material should not be exposed to the application
And an isolated security module like a vault should be used for cryptographic operations
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/320>
