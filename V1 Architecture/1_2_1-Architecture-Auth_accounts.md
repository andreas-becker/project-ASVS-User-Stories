# V1.2 Authentication Architecture

## ASVS: 1.2.1

## ASVS Requirement description

Verify the use of unique or special low-privilege operating
system accounts for all application components, services, and 
servers.
([C3](https://owasp.org/www-project-proactive-controls/#div-numbering))

## User Story

**Feature_Name**: Low-Privilege Operating System Accounts

**Story**:
As a Security Engineer\
I want to ensure the use of unique or special low-privilege operating system accounts for all 
application components, services, and servers\
So that we can minimize the potential damage from a compromised service or server

## Scenario

**Scenario_name**: Implementing low-privilege operating system accounts

**Gherkin syntax**:

```gherkin
Given our application components, services, and servers
When I implement unique or special low-privilege operating system accounts
Then the potential damage from a compromised service or server is minimized
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
<https://cwe.mitre.org/data/definitions/250>