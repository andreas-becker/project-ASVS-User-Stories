# V14.2 Dependency

## ASVS: 14.2.5

## ASVS Requirement description

Verify that a Software Bill of Materials (SBOM) is maintained of
all third party libraries in use.
([C2](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Maintain Software Bill of Materials

**Story**:
As a Security Engineer\
I want to maintain a Software Bill of Materials (SBOM) of all third-party libraries used in our
application\
So that we can keep track of all components and ensure their integrity and security

## Scenario

**Scenario_name**: Verifying Maintenance of Software Bill of Materials

**Gherkin syntax**:

```gherkin
Given our application that uses third-party libraries
When a new library is added to the application
Then it should be added to the Software Bill of Materials (SBOM)
And the SBOM should be updated to reflect this change
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
