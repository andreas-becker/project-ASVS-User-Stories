# V12.2 File Integrity

## ASVS: 12.2.1

## ASVS Requirement description

Verify that files obtained from untrusted sources are validated
to be of expected type based on the file's content.

## User Story

**Feature_Name**: File Type Validation

**Story**:\
As a Security Engineer\
I want the application to validate files from untrusted sources\
So that we can ensure they are of the expected type based on their content

## Scenario

**Scenario_name**: Validating File Types from Untrusted Sources

**Gherkin syntax**:

```gherkin
Given our application receives files from untrusted sources
When a file is uploaded
Then the application should validate the file based on its content
And reject the upload if the file is not of the expected type
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
