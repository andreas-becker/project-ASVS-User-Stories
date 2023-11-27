# V8.3 Sensitive Private Data

## ASVS: 8.3.7

## ASVS Requirement description

Verify that sensitive or private information that is required to
be encrypted, is encrypted using approved algorithms that provide
both confidentiality and integrity.
([C8](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Sensitive Data Encryption

**Story**:\
As a Security Engineer\
I want sensitive or private information to be encrypted\
So that we can ensure both confidentiality and integrity of our data

## Scenario

**Scenario_name**: Verifying Encryption of Sensitive Data

**Gherkin syntax**:

```gherkin
Given our application's data handling system
When I review the data encryption methods
Then it should show that sensitive or private information is encrypted
And it should use approved algorithms that provide both confidentiality and integrity
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/327>
