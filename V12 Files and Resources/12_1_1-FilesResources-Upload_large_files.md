# V12.1 File Upload

## ASVS: 12.1.1

## ASVS Requirement description

Verify that the application will not accept large files that
could fill up storage or cause a denial of service.

## User Story

**Feature_Name**: Handle file uploads

**Story**:\
As a Security Engineer\
I want restrictions set on the files which can be uploaded to the application\
So that the application doesn't run out of resources to process the uploaded files.

## Scenario

**Scenario_name**: Do not accept large files

**Gherkin syntax**:

```gherkin
GIVEN the application has file upload capability
AND a maximum file size for uploaded files is defined
WHEN a file of size larger than the maximum defined size is uploaded into the application
THEN the file upload fails
AND and error message is displayed to that effect.
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/400>
