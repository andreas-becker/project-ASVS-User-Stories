# V12.5 File Download

## ASVS: 12.5.1

## ASVS Requirement description

Verify that the web tier is configured to serve only files with
specific file extensions to prevent unintentional information and
source code leakage. For example, backup files (e.g. .bak),
temporary working files (e.g. .swp), compressed files (.zip,
.tar.gz, etc) and other extensions commonly used by editors should
be blocked unless required.

## User Story

**Feature_Name**: Restricted file serving

**Story**:\
As a Security Engineer\
I want the application to securely handle requests to uploaded files
So that the application is less prone to information disclosure attacks

## Scenario

**Scenario_name**: Restricted file serving

**Gherkin syntax**:

```gherkin
GIVEN files can be downloaded from the application
WHEN a file download request is placed by the client
AND the requested file is a backup file (eg: .bak) or temporary working file (eg: .swp) or compressed files (eg: .zip, .tzr.gz)
THEN the request is denied
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
