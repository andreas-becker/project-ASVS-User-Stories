# V12.4 File Storage

## ASVS: 12.4.2

## ASVS Requirement description

Verify that files obtained from untrusted sources are scanned by antivirus
scanners to prevent upload and serving of known malicious content.

## User Story

**Feature_Name**: TBD

**Story**:\
As a Security Engineer\
I want to ...\
So that I ...

## Scenario

**Scenario_name**: Malware scan for uploaded files

**Gherkin syntax**:

```gherkin
GIVEN the application has file uploaded capability
AND content inspection is enabled at the network infrastructure
OR malware inspection is enabled at the file origin
WHEN a malware infected file is uploaded in to the application
THE the upload fails
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/509>
