# V14.1 Build and Deploy

## ASVS: 14.1.2

## ASVS Requirement description

Verify that compiler flags are configured to enable all available
buffer overflow protections and warnings, including stack
randomization, data execution prevention, and to break the build
if an unsafe pointer, memory, format string, integer, or string
operations are found.

## User Story

**Feature_Name**: Compiler Security Configurations

**Story**:
As a Security Engineer\
I want to ensure that our application's compiler flags are configured to enable all available
buffer overflow protections and warnings\
So that we can prevent potential security vulnerabilities during the build process

## Scenario

**Scenario_name**: Enforcing Secure Compiler Configurations

**Gherkin syntax**:

```gherkin
Given our application's build process
When a new version of the application is being compiled
Then the compiler should be configured to enable all available buffer overflow protections and warnings
And it should break the build if an unsafe pointer, memory, format string, integer, or string operations are found
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://owasp.org/www-project-web-security-testing-guide/v41/4-Web_Application_Security_Testing/02-Configuration_and_Deployment_Management_Testing/README.html> \
<https://cwe.mitre.org/data/definitions/120>