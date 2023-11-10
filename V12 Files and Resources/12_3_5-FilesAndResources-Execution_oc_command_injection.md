# V12.3 File Execution

## ASVS: 12.3.5

## ASVS Requirement description

Verify that untrusted file metadata is not used directly with system API or
libraries, to protect against OS command injection.

## User Story

**Feature_Name**: TBD

**Story**:\
As a Security Engineer\
I want to ...\
So that I ...

## Scenario

**Scenario_name**: Prevent OS command injection

**Gherkin syntax**:

```gherkin
GIVEN the application has file upload capability
AND the user provided file metadata is not used in the application API
AND the user provided file metadata is not used in the application libraries
WHEN an OS command injection request is received
THEN the request is not serviced
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/78>
