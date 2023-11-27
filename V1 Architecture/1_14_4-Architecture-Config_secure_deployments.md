# V1.14 Configuration Architecture

## ASVS: 1.14.4

## ASVS Requirement description

Verify that the build pipeline contains a build step to
automatically build and verify the secure deployment of the
application, particularly if the application infrastructure is
software defined, such as cloud environment build scripts.

## User Story

**Feature_Name**: Automated Secure Deployment

**Story**:
As a Security Engineer\
I want the build pipeline to contain a build step that automatically builds and verifies the secure
deployment of the application, especially when the application infrastructure is software defined, 
like cloud environment build scripts\
So that we can ensure the security of our application deployment

## Scenario

**Scenario_name**: Verifying automated secure deployment in build pipeline

**Gherkin syntax**:

```gherkin
Given our application's build pipeline
When I review the pipeline process
Then it should contain a build step that automatically builds and verifies the secure deployment of the application
And this should be particularly true if the application infrastructure is software defined, like cloud environment build scripts
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links
