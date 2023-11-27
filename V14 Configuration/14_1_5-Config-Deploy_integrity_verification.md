# V14.1 Build and Deploy

## ASVS: 14.1.5

## ASVS Requirement description

Verify that authorized administrators can verify the integrity of all
security relevant configurations to detect tampering.

## User Story

**Feature_Name**: Configuration Integrity Verification

**Story**:
As a Security Engineer\
I want to ensure that authorized administrators can verify the integrity 
of all security-relevant configurations\
So that we can detect any tampering and maintain the security of our system

## Scenario

**Scenario_name**: Implementing Configuration Integrity Verification

**Gherkin syntax**:

```gherkin
Given our system's security-relevant configurations
When an authorized administrator reviews them
Then they should be able to verify the integrity of these configurations
And detect any signs of tampering
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
