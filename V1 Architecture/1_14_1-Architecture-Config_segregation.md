# V1.14 Configuration Architecture

## ASVS: 1.14.1

## ASVS Requirement description

Verify the segregation of components of differing trust levels
through well-defined security controls, firewall rules, API
gateways, reverse proxies, cloud-based security groups, or similar
mechanisms.

## User Story

**Feature_Name**: Trust Level Segregation

**Story**:
As a Security Engineer\
I want to ensure that application components of different trust levels are properly segregated\
So that we can maintain a secure and reliable system

## Scenario

**Scenario_name**: Verifying segregation of components with differing trust levels

**Gherkin syntax**:

```gherkin
Given our application's components with different trust levels
When I review their segregation mechanisms
Then they should be properly segregated through security controls, firewall rules, API gateways,
reverse proxies, or similar mechanisms
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
<https://cwe.mitre.org/data/definitions/923>