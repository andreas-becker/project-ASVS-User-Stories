# V14.1 Build and Deploy

## ASVS: 14.1.4

## ASVS Requirement description

Verify that the application, configuration, and all dependencies
can be re-deployed using automated deployment scripts, built from
a documented and tested runbook in a reasonable time, or restored
from backups in a timely fashion.

## User Story

**Feature_Name**: Automated and Reliable Deployment

**Story**:
As a Security Engineer\
I want to ensure that our application, its configuration, and all dependencies can be re-deployed
using automated deployment scripts\
So that we can maintain the integrity and consistency of our application, and restore from backups
in a timely fashion

## Scenario

**Scenario_name**: Implementing Automated and Reliable Deployment

**Gherkin syntax**:

```gherkin
Given our application's build and deployment processes
When a new version of the application is being deployed
Then the application, its configuration, and all dependencies should be re-deployed using automated deployment scripts
And it should be built from a documented and tested runbook in a reasonable time
And it should be restorable from backups in a timely fashion
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://owasp.org/www-project-web-security-testing-guide/v41/4-Web_Application_Security_Testing/02-Configuration_and_Deployment_Management_Testing/README.html>
