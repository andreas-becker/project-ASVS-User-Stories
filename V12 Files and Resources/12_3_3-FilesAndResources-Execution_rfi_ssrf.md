# V12.3 File Execution

## ASVS: 12.3.3

## ASVS Requirement description

Verify that user-submitted filename metadata is validated or ignored to
prevent the disclosure or execution of remote files via Remote File Inclusion
(RFI) or Server-side Request Forgery (SSRF) attacks.

## User Story

**Feature_Name**: TBD

**Story**:\
As a Security Engineer\
I want to ...\
So that I ...

## Scenario

**Scenario_name**: Prevent disclosure or execution of files

**Gherkin syntax**:

```gherkin
GIVEN the application has file upload capability
AND the user submitted file names are validated or ignored
WHEN a request to remotely execute or disclose the file is made to the application
THEN the request is not serviced.
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/98>
