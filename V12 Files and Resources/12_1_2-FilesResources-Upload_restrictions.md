# V12.1 File Upload

## ASVS: 12.1.2

## ASVS Requirement description

Verify that the application checks compressed files (e.g. zip,
gz, docx, odt) against maximum allowed uncompressed size and
against maximum number of files before uncompressing the file.

## User Story

**Feature_Name**: File Upload Restrictions

**Story**:\
As a Security Engineer\
I want the application to check the size and number of files in a compressed file before
uncompressing\
So that the application resources are not overwhelmed by large or numerous files

## Scenario

**Scenario_name**: Handling Large Compressed Files

**Gherkin syntax**:

```gherkin
Given our application has file upload capability
When a compressed file is uploaded
Then the application should check the uncompressed size and number of files
And reject the upload if the size or number of files exceeds the maximum allowed
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/409>
