# V8.1 General Data Protection

## ASVS: 8.1.5

## ASVS Requirement description

Verify that regular backups of important data are performed and
that test restoration of data is performed.

## User Story

**Feature_Name**: Regular Data Backups and Restoration

**Story**:\
As a Security Engineer\
I want to ensure that regular backups of important data are performed
and that test restoration of data is also carried out\
So that we can safeguard our data and ensure its availability in case 
of any unforeseen incidents

## Scenario

**Scenario_name**: Implementing Regular Data Backup and Restoration

**Gherkin syntax**:

```gherkin
Given our application's important data
When a backup schedule occurs
Then a backup of the important data should be performed
And a test restoration of the data should also be carried out to verify the backup's integrity
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
