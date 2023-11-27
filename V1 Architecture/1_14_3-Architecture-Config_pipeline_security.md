# V1.14 Configuration Architecture

## ASVS: 1.14.3

## ASVS Requirement description

Verify that the build pipeline warns of out-of-date or insecure
components and takes appropriate actions.

## User Story

**Feature_Name**: Build Pipeline Security

**Story**:
As a Security Engineer\
I want the build pipeline to alert us about outdated or insecure components\
So that we can take appropriate actions to maintain the security of our application

## Scenario

**Scenario_name**: Verifying alert mechanism for insecure components in build pipeline

**Gherkin syntax**:

```gherkin
Given our application's build pipeline
When I review the pipeline process
Then it should warn us about out-of-date or insecure components
And it should take appropriate actions to address these issues
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
<https://cwe.mitre.org/data/definitions/1104>