# V10.2 Malicious Code Search

## ASVS: 10.2.1

## ASVS Requirement description

Verify that the application source code and third party libraries
do not contain unauthorized phone home or data collection
capabilities. Where such functionality exists, obtain the user's
permission for it to operate before collecting any data.

## User Story

**Feature_Name**: Unauthorized Data Collection Prevention

**Story**:\
As a Security Engineer\
I want to ensure that our application and any third-party libraries we use do not have any
unauthorized data collection capabilities\
So that we can protect our users' privacy and maintain the security of their data

## Scenario

**Scenario_name**: Verifying Absence of Unauthorized Data Collection

**Gherkin syntax**:

```gherkin
Given our application's source code and third-party libraries
When I review the code and libraries
Then they should not contain unauthorized data collection capabilities
And if such functionality exists
Then the user's permission should be obtained before collecting any data
```

## Validations

**Chef Inspec**

TBC

**OPA**

TBC

**External Tests**

TBC

## External links

<https://cwe.mitre.org/data/definitions/359>
