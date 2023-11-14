# V8.3 Sensitive Private Data

## ASVS: 8.3.1

## ASVS Requirement description

Verify that sensitive data is sent to the server in the HTTP message body or
headers, and that query string parameters from any HTTP verb do not contain
sensitive data.

## User Story

**Feature_Name**: Secure Data Transmission

**Story**:\
As a Security Engineer\
I want to make sure sensitive data is sent securely to the server, avoiding inclusion
in query string parameters\
So that we ensure the protection of user information during communication

## Scenario

**Scenario_name**: TBD

**Gherkin syntax**:

```gherkin
TBD
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/319>
