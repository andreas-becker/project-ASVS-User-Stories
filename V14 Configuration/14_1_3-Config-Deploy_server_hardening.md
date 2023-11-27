# V14.1 Build and Deploy

## ASVS: 14.1.3

## ASVS Requirement description

Verify that server configuration is hardened as per the
recommendations of the application server and frameworks in use.

## User Story

**Feature_Name**: Server Configuration Hardening

**Story**:
As a Security Engineer\
I want to ensure that our server configuration is hardened according to the recommendations of the
application server and frameworks we use\
So that we can maintain a secure environment for our application

## Scenario

**Scenario_name**: Enforcing Server Configuration Hardening

**Gherkin syntax**:

```gherkin
Given our application's server and the frameworks in use
When the server is configured
Then the configuration should be hardened according to the recommendations of the application server and frameworks
And any non-compliant configurations should be flagged and corrected
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
<https://cwe.mitre.org/data/definitions/16>