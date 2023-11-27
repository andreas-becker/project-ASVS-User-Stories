# V12.3 File Execution

## ASVS: 12.3.6

## ASVS Requirement description

Verify that the application does not include and execute
functionality from untrusted sources, such as unverified content
distribution networks, JavaScript libraries, node npm libraries,
or server-side DLLs.

## User Story

**Feature_Name**: Prevent Execution from Untrusted Sources

**Story**:\
As a Security Engineer\
I want to ensure that our application does not execute functionality from untrusted sources\
So that we can maintain the security and integrity of our system

## Scenario

**Scenario_name**: Preventing Execution from Untrusted Sources

**Gherkin syntax**:

```gherkin
Given our application has file upload capability
When a file is uploaded
Then the application should verify the source of the file
And reject the upload if the source is untrusted
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/829>
