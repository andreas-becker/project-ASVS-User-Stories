# V1.4 Access Control Architecture

## ASVS: 1.4.1

## ASVS Requirement description

Verify that trusted enforcement points, such as access control
gateways, servers, and serverless functions, enforce access
controls. Never enforce access controls on the client.

## User Story

**Feature_Name**: Trusted Enforcement Points Access Control

**Story**:
As a Security Engineer\
I want to ensure that trusted enforcement points, such as access control gateways, servers, and 
serverless functions, enforce access controls\
So that we can maintain the integrity and security of our system without relying on client-side
controls

## Scenario

**Scenario_name**: Enforcing access controls at trusted enforcement points

**Gherkin syntax**:

```gherkin
Given our system's trusted enforcement points
When I enforce access controls at these points
Then the integrity and security of our system is maintained
And we do not rely on client-side controls
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
<https://cwe.mitre.org/data/definitions/602>