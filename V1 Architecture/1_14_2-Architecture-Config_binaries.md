# V1.14 Configuration Architecture

## ASVS: 1.14.2

## ASVS Requirement description

Verify that binary signatures, trusted connections, and verified
endpoints are used to deploy binaries to remote devices.

## User Story

**Feature_Name**: Secure binary Deployment

**Story**:
As a Security Engineer\
I want to ensure that binary signatures, trusted connections, and verified endpoints are used when 
deploying binaries to remote devices\
So that we can maintain the security and integrity of our application

## Scenario

**Scenario_name**: Verifying secure deployment of binaries to remote devices

**Gherkin syntax**:

```gherkin
Given our application's binaries ready for deployment
When I review the deployment process
Then binary signatures should be used
And trusted connections should be established
And verified endpoints should be used for deployment
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
<https://cwe.mitre.org/data/definitions/494>