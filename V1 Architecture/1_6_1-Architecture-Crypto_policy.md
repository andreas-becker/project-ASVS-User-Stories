# V1.6 Cryptographic Architecture

## ASVS: 1.6.1

## ASVS Requirement description

Verify that there is an explicit policy for management of
cryptographic keys and that cryptographic key lifecycle follows
a key management standard such as NIST SP 800-57.

## User Story

**Feature_Name**: Cryptographic Key Management

**Story**:
As a Security Engineer\
I want to ensure that there is an explicit policy for the management of cryptographic keys and
that the lifecycle of these keys follows a key management standard such as NIST SP 800-57\
So that we can maintain the integrity and security of our cryptographic keys

## Scenario

**Scenario_name**: Implementing a policy for cryptographic key management

**Gherkin syntax**:

```gherkin
Given our application's cryptographic key processes
When I implement an explicit policy for the management of cryptographic keys
And ensure that the lifecycle of these keys follows a key management standard such as NIST SP 800-57
Then the integrity and security of our cryptographic keys are maintained
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