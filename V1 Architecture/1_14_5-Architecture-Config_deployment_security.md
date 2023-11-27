# V1.14 Configuration Architecture

## ASVS: 1.14.5

## ASVS Requirement description

Verify that application deployments adequately sandbox,
containerize and/or isolate at the network level to delay and
deter attackers from attacking other applications, especially
when they are performing sensitive or dangerous actions such as
deserialization.
([C5](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Application Deployment Security

**Story**:
As a Security Engineer\
I want to ensure that application deployments are adequately sandboxed, containerized and/or 
isolated at the network level\
So that we can delay and deter attackers from attacking other applications, especially when they 
are performing sensitive or dangerous actions such as deserialization

## Scenario

**Scenario_name**: Verifying security measures in application deployments

**Gherkin syntax**:

```gherkin
Given our application's deployment process
When I review the sandboxing, containerization, and network isolation measures
Then they should be adequate to delay and deter attackers from attacking other applications
And this should be particularly true when other applications are performing sensitive or dangerous
actions such as deserialization
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
<https://cwe.mitre.org/data/definitions/265>