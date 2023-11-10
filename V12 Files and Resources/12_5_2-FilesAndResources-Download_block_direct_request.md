# V12.5 File Download

## ASVS: 12.5.2

## ASVS Requirement description

Verify that direct requests to uploaded files will never be executed as
HTML/JavaScript content.

## User Story

**Feature_Name**: TBD

**Story**:\
As a Security Engineer\
I want to ...\
So that I ...

## Scenario

**Scenario_name**: Restricted access to uploaded files

**Gherkin syntax**:

```gherkin
GIVEN the application as file upload capability
AND files are uploaded to the application
WHEN a request is placed by the client on the uploaded file
AND the request is received as HTML or Javascript content
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

<https://cwe.mitre.org/data/definitions/434>
