# V12.3 File Execution

## ASVS: 12.3.1

## ASVS Requirement description

Verify that user-submitted filename metadata is not used directly
by system or framework filesystems and that a URL API is used to
protect against path traversal.

## User Story

**Feature_Name**: Handle files securely

**Story**:\
As a Security Engineer\
I want the application to securely handle files\
So that the application is hardened against cyber-security attacks

## Scenario

**Scenario_name**: Protect against path traversal

**Gherkin syntax**:

```gherkin
GIVEN the application accesses a file during its operation
AND the filename is dynamically built with parameters that the user can control
AND the filename is normalized
AND the normalized filename is not identical to the dynamically build filename
WHEN a specially crafted request is sent to the server e.g. ``../../../etc/passwd`` instead of ``bob``
THEN the request fails
AND an entry is logged with relevant information to the use case
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/22>
