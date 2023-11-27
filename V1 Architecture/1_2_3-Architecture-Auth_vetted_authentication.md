# V1.2 Authentication Architecture

## ASVS: 1.2.3

## ASVS Requirement description

Verify that the application uses a single vetted authentication
mechanism that is known to be secure, can be extended to include
strong authentication, and has sufficient logging and monitoring
to detect account abuse or breaches.

## User Story

**Feature_Name**: Vetted Authentication Mechanism

**Story**:
As a Security Engineer\
I want to ensure that the application uses a single vetted authentication mechanism that is known 
to be secure, can be extended to include strong authentication, and has sufficient logging and
monitoring\
So that we can detect account abuse or breaches and maintain the security of our system

## Scenario

**Scenario_name**: Implementing a vetted authentication mechanism

**Gherkin syntax**:

```gherkin
Given our application components, services, and servers
When I implement a single vetted authentication mechanism that is known to be secure and can be extended to include strong authentication
And I ensure that it has sufficient logging and monitoring
Then account abuse or breaches can be detected
And the security of our system is maintained
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
<https://cwe.mitre.org/data/definitions/306>