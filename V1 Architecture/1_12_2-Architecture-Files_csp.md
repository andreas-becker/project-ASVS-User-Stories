# V1.12 Secure File Upload Architecture

## ASVS: 1.12.2

## ASVS Requirement description

Verify that user-uploaded files - if required to be displayed or
downloaded from the application - are served by either octet 
stream downloads, or from an unrelated domain, such as a cloud
file storage bucket. Implement a suitable Content Security Policy
(CSP) to reduce the risk from XSS vectors or other attacks from
the uploaded file.

## User Story

**Feature_Name**: Secure File Upload

**Story**:
As a Security Engineer\
I want to ensure that user-uploaded files are served securely\
So that we can reduce the risk from potential attacks

## Scenario

**Scenario_name**: Verifying secure serving of user-uploaded files

**Gherkin syntax**:

```gherkin
Given our application's user-uploaded files
When I review their serving method
Then they should be served either by octet stream downloads or from an unrelated domain
And a suitable Content Security Policy (CSP) should be implemented
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
<https://cwe.mitre.org/data/definitions/646>