# V10.2 Malicious Code Search

## ASVS: 10.2.2

## ASVS Requirement description

Verify that the application does not ask for unnecessary or
excessive permissions to privacy related features or sensors,
such as contacts, cameras, microphones, or location.

## User Story

**Feature_Name**: Limiting Excessive Permissions

**Story**:\
As a Security Engineer\
I want to ensure that the application does not request unnecessary or excessive permissions\
So that we can protect user privacy and maintain data security.

## Scenario

**Scenario_name**: Verifying Absence of Excessive Permissions

**Gherkin syntax**:

```gherkin
Given our application's source code and third-party libraries
When I review the permissions requested by the application
Then it should not request unnecessary or excessive permissions to privacy-related features or sensors
And if such permissions are requested
Then the user's consent should be obtained before accessing these features or sensors
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/272>
