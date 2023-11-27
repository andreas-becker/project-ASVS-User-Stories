# V8.1 General Data Protection

## ASVS: 8.1.6

## ASVS Requirement description

Verify that backups are stored securely to prevent data from
being stolen or corrupted.

## User Story

**Feature_Name**: Secure Data Backup Storage

**Story**:\
As a Security Engineer\
I want to ensure that our backups are stored securely\
So that we can prevent our data from being stolen or corrupted

## Scenario

**Scenario_name**: Implementing Secure Backup Storage

**Gherkin syntax**:

```gherkin
Given our application's backup data
When it is being stored
Then the storage should be secure to prevent the data from being stolen or corrupted
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/19>
