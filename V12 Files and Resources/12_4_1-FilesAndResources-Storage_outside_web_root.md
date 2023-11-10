# V12.4 File Storage

## ASVS: 12.4.1

## ASVS Requirement description

Verify that files obtained from untrusted sources are stored outside the web
root, with limited permissions.

## User Story

**Feature_Name**: TBD

**Story**:\
As a Security Engineer\
I want the files uploaded to the application to be handled securely\
So that I reduce the risk of cyber attacks using files as vector.

## Scenario

**Scenario_name**: Untrusted file storage

**Gherkin syntax**:

```gherkin
GIVEN the application has file upload capability
WHEN a file is uploaded in to the application
THEN the file is stored outside the web root
AND the file has limited permissions
AND the file is validated
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/552>
