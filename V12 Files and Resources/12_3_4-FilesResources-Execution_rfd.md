# V12.3 File Execution

## ASVS: 12.3.4

## ASVS Requirement description

Verify that the application protects against Reflective File
Download (RFD) by validating or ignoring user-submitted
filenames in a JSON, JSONP, or URL parameter, the response
Content-Type header should be set to text/plain, and the
Content-Disposition header should have a fixed filename.

## User Story

**Feature_Name**: Guard Against Reflective File Download

**Story**:\
As a Security Engineer\
I ensure the app defends against RFD by handling user-submitted filenames carefully\
So that we include setting specific headers for a safe user experience

## Scenario

**Scenario_name**: TBD

**Gherkin syntax**:

```gherkin
TBD
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/641>
