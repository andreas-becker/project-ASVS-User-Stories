# V6.4 Secret Management

## ASVS: 6.4.1

## ASVS Requirement description

Verify that a secrets management solution such as a key vault is
used to securely create, store, control access to and destroy
secrets.
([C8](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Secure Secrets Management

**Story**:\
As a Security Engineer\
I want to use a secrets management solution like a key vault\
So that we can securely create, store, control access to, and destroy secrets

## Scenario

**Scenario_name**: Verifying secure management of secrets

**Gherkin syntax**:

```gherkin
Given our application's secrets management solution
When I review the solution used
Then it should be a secure system like a key vault
And it should be capable of securely creating, storing, controlling access to, and destroying secrets
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/798>
