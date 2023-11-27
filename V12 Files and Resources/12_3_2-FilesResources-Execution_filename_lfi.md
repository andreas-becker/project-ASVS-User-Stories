# V12.3 File Execution

## ASVS: 12.3.2

## ASVS Requirement description

Verify that user-submitted filename metadata is validated or
ignored to prevent the disclosure, creation, updating or removal
of local files (LFI).

## User Story

**Feature_Name**: File Safety Check

**Story**:\
As a Security Engineer\
I ensure the app checks and ignores certain file details from users\
So that we stop any potential issues, keeping our system secure

## Scenario

**Scenario_name**: Prevent disclosure or changes to local files

**Gherkin syntax**:

```gherkin
GIVEN the application has file uploaded capability
WHEN a file is uploaded to the application
THEN the file name is ignored
AND replaced with an application generated file name
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/73>
