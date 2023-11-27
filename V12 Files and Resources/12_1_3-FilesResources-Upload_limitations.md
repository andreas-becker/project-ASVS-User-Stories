# V12.1 File Upload

## ASVS: 12.1.3

## ASVS Requirement description

Verify that a file size quota and maximum number of files per user
is enforced to ensure that a single user cannot fill up the
storage with too many files, or excessively large files.

## User Story

**Feature_Name**: User File Upload Limitations

**Story**:\
As a Security Engineer\
I want the application to enforce a file size quota and a maximum number of files per user\
So that a single user cannot overwhelm the storage with too many files or excessively large files

## Scenario

**Scenario_name**: Enforcing File Upload Limitations

**Gherkin syntax**:

```gherkin
Given our application has file upload capability
When a user attempts to upload a file
Then the application should check the file size and the number of files the user has already stored
And reject the upload if the file size or number of files exceeds the maximum allowed per user
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/770>
